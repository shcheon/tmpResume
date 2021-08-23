# Interview 준비

# RDBMS

## Database

- 데이터베이스
  - 데이터베이스를 사용하는 이유
  - 데이터베이스 성능
- Index
  - Index 란 무엇인가
  - Index 의 자료구조
  - Primary index vs Secondary index
  - Composite index
  - Index 의 성능과 고려해야할 사항
- 정규화에 대해서
  - 정규화 탄생 배경
  - 정규화란 무엇인가
  - 정규화의 종류
  - 정규화의 장단점
- Transaction
  - 트랜잭션(Transaction)이란 무엇인가?
  - 트랜잭션과 Lock
  - 트랜잭션의 특성
  - 트랜잭션의 상태
  - 트랜잭션을 사용할 때 주의할 점
- Statement vs PreparedStatement
- NoSQL
  - 정의
  - CAP 이론
    - 일관성
    - 가용성
    - 네트워크 분할 허용성
  - 저장방식에 따른 분류
    - Key-Value Model
    - Document Model
    - Column Model

[참조](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Database)



## Oracle Database

- Database Server
- Database Instance
- System Global Area
- Program Global Area
- Background Process
- Shared Pool
- Large Pool
- Database Buffer Cache
- In-memory Area

[참조](https://www.oracle.com/webfolder/technetwork/tutorials/architecture-diagrams/19/pdf/db-19c-architecture.pdf)

- 11g -> 19c 변경점

- SQL 파싱 과정 

- SQL 처리 순서

  -  **1. FROM> 2.** **WHERE****> 3.** **GROUP BY****> 4.** **HAVING** **> 5.** **SELECT** **> 6. ORDER BY**

    [참조](https://mine-it-record.tistory.com/66)

- Data Structure

  - 인덱스
  - B*Tree
  - Bitmap

- 정규화

- 트랜잭션

  

## SQL Lite

- 



## MySQL

- 



## SQL Tuning

- I/O 최소화
- 인덱스 튜닝
- 조인튜닝
- 소트 튜닝
- SQL 옵티마이저
- 파티션 튜닝



# Image Processing

- Image Enhancement
- 



# Graphic

- OpenGL



## Android

- Component
- Design Pattern



# WEB

## Spring

- MVC Pattern
- IoC Container
- Dependency Injection
- AOP
- Value Object, Data Access Object ,Data Transfer Object
- Design Pattern : Singleton, Factory Method, Proxy Pattern, Template Method



[참조](https://velog.io/@dev_osj/Design-Pattern-in-Spring)



## PHP

- 



## HTML

- 



## JavaScript

- JavaScript Event Loop
- Hoisting
- Closure
- this 에 대해서
- Promise

[참조](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/JavaScript)



## Front-end

- 브라우저의 작동 원리
- Document Object Model
  - Event Bubbling and Capturing
  - Event delegation
- CORS
- 크로스 브라우징
- 웹 성능과 관련된 Issues
- 서버 사이드 렌더링 vs 클라이언트 사이드 렌더링
- CSS Methodology
- normalize.css vs reset.css
- 그 외 프론트엔드 개발 환경 관련

[참조](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/FrontEnd)





# Network

- GET, POST 방식의 차이점
- TCP 3-way-handshake
- TCP 와 UDP 의 차이점
- HTTP 와 HTTPS 의 차이점
  - HTTP 의 문제점들
- DNS round robin 방식
- 웹 통신의 큰 흐름

[참조](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Network)

- HTTP
- OSI 7 Layers
- RESTful API
- TCP, UDP
- DNS
- Security



# Operating System

- 프로세스와 스레드의 차이
- 스케줄러의 종류
  - 장기 스케줄러
  - 단기 스케줄러
  - 중기 스케줄러
- CPU 스케줄러
  - FCFS
  - SJF
  - SRT
  - Priority scheduling
  - RR
- 동기와 비동기의 차이
- 멀티스레드
  - 장점과 단점
- 프로세스 동기화
  - Mutex VS Semaphore
  - Critical Section
  - 해결책
- 메모리 관리 전략
  - 메모리 관리 배경
  - Paging
  - Segmentation
- 가상 메모리
  - 배경
  - 가상 메모리가 하는 일
  - Demand Paging (요구 페이징)
  - 페이지 교체 알고리즘
- 캐시의 지역성
  - Locality
  - Caching line

[참조](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/OS#%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4-%EB%8F%99%EA%B8%B0%ED%99%94)

- Linux, SunOS, Unix
- POSIX API
- Inter Process Communication
- Mutex, Semaphore
- Real-Time Operating System vs Operating System



# Programming Language

## 객체지향

- OOP(캡슐화, 상속, 추상화, 다형성)



## Java

- JVM 에 대해서 / GC 의 원리
- Collection
- Annotation
- Generic
- final
- Overriding vs Overloading
- Access Modifier
- Wrapper class
- Multi-Thread 환경에서의 개발

[참조](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Java)





# C

- 
- 



## C++

- 



## C#

- 
- 



## DOT NET

- 



# Programming Paradigm

- 명령형
  - 객체지향
  - 절차지향
- 선언형
  - 함수형

[참조](https://velog.io/@younoah/programming-paradigm)



## Architecture

- Layered Architecture
- Micro Service Architecture



URL : https://mingrammer.com/translation-10-common-software-architectural-patterns-in-a-nutshell/

URL : https://the-boxer.tistory.com/26



## DevOps

- git vs git lab, bitbucket
- github
- svn
- Jenkins



## Virtualization

- 



# Clean Code

- Test-Driven Development
  - Unit-Test
  - Mocking
- BDD
- DDD
- SOLID
  - SRP(=Single Responsibility Principle) : 단일 책임 원칙
  - OCP(=Open Closed Principle) : 개방 폐쇄 원칙
  - LSP(=Liskov Substitution Principle) : 리스코프 치환원칙
  - ISP(=Interface Segregation Principle) : 인터페이스 분리 원칙
  - DIP(=Dependency Inversion Principle) : 의존 역전 원칙



## JVM

- 실행과정

![image-20210823212336449](C:\Users\천승현\AppData\Roaming\Typora\typora-user-images\image-20210823212336449.png)



- 런타임 영역

![image-20210823212359375](C:\Users\천승현\AppData\Roaming\Typora\typora-user-images\image-20210823212359375.png)



- Garbage Collection

![image-20210823212419801](C:\Users\천승현\AppData\Roaming\Typora\typora-user-images\image-20210823212419801.png)

![image-20210823212429994](C:\Users\천승현\AppData\Roaming\Typora\typora-user-images\image-20210823212429994.png)





[참조](https://asfirstalways.tistory.com/158)



## Design Pattern

- 생성(Creational)패턴
  - 싱글턴(Singleton)
  - 추상 팩토리(Abstract Factory)
  - 팩토리 메서드(Factory Method)
  - 빌더 (Builder)
  - 프로토 타입(Prototype)
- 구조(Structural)패턴
  - 어댑터(Adapter)
  - 브리지(Bridge)
  - 콤포지트(Composite)
  - 데커레이터(Decorator)
  - 퍼사드(Facade)
  - 플라이웨이트(Flyweight)
  - 프록시(Proxy)
- 행위(Behavioral)패턴
  - 책임 연쇄(Chain of Responsibility)
  - 커맨드(Command)
  - 인터프리터(Interpreter)
  - 이터레이터(Iterator)
  - 미디에이터(Mediator)
  - 메멘토(Memento)
  - 옵저버(Observer)
  - 스테이트(State)
  - 스트래티지(Strategy)
  - 템플릿 메서드(Template Method)
  - 비지터(Visitor)
- 안티패턴

[참조](https://gmlwjd9405.github.io/2018/07/06/design-pattern.html)



## Data Structure 

- ![img](https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F23493B3356E9549111)
- 단순구조
  - 정수
  - 실수
  - 문자
  - 문자열
- 선형구조
  - 리스트
    - Linked-List
    - Double Linked-List
  - Stack
  - Queue
  - Dequeue
- 비선형 구조
  - 트리
    - 일반트리
    - 이진트리, Heap
  - 그래프
    - 방향 그래프
    - 무방향 그래프
    - 구현 : 인접 리스트, 인접 행렬

- Hash 
  - table
  - function
  - collision 해결방법



## Algorithm

- 구간합
  - 인덱스 트리
  - 투 포인터
- 정렬
  - Heap sort
  - Quick Sort
  - Merge Sort
- 최소 스패닝 트리 (MST)
  - 프림 알고리즘
  - 크루스칼 알고리즘
- 탐색
  - DFS
  - BFS
  - 이진탐색
    - 트리
    - 배열
- 최단경로
  - 다익스트라
  - 플로이드-워셜
  - 벨만포드

- 최장증가수열(LIS)
- 최소 공통조상(LCA)
- 위상정렬
- 백트래킹
- 유클리드 호제법
- 에라토스테네스의 체
- Union-Find



# Open Source

## PX4 

- NuttX
- uORB
- MAVLink



## jMAVSim

- Java 3D
- 쿼트콥터 모델링
- 센서 시뮬레이션 (IMU, 고도 센서, GPS)
- 



## Apache Tomcat

- 



## Google Cloud Messsage API

- 
