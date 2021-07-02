# Power BI Tutorial

# 목차

# Power BI 란?
관련없는 데이터 소스를 시각적으로 몰입도가 뛰어나고 일관된 대화형 정보로 변환하는 소프트웨어 서비스, 앱 및 커넥터의 컬렉션이다.

# Power BI 설치
  1. [Power BI](https://powerbi.microsoft.com/ko-kr/downloads/) 사이트 접속 
  2. Microsoft Power BI Desktop 설치

# Power BI 튜토리얼
  ## csv 데이터 가져오기 
  - [포스트 코로나 데이터](https://dacon.io/competitions/official/235618/overview/description) 다운로드 
    <div align="center">
      <img src="./image/import_csv_data_001.PNG" alt="import_csv_data_001">
      <img src="./image/import_csv_data_002.PNG" alt="import_csv_data_002">
    </div>
  
  - Power BI로 Index.csv 파일 불러오기
  
    <div align="center">  
      <img src="./image/import_csv_data_003.PNG" alt="import_csv_data_003">
      <img src="./image/import_csv_data_004.PNG" alt="import_csv_data_004">
      <img src="./image/import_csv_data_005.PNG" alt="import_csv_data_005">
    </div>
  
  ## csv 데이터 전처리
   
  - 새 열 만들기
    1. 데이터 창으로 이동
    2. 새 열 추가
    
    <div align="center">
      <img src="./image/preprocessing_csv_data_001.PNG" alt="preprocessing_csv_data_001">
    </div>  
    
    3. 새 열의 값을 생성하기위해 컬럼명 클릭
    4. 값을 생성하기 위한 해당하는 함수를 입력  
      
    <div align="center">  
      <img src="./image/preprocessing_csv_data_002.PNG" alt="preprocessing_csv_data_002">
    </div>
  
  
  - 새 열의 값 생성하기 (**④**에 입력)
    * year 열
  
          year = LEFT([period, 4])
    
    * momth 열
          
          month = RIGHT([period], 2) 
  
    * day 열
      
          day = [year]&"-"&[month]
      
      <div align="center">
          <img src="./image/preprocessing_csv_data_003.PNG" alt="preprocessing_csv_data_003">
      </div>
    
    * rising_falling 열
      
          rising_falling = IF([cgi] > 100, rising, falling)
          
    * rising 열
        
          rising = IF([rising_falling] = "rising", 1, 0)
          
    * falling 열
    
          falling = IF([rising_falling] = "falling", 1, 0)
    
  
  ## 지도 데이터 가져오기
  [행정구역 데이터](http://data.nsdi.go.kr/dataset/15144)
  <div align="center">
      <img src="./image/import_map_data_001.PNG" alt="import_map_data_001">
  </div>  
  
  ## 지도 데이터 전처리
  
  - 지도 데이터 [QGIS](../QGIS/qgis_tutorial.md)로 불러오기
    - 레이어 -> 레이어 추가 -> 벡터 레이어 추가
      <div align="center">
          <img src="./image/preprocessing_map_data_001.PNG" alt="preprocessing_map_data_001">
      </div> 
      
    - 지도 파일 열기
    
      <div align="center">    
          <img src="./image/preprocessing_map_data_002.PNG" alt="preprocessing_map_data_002">
          <img src="./image/preprocessing_map_data_003.PNG" alt="preprocessing_map_data_003">
          <img src="./image/preprocessing_map_data_004.PNG" alt="preprocessing_map_data_004">
      </div>  
    
  - csv에 있는 값과 매칭하기 위해 값 수정하기
    - 속성 테이블 열기
      <div align="center">
          <img src="./image/preprocessing_map_data_005.PNG" alt="preprocessing_map_data_005">
      </div>
    - 수정할 행 선택 및 수정 창 열기  
      <div align="center">
          <img src="./image/preprocessing_map_data_006.PNG" alt="preprocessing_map_data_006">
      </div>
    - 수정하기
        1. 기존 정보 갱신 선택
        2. SGG_NM 선택
        3. 문자열 -> right 더블 클릭
        4. 필드와 값 -> SGG_NM 더블 클릭
        5. `right("SGG_NM", 3)` 코드 작성
        6. 확인
      <div align="center">    
          <img src="./image/preprocessing_map_data_007.PNG" alt="preprocessing_map_data_007">
      </div> 
    
    
    
  
  
  
