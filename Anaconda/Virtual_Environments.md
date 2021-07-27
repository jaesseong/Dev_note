# 아나콘다 환경에서 가상환경 사용하기
모든 코드는 `Anaconda prompt(anaconda3)`에서 실행되었습니다.

# 목차

# 가상환경 생성
```
conda create -n [가상환경 이름] python
```

# 가상환경 활성화
```
conda activate [가상환경 이름]
```

# 가상환경에 jupyter notebook 설치하기
```
pip install jupyter notebook
pip install ipykernel
```
jupyter notebook를 설치할 때, ipykernel은 함께 설치되니 jupyter만 설치하여도 무방

# 가상환경에 kernel 연결하기
```
python -m ipykernel install --user --name [가상환경 이름] --display-name [표시할이름]
```

# jupyter notebook에서 가상환경 kernel 연결 오류
 - jupyter cmd 창에서 win32api 모듈 에러를 발견한 경우
    ```
    conda install -c anaconda pywin32
    ```
    
