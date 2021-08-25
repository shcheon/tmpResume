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

- Introduction
  - 디지털 영상처리란?
  - 디지털 영상처리 단계
- 디지털 영상처리 기본
  - 인지 요소
  - 이미지 감지 및 획득
  - 이미지 샘플링 및 양자화
  - 픽셀 간 기본적인 관계
- 공간 영역에서의 영상 개선
  - 명암 이미지 변환
  - 히스토그램 처리
  - 산술/로직 연산을 이용한 영상 개선
  - 공간영역 필터링
  - 스무딩 
  - 샤프닝
  - 공간영역 개선방법 조합을 영상 개선
- 주파수 영역에서의 영상 개선
  - 1차원 퓨리에 변환
  - 2차원 이산 퓨리에 변환
  - 주파수 영역에서의 필터링
  - 주파수 영역과 공간영역의 관련성
  - 주파수 영역 필터의 스무딩
  - 주파수 영역 필터의 샤프닝
  - 동형 필터링
- 영상 복원
  - 영상 복원 과정
  - 노이즈 모델
  - 공간 필터링을 이용한 노이즈 제거
  - 주파수 필터링을 이용한 주기성 노이즈 제거
  - Linear, Position-Invariant Degradation
  - Degradation function
  - Inverse Filter
  - Minimum Mean Squre Error Filtering
  - Constrainted Least Squares Filtering
  - Geometric mean Filter
  - Geometric Transformations
- 컬러 영상 처리
  - 컬러 모델
  - Pseudocolor 영상처리
  - Full-Color 영상처리
  - 컬러 변환
  - 스무딩과 샤프닝
  - 컬러 영역분할
  - 컬러 영상의 잡음
  - 컬러 영상 압축
- 웨이블릿과 다중 해상도(MultiResolution) 처리
  - 배경
  - 웨이블릿 변환
- 영상 압축
  - 중복제거 (Coding, Interpixel, Psychovisual, Fidelity)
  - 소스 인코더,디코더
  - 채널 인코더,디코더
  - 정보 이론 요소
  - 무손실 압축
  - 손실 압축
  - 영상 압축 표준
- 형태학적(Morphological) 영상 처리
  - 팽창(Dilation)
  - 침식(Erosion)
  - 개방, 폐쇠
  - Hit-or-Miss 변환
  - 경계선 추출
  - Region Filling
  - Connected Components 추출
  - Convex hull
  - Thinning
  - Thickening
  - Skeletons
  - Pruning
- 영상 분할
  - 중단 영역 검출
  - Edge 연결, 경계선 검출
  - Thresholding
  - Region 기반 분할
  - Morphological WaterSheds기반 분할
- 표현 및 서술
  - 표현
  - 경계 서술자
  - 지역 서술자
  - 관계형 서술자
- 객체 인식
  - 패턴
  - Decision-Theoretic 방법 기반 인식
  - 구조적 방법



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

- HTTP에 대하여 설명해보세요
  - HTTP 1.0 : 
  - HTTP 1.1 : 
  - HTTP 2.0 :
  - HTTPS 에 대하여 설명해보세요
  - HTTP 구조
    - 공통헤더, 요청 헤더, 응답헤더
    - 본문
- HTTP Method에 대하여 설명해보세요
  - GET과 POST 방식의 차이점을 설명해보세요
- REST, REST API에 대하여 설명해보세요
- OSI 7 Layers를 Web Browser 실행과 연관지어 설명해보세요
- TCP/IP Layers에 대하여 설명해보세요
- TCP와 UDP의 차이점을 설명해보세요
- 암호화, 복호화 방식에 대해 설명해보세요
- Cookie와 Session에 대하여 설명해보세요
- 네트워크 보안에 대하여 설명해보세요

[참조](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/tree/master/Network)

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

- 단순구조

  - 정수 : 음수, 0, 양수(자연수)
  - 실수 : 유리수, 무리수
  - 문자 : a,b,c와 같은 기후 
  - 문자열 :  문자들로 이루어진 데이터

- 선형구조

  - 리스트
    - Linked-List  : 데이터와 포인터를 가지며, 한 방향으로 연결되어 있는 구조 
    - Double Linked-List : 데이터와 2개의 포인터를 가지며, 양 방향으로 연결되어 있는 구조
    - 연산 : 포인터를 이용한 데이터 접근 및 삽입/삭제 

  - Stack
    - 후입선출 구조로 데이터 저장되는 구조(Last-In-First_Out)
    - 연산 : 스택 포인터를 이용하여 Push로 데이터를 삽입하고, pop으로 데이터를 인출함

  - Queue
    - 선입선출 구조로 데이터가 저장되는 구조 (First-In-First-Out)
    - 연산 : rear포인터를 이용해 데이터를 삽입, front 포인터를 이용해 데이터를 인출함

  - Deque
    - Queue의 양 끝에서 삽입/삭제를 수행할 수 있는 구조
    - 연산 : rear,front 포인터 양 끝에서 으로 데이터를 삽입/인출


- 비선형 구조

  - 그래프
    - 노드와 그 노드를 연결하는 간선으로 이루어져 있는 구조
    - 특징 : 사이클 가능, 방향 그래프 O, 무방향 그래프 O, 루트 노드 X, 부모자식 X
    - 구현 : 인접 리스트, 인접 행렬

  - 트리
    - 일반트리 
      - 그래프와 동일한 구조이지만, 노드 간 계층적이고, 사이클을 포함할 수 없다는 특징이 있음
      - 구현 : 데이터를 저장하는 공간과 자식노드를 가르키는 포인터로 자료형을 정의

    - 이진트리
      - 부모 노드의 자식노드가 2개로 구성된 트리
      - 부모보다 값이 작은 노드는 왼쪽 자식, 부모보다 값이 큰 노드는 오른쪽 자식으로 배치하는게 특징
      - 이진탐색트리 적용 가능

    - 이진트리 종류 
      - 완전이진트리 : 마지막 레벨을 제외한 모든 레벨이 채워져 있음
      - B 트리 : 자식노드의 개수가 2개 이상인 트리
      - B+ 트리 : 자식을 가지고 있는 노드들은 B트리 형태지만, 리프노드는 연결 리스트로 모두 이어져 있는 구조
      - Heap
        - 루트 노드 값을 최소 또는 최대로 유지하는 완전 이진트리


  - Hash table, Hash map

    - Data를 Hash Function을 이용해 인덱스로 변환하여 ,그 인덱스로 데이터를 저장하는 구조
    - Hash Function : 임의의 길이 데이터를 고정된 길이의 데이터로 맵핑하는 함수

  - 해쉬 충돌

    -  데이터는 다르지만 Hash Function의 결과 값이 동일한 경우

    - 충돌 해결방법

      1. Chainning : 해시 테이블 구조를 연결 리스트 또는 트리로 사용하여 구조 개선

      2. Open Addressing : 충돌 발생한 지점으로부터 빈 공간을 찾아서 데이터를 저장하기 위해 탐사
         - 선형 탐사, 제곱탐사, 이중 해싱
      3. Hash Function 개선 : 나눗셈법, 곰셈법으로 해시함수 변경


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

