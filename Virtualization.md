# Virtualization
## **1. Virtualization**
* 단일 컴퓨터의 하드웨어 요소를 VM이라고 하는 다수의 가상 컴퓨터로 분할할 수 있도록 해주는 기술
* 물리적 컴퓨터 하드웨어를 보다 효율적으로 활용할 수 있도록 해주는 프로세스

<br>

***

## **2. 전가상화 (Full-Virtualization)**
* 하드웨어를 완전히 가상화하는 방식
* GuestOS가 하드웨어에 접근하면서 제어를 요구한다
* 이 때 CPU는 가상화 지원하는지 확인하는데, 지원하지 않으면 GuestOS는 아예 운영 X
* 지원 가능하면 하드웨어 제어를 요구하고, 그 이후 하드웨어 제어를 할수 있게 된다.
* 하이퍼바이저를 구동하면 DOM0라는 관리용 가상머신이 구동되고 모든 가상머신의 하드웨어 접근이 DOM0로 이루어진다.
* GeustOS가 각각의 언어로 요청하는 모든 명령들을 하이퍼바이저가 번역하여 하드웨어에 전달 (DOM0가 개입한다)

→ **하이퍼바이저 (Hypervisor)** - OS와 하드웨어 사이에 존재하는 일종의 가상화 매니저

<p align = "center">
    <img src="Pictures\Full Virtualization.jpg">
    </p>
    <p align = "center"> # Full Virtualization </p>

<br>

***

## **3. 반가상화 (Para-Virtualization)**
* 하드웨어를 완전히 가상화하지 않고 전가상화의 성능저하를 해결하기 위해 하이퍼콜(Hyper Call)이라는 인터페이스를 통해 하이퍼바이저에게 직접 요청한다.
* GuestOS의 커널을 수정하여 이런 역학이 가능하도록 만들어야 한다.
* 


