# **Docker Buildkit**

## **1. Docker Buildkit**
* 18.09부터 도커 파일을 이용해 토커 이미지를 빌드할 때 Buildkit을 기본적으로 사용
* 도커 파일을 빌드할 때 더 빠른 속도로, 더 효율적으로 빌드할 수 있게 해준다.

## **2. Buildkit을 이용했을 때 차이점**


<p align = "center">
    <img src="Pictures\CMD_docker build . Buildkit O.jpg">
    </p>
    <p align = "center"> # Docker build . Builkit 사용할 경우</p>

<br>

<p align = "center">
    <img src="Pictures\Docker buildkit settings.jpg">
    </p>
    <p align = "center"> # Docker buildkit settings</p>

* buildkit : true - 기본 설정 값<br>
* buildkit : false - buildkit을 사용하지 않겠다.

<br>

<p align = "center">
    <img src="Pictures\CMD_docker build . Buildkit X.jpg">
    </p>
    <p align = "center"> # Docker build . Buildkit 사용하지 않을 경우</p>


