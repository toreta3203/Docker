# **Docker Container 생성 순서**

## **1. Docker Container 생성 순서**
1. Docker Client에 "docker run [Image]" 명령어 입력
2. 도커 이미지의 파일 스냅샷을 컨테이너 하드디스크로 복사

<p align = "center">
    <img src="Pictures\Container create_1.jpg">
    </p>
    <p align = "center"> # Container Create 1</p>

3. 도커 이미지에서 가지고 있는 명령어를 컨테이너에 전달

<p align = "center">
    <img src="Pictures\Container create_2.jpg">
    </p>
    <p align = "center"> # Container Create 2</p>

4. 컨테이너가 실행될 때 명령어를 이용해 애플리케이션을 실행

<p align = "center">
    <img src="Pictures\Container create_3.jpg">
    </p>
    <p align = "center"> # Container Create 3</p>
