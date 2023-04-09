# **Docker Cgroup and Namespace**

## **1. Docker Cgroup and Namespace**
* 프로세스들 사이에 벽을 만드는 리눅스 커널의 기능

▶ Cgroup - CPU, 메모리, 네트워크 대역폭, HD I/O 등 프로세스 그룹의 시스템 리소스 사용량을 관리한다.<br>
EX) 어떤 애플리케이션의 사용량이 너무 많다면 Cgroup에 배치해서 CPU와 메모리 사용을 제한할 수 있다.
▶ Namespace - 하나의 시스템에서 프로세스를 격리시킬 수 있는 가상화 기술로 별개의 독립된 공간을 사용하는 것처럼 격리된 환경을 제공하는 경량 프로세스 가상화 기술

<p align = "center">
    <img src="Pictures\Container_1.jpg">
    </p>
    <p align = "center"> # Container 1 </p>

<p align = "center">
    <img src="Pictures\Container_2.jpg">
    </p>
    <p align = "center"> # Container 2 </p>
