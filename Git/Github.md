# [Github](github.com)

-----

## Github란?

깃허브<sup>Github</sup>는 분산 버전 컨트롤 소프트웨어 깃<sup>Git</sup>을 기반으로 소스 코드를 호스팅하고, 협업 지원 기능들을 지원하는 마이크로소프트<sup>Microsoft</sup>의 웹서비스

![Github logo](C:\Users\wotjd\TIL\2021-06-29\image\github-seeklogo.com.svg "Github logo")





## 원격 저장소와 로컬 저장소

깃<sup>Git</sup>은 원격 저장소와 로컬 저장소 두 종류의 저장소를 제공

- 원격 저장소<sup>Remote Repository</sup>: 파일이 원격 저장소 전용 서버에서 관리되며 여러 사람이 함께 공유하기 위한 저장소
- 로컬 저장소<sup>Local Repository</sup>: 내 PC에 파일이 저장되는 개인 전용 저장소



## 깃허브<sup>Github</sup> 튜토리얼

1. [깃<sup>Git</sup> 설치](https://git-scm.com/) + [깃허브<sup>Github</sup> 회원가입](https://github.com/)
2. 로그인 후 레파지토리<sup>repository</sup>(원격 저장소<sup>Remote Repository</sup>) 만들기 
   1. 홈에서 오른 쪽 상단 자신의 프로필 클릭 <br/> <p align="center">![github_tutorial_001](C:\Users\wotjd\TIL\Git\image\github_tutorial_001.PNG)</p>
   2. your repositories 클릭 <br/><p align="center">![github_tutorial_002](C:\Users\wotjd\TIL\Git\image\github_tutorial_002.PNG)</p>
   3. 
   4. New 클릭</br><p align="center">![github_tutorial_003](C:\Users\wotjd\TIL\Git\image\github_tutorial_003.PNG)</p>
   5. 레파지토리 이름 및 설명 작성</br><p align="center">![github_tutorial_004](C:\Users\wotjd\TIL\Git\image\github_tutorial_004.PNG)</p>
   6. Readme file 추가하기</br> <p align="center">![github_tutorial_005](C:\Users\wotjd\TIL\Git\image\github_tutorial_005.PNG)</p>
   7. 생성 완료
3.  로컬 저장소<sup>Local Repository</sup> 생성
   1. 원하는 곳에 폴더 생성
   2. Git Bash에 들어가기
      1.  생성한 폴더로 이동</br>`cd 폴더명`
      2.  메인 브렌치 명 변경</br> `git config --global init.defaultBranch main`
      3.  폴더를 로컬 깃 저장소로 등록</br> `git init`
      4.  사용자 정보 등록</br> `git config --global user.name "User Name"</br>git config --global user.email useremail@example.com`
   3. 



