# **Docker iamge create**

## **1. Docker Iamge 생성**
* 직접 도커 이미지 생성하기
* 도커 이미지 - 컨테이너를 만드는 데 필요한 설정이나 종속성을 가진 소프트웨어 패키지
* docker create [이미지 이름]

<br>

***

## **2. Docker Image 생성 순서**

1. 도커 파일 작성 - 도커 이미지를 만들기 위한 설정 파일, 도커 컨테이너가 어떻게 행동해야 하는지에 대한 설정을 정의하는 곳
2. 도커 클라이언트 - 도커 파일에 입력된 명령어들이 도커 클라이언트에 전달되야 한다.
3. 도커 서버 - 도커 클라이언트에 전달된 모든 중요한 작업들을 하는 곳
4. 이미지 생성

## **3. Dockerfile 만들기**

1. 베이스 이미지를 명시
2. 베이스 이미지 이외에 Application 실행하는 데 필요한 파일들을 이미지 안에 내려받기 위한 명령어 명시
3. 컨테이너 시작 시에 실행할 명령어 명시<br>

**→ 베이스 이미지 (Base Image)** - 이미지를 만들기 위한 기본 이미지, 일반적으로 OS (Windows, MacOS, Linux 등)

<p align = "center">
    <img src="Pictures\Docker Image.jpg">
    </p>
    <p align = "center"> # Docker Iamge 구성</p>

<br>

<p align = "center">
    <img src="Pictures\Docker Image create.jpg">
    </p>
    <p align = "center"> # Docker Iamge 만들기</p>

<br>

* FROM
  * 이미지 생성 시 기반이 되는 이미지
  * <이미지 이름>:<태그> 형식으로 작성
  * 태그를 붙이지 않으면 자동으로 가장 최신 버전으로 내려받는다.

* RUN
  * 도커 이미지가 생성되기 전에 수행할 셀 명령어

* CMD
  * 컨테이너가 시작됐을 때 실행할 실행 파일 또는 셀 스크립트
  * 이 명령어는 도커 파일 내에서 한 번만 쓸 수 있다.

<p align = "center">
    <img src="Pictures\CMD_docker build . Buildkit X.jpg">
    </p>
    <p align = "center"> # Docker build . Buildkit 사용하지 않을 경우</p>

<p align = "center">
    <img src="Pictures\Docker Build.jpg">
    </p>
    <p align = "center"> # Docker build Process</p>


## **4. 도커 이미지에 이름 붙여주기**

* 도커 이미지에 이름을 붙이려면 -t 태그를 이용해야 한다.
* docker build -t 저장소/프로젝트 이름:버전
  
  <p align = "center">
    <img src="Pictures\CMD_docker build -t.jpg">
    </p>
    <p align = "center"> # Docker build -t </p>
