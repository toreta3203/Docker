# **Docker stop, docker kill**

## **1. Docker stop**
* 도커 컨테이너 중지시키기 - docker stop <중지할 컨테이너 ID/이름>
* stop은 Graceful하게 컨테이너를 중지시킨다.
* 그동안 하던 작업들을 모두 마치고 컨테이너를 중지시키는 것

<p align = "center">
    <img src="Pictures\docker stop_process.jpg">
    </p>
    <p align = "center"> # Docker stop</p>

<br>

***

## **2. Docker kill**
* 도커 컨테이너 중지시키기 - docker kill <중지할 컨테이너 ID/이름>
* kill은 stop과 달리 어떠한 것도 기다리지 않고 즉시 컨테이너를 중지시킨다

<p align = "center">
    <img src="Pictures\docker kill_process.jpg">
    </p>
    <p align = "center"> # docker kill</p>

### **# 실습**

docker run alpine ping google.com

docker ps

docker stop <container ID / 이름><br>
// 작업을 중지 시키고 컨테이너를 중지시키기 때문에 몇 초 후에 중지된다

docker run alpine ping google.com

docker ps

docker kill <container ID / 이름><br>
// docker stop과 달리 바로 컨테이너가 중지됨

