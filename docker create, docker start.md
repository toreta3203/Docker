# **Docker create / docker start**

## **1. Docker create**
* 도커 생성하기 - docker create <이미지 이름>

<p align = "center">
    <img src="Pictures\Container create_1.jpg">
    </p>
    <p align = "center"> # Container Create</p>

<br>

***

## **2. Docker start**
* 생성된 도커 컨테이너 실행하기 - docker start <컨테이너 ID/이름>

<p align = "center">
    <img src="Pictures\Container create_2.jpg">
    </p>
    <p align = "center"> # Container start</p>

* docker start -a <컨테이너 ID/이름>
* -a = attach 의 약자로 컨테이너를 실행한 후에 표준 입력(stdin), 표준 출력(stdout), 표준 에러(stderr)
* 를 가능하게 하며, 프로그램으로 입력 받은 내용을 터미널에 보여주는 역할

<p align = "center">
    <img src="Pictures\CMD_docker start -a.jpg">
    </p>
    <p align = "center"> # Container start 와 start -a 차이점</p>