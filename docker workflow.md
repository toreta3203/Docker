# **Docker Workflow**

## **1. Docker Workflow**

<p align = "center">
    <img src="Pictures\docker workflow.jpg">
    </p>
    <p align = "center"> # docker workflow </p>

1. 도커 클라이언트(CLI)에 명령어 입력
2. 도커 서버(도커 데몬)가 도커 클라이언트에 입력한 명령어를 전달 받으면 명령어에 따른 이미지 생성, 컨테이너를 실행, 그리고 해당 컨테이너에서 애플리케이션을 실행

<br>

---

## **2. Docker hello-world workflow**

<p align = "center">
    <img src="Pictures\hello-world workflow.jpg">
    </p>
    <p align = "center"> # hello-world workflow </p>

1. 도커 클라이언트에 명령 입력 시 도커 서버로 요청 전송
2. 서버에서 hello-world의 이미지가 로컬에 다운로드되어 있는지 확인
3. 내려받은 hello-world 이미지가 없기 때문에 'Unable to find image 'hello-world:latest' locally' 라는 문구 출력 (2번째 줄)
4. 도커 이미지가 저장된 도커 허브(Docker Hub)에서 hello-world 이미지를 가져오고, 로컬에 보관
5. 이 이미지를 이요해 컨테이너 생성
6. 생성된 컨테이너는 이미지에서 받은 설정이나 조건에 따라 프로그램 실행

<p align = "center">
    <img src="Pictures\CMD_docker run hello-world.jpg">
    </p>
    <p align = "center"> # docker run hello-world </p>

### **▶ docker run hello-world 두번 쨰 입력 시**

<p align = "center">
    <img src="Pictures\CMD_docker run hello-world_second.jpg">
    </p>
    <p align = "center"> # docker run hello-world_second </p>
