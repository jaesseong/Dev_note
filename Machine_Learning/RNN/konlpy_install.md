# Konlpy Installation

# 목차

# Java

## Java 설치
[이 곳](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)에서 Java를 자신의 컴퓨터의 비트에 맞춰 설치

## 환경 변수 설정
내 PC -> 속성 -> 고급 시스템 설정 -> 환경변수 -> 사용자 변수 추가   
변수 이름 : `JAVA_HOME`  
변수 값 : `C:\Program Files\Java\jdk-11.0.12\bin\server`  
변수 값에는 `jvm.dll` 파일의 위치를 넣는 것이 필자는 작동하였다.

# Visual Studio

## Visual Studio 설치1
[이 곳](https://visualstudio.microsoft.com/ko/vs/older-downloads/)에서 재배포 가능 패키지 및 빌드 도구를 들어가자
그런 다음, **Microsoft Build Tools 2015 업데이트 3**를 다운로드 해주자.

## Visual Studio 설치2
첫 번째 방법이 되지 않는 분들은 [이 곳](https://visualstudio.microsoft.com/ko/)에서 Visual Studio community version을 설치하도록 하자  
![visual_studio_001](./img/visual_studio_001.png)   


# jpype 설치
conda 명령어를 이용하여 설치하는 방법도 있으나 오류가 발생하니 공식 문서에 있는 방법을 사용하자  

먼저, python의 version이 3.9 **미만**이어야 한다.
prompt에서 `python --vesion` 명령어를 통해 확인하자

그런 다음, prompt에서 pip를 업그레이드 해주자
```
pip install --upgrade pip
```
[이 곳](https://remotedesktop.google.com/access/session/4ff206a0-c8a6-e5ae-5d9b-bc8ea5ba1373)에 들어가서 자신의 python 버전에 맞는 1.3.0 version **미만**의 jpype를 다운로드 해주자.  
필자는 python이 3.8 version 이였으므로 `JPype1‑1.1.2‑cp38‑cp38‑win_amd64.whl`를 다운로드하였다.
```
pip install C:\Users\dfdfs\Downloads\JPype1‑1.1.2‑cp38‑cp38‑win_amd64.whl
```

# Konlpy 설치
~~그디어 마지막이다.~~
```
pip install konlpy
```
