# **Docker exec**

## **1. Docker exec**
* 실행 중인 컨테이너에 명령어 전달하기 - docker exec <컨테이너 ID>
  
<p align = "center">
    <img src="Pictures\CMD_docker run alpine ping google.com.jpg">
    </p>
    <p align = "center"> # ping test</p>

<p align = "center">
    <img src="Pictures\CMD_docker exec.jpg">
    </p>
    <p align = "center"> # docker exec ls</p>

<br>

***

## **2. redis를 이용해 exec 활용**

<p align = "center">
    <img src="Pictures\CMD_docker run redis.jpg">
    </p>
    <p align = "center"> # docker run redis</p>

<p align = "center">
    <img src="Pictures\CMD_docker exec -it redis-cli.jpg">
    </p>
    <p align = "center"> # docker exec -it redis-cli</p>

* -i (interactive)
* -t (terminal)

* 실행 중인 컨테이너에 셀 환경으로 접속 - docker exec -it <컨테이너 ID> sh
* Control + D 로 쉘 환경에서 빠져나올 수 있다.

<p align = "center">
    <img src="Pictures\CMD_docker run alpine ping google.com.jpg">
    </p>
    <p align = "center"> # docker run alpine ping google.com </p>

<p align = "center">
    <img src="Pictures\CMD_docker exec -it container sh.jpg">
    </p>
    <p align = "center"> # docker exec -it [Container ID] sh </p>
