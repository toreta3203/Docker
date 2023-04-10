# **docker ps**

## **1. docker ps**
* docker ps<br>
→ docker<br>
→ ps - process status 의 약자
* docker ps -a<br>
// 모든 도커 컨테이너를 나열

<p align = "center">
    <img src="Pictures\CMD_docker run alpine ping google.com.jpg">
    </p>
    <p align = "center"> # docker run alpine ping google.com </p>


<p align = "center">
    <img src="Pictures\CMD_docker ps.jpg">
    </p>
    <p align = "center"> # docker ps </p>

→ CONTAINER ID - 컨테이너의 고유한 아이디 해시값 (일부분만 출력되는 것)

→ IMAGE - 컨테이너 생성 시 사용한 도커 이미지 이름

→ COMMAND - 컨테이너 시작 시 실행될 명령어, 대부분 이미지에 내장돼 있으므로 별도 설정이 필요하지 않다.

→ CREATE - 컨테이너가 생성된 시각

→ STATUS - 컨테이너의 상태. UP (실행 중), Exited (종료), Pause (일시 정지)

→ PORT - 컨테이너가 개방한 포트와 호스트에 연결한 포트, 특별한 설정 하지 않은 경우 출력되지 않는다.

→ NAME - 컨테이너의 고유한 이름. 컨테이너 생성 시 --name 옵션으로 이름을 설정하지 않으면 도커 엔진이 임의로 형용사와 명사를 조합해 설정함.
'docker rename' 명령어로 이름을 변경 가능 (doker rename <원래 이름> <변경할 이름>) 

