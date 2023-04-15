# **Docker rm, docker rmi**

## **1. Docker rm**
* 도커 컨테이너 삭제하기 - docker rm <중지할 컨테이너 ID/이름>
* rm은 remove의 약자
* rm 명령어는 컨테이너가 중지된 상태여야 삭제할 수 있다.

<p align = "center">
    <img src="Pictures\CMD_docker run alpine ping google.com.jpg">
    </p>
    <p align = "center"> # ping test</p>

<p align = "center">
    <img src="Pictures\CMD_docker rm_error.jpg">
    </p>
    <p align = "center"> # docker rm error</p>

<p align = "center">
    <img src="Pictures\CMD_docker rm_correct.jpg">
    </p>
    <p align = "center"> # docker rm correct</p>

**▶ 중지된 모든 컨테이너 삭제하기**
* docker rm 'docker ps -a -q'

<br>

***

## **2. Docker rmi**
* 도커 이미지 삭제하기 - docker rmi <이미지 ID>
* 도커 이미지 나열 - docker images

<p align = "center">
    <img src="Pictures\CMD_docker rmi.jpg">
    </p>
    <p align = "center"> # docker rmi</p>
