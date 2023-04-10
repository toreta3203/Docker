# **docker run ls**

## **1. docker run ls**
* docker run <이미지> ls<br>
→ docker<br>
→ run - 컨테이너 생성 및 실행<br>
→ <이미지> - 이 컨테이너를 위한 이미지<br>
→ ls - 이미지의 기본 시작 명령어 대신 실행할 명령어 (ls는 파일 목록 출력)


<p align = "center">
    <img src="Pictures\CMD_docker run ls.jpg">
    </p>
    <p align = "center"> # docker run alpine ls </p>

<p align = "center">
    <img src="Pictures\CMD_docker run hello-world ls_error.jpg">
    </p>
    <p align = "center"> # docker run hello-world ls_error </p>

→ hello-world 이미지에 ls를 사용할 수 있는 파일이 없기 때문에 에러 발생
