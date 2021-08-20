---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

안녕하세요.<br>

여러 분야의 레거시 프로젝트를 분석하며, S/W 아키텍쳐, 자료구조, 알고리즘을 빠르게 이해하는 역량과
다양한 개발환경에서의 개발 경험을 보유하고 있습니다.


**Table of Contents**
* TOC
{:toc}

<br><br>

# **수상 및 논문게재 이력**

- [재능기부 S/W 챌린지 우수상 ('12. 11. 28')](#안드로이드-어린이-집-종합관리용-서비스-개발)

- [캔위성 경연대회 장려상 ('12. 9. 6')](#다중-통신을-수행하는-캔위성-제작)

- [문용호, **천승현**, 하석운, “이동보안시스템에서 폐색영역에서의 소형무인비행체 위치 및 방향 추적”, 대한임베디드공학회, 제 10권 제5호 2015년 10월](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002043955)

- [**S.H. Cheon**, I.K. Eom, S.W. Ha, Y.H. Moon, "An enhanced SURF algorithm based on new interest point detection procedure and fast computation technique", Journal of Real-Time Image Processing, June. 2016. (SCIE)](https://dl.acm.org/doi/abs/10.1007/s11554-016-0614-y)

- [**S.H. Cheon**, I.K. Eom, Y.H. Moon, "Fast descriptor extraction method for a SURF-based interest point", Electronics Letters, vol.52, Issue 4, pp.274-275, Feb. 2016. (SCI)](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/el.2015.3055)

- [**S.H. Cheon**, S.W. Ha, Y.H. Moon, "Hardware In-the-Loop Simulation Platform for Image-based Object Tracking Method using Small UAV", The 35th IEEE Digital Avionics System Conference, Sep. 2016](https://ieeexplore.ieee.org/document/7778031)

<br><br>

# **회사(2017.7 ~ 현재)**

## **삼성SDS**

- 재직기간 : '18.07 ~ 현재

### **반도체 Backend 공정 Factory Planning Backend서버 운영**

- 개요 : Week 단위의 반도체 생산 계획을 Day 단위로 설비의 Capacity를 고려하여 생산계획을 생성하는 Backend 서버를 운영하였습니다.

- 주요 역할

  - SQL Join을 이용한 데이터 전처리 및 가공 및 SQL Tuning 수행

    - 100개 이상의 테이블 관리 및 100만건 이상의 데이터를 SQL Join을 통해 데이터를 가공하는 로직을 구현 업무를 담당하였습니다.

    - SQL Tuning을 통해 처리시간을 단축하는 업무를 담당하였습니다.  

    - 기술 요소 : Oracle Database, PL/SQL, SunOS, Cron(Scheduling)

  - MOZART Framework를 활용한 일 생산 계획 수립 비즈니스 로직 구현

    - 30개 이상의 DB 테이블를 In-Memory로 로딩하여, 반도체 생산계획을 수립하기 위한 S/W 설계, 자료구조, 알고리즘을 개발하는 업무를 수행하였습니다.

    - Order에 따른 반도체 공정별 일 생산 목표(Target)를 생성하는(Backward Pegging) 로직 구현업무를 담당하였습니다.

    - Order 납기 준수를 위한, 설비에 공정 별 생산 계획을 예측하는(Forward Planning) 로직을 구현하는 업무를 담당하였습니다.

    - 기술 요소 : C#, .NET Framework 4.6, [MOZART Framework](http://www.vmsmozart.com/index.php?mc=a&md=04&t=)

    ![mozart](/assets/img/Mozart.png)
    
  - 반도체 생산 계획 보정 및 기준정보 등록/수정/삭제용 UI 유지보수

    - Xplatform 기반으로 동작하는 WEB서버를 운용하며 Web Browser UI 구성, Popup 이벤트 처리, Backend 서버와 통신하는 로직을 분석하는 업무를 수행하였습니다.

    - Spring기반으로 구축된 WAS 서버의 역할에 해당하는 SSO 인증, 시큐어 코딩, DB CRUD 처리를 수행하는 기능을 유지보수하는 업무를 수행하였습니다.

    - 기술 요소 : Javascript, JSP, Java 6, Spring, Jetty, WebLogic, Oracle Http Server, XPlatform 

  - JDBC API를 이용한 DB to DB 간 데이터 전송 프로그램 운용

    - Batch단위로 Database 간의 데이터를 송수신하는 프로그램을 운영하였습니다.

    - 기술 요소 : Java 6, OJDBC jar, SunOS

  - 레거시 프로젝트 TDD 개발환경 구축 및 리팩토링 업무 수행

    - Test-Driven-Development 개발문화를 도입하고, Clean Code 작성에 도움이 되는 지식을 전파하는 활동을 하였습니다.

    - 코드 품질에 해당하는 Cyclomatic Complexity, LinesOfCode, CouplingBetweenObjects, Modular Circular Dependency, Duplicate Codes를 없애기 위한 리팩토링 업무를 진행하였습니다.

    - 기술 요소 : C# - MStest,Moq / Java - JUnit, Mockito, spring-test

<br><br>

## **슈어소프트테크**

- 재직기간 : 1년 ('17.07 ~ '18.07)

- 수행업무

  - [PROV for Android 솔루션 개발](https://www.suresofttech.com/ko/html/tool/secure_prov.php)  

  - [VISTA 솔루션 개발](https://www.suresofttech.com/ko/html/tool/inter_vista.php)

### **PROV for Android 솔루션 개발**

- 개요 : 안드로이드 기반 인포테인먼트 시스템에서 발생하는 메모리 누수를 검출하는 모듈 개발

- 주요 역할

  - Native 메모리 누수 검출 모듈 개발 

    - malloc, calloc, free, memalign, new, delete 등 C/C++에서 동적 메모리 할당 키워드가 사용될 때, 이를 Hooking하여 메모리 누수를 감지하는 Agent 모듈을 구현하였습니다.      

    - 기술 요소 : C++, Linux OS, Android Platform Development Kit, [Malloc Debug](https://android.googlesource.com/platform/bionic/+/master/libc/malloc_debug/README.md), IPC Communication (UDS Socket)
	
  - 메모리 누수 로그 수집용 App 개발 

    - Android에서 실행되는 여러개의 Native Process로부터 전송하는 메모리 할당/해제 사용 로그를 수집하고 파일 형태로 기록하는 로직을 Thread, Queue, 임계영역, IPC를 이용하여 로그를 수집하는 기능 구현  

    - 기술 요소 : Java, C/C++, Android NDK, Android SDK (Kitkat 4.4.2),  Android Component

    ![MemoryLeak](/assets/img/MemoryLeak.png)

<br><br>

### **VISTA 솔루션 개발**

- 개요 : 차량용 인포테인먼트 시스템 UI 테스트 자동화 도구 개발

- 주요 역할

  - 인포테인먼트 화면 캡쳐 모듈 개발  

    - ScreenCapture가 지원되지 않는 안드로이드 기반 인포테인먼트 장비에서 화면을 캡쳐하는 Agent 프로그램을 구현하였습니다.

    - 기술 요소 : C++, Java, Android PDK (Kitkat 4.4.2), [Android Debug Bridge](https://developer.android.com/studio/command-line/adb)        

  - Deep Learning 모델 학습 환경 구축

    - Tensorflow Object Detection API를 활용하여, 딥러닝 모델 학습 및 Image Labeling Tool을 이용하여 인포테이먼트 장비 이미지 Dataset을 생성하는 업무를 진행하였습니다.

    - 기술 요소 : Python, [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)

    ![DeepLearning2](/assets/img/DeepLearning2.png)
    <br><br>
    ![DeepLearning3](/assets/img/DeepLearning3.png)
<br><br>     

# **대학원(2015.3 ~ 2017.2)**

## **객체 검출 및 인식 알고리즘(SURF) 성능 개선 연구**

- 개요 : SURF 알고리즘 연산시간 최적화를 위한 연구

- 주요 역할

  - 영상 인식 알고리즘 개선

    - SURF 알고리즘에 포함된 Integral Image, Hessian-Matrix 기반 Interest Point 검출 및 Descriptor 생성 알고리즘을 이해한 후, 알고리즘 병목현상을 개선하는 연구를 진행하였습니다.

    - 기술 요소 : C++, OpenCV, OpenSURF

	![SCI_Paper](/assets/img/SCI_Paper.png)
	<br><br>
	![SCIE_Paper](/assets/img/SCIE_Paper.png)
<br><br>

## **영상기반 객체 추적 비행 알고리즘 연구 및 플랫폼 개발**

- 개요 : 드론으로 영상기반 객체추적 비행 알고리즘 구현 및 시뮬레이션 환경 구축

- 주요 역할

  - 비행 제어용 Board인 PIXHAWK H/W에 탑재되는 RTOS 및 내부 S/W 아키텍쳐 분석

    - 기술 요소 : C++, CMake, [PX4](https://github.com/PX4/PX4-Autopilot), [MAVLink(Data Protocol)](https://github.com/mavlink/mavlink), uORB (IPC용 Message 전송 API)

  - 영상기반 드론 객체 추적 비행 알고리즘 구현

    - 기술 요소 : C++, OpenCV, Linux, PID Controller(제어 알고리즘), [SURF](https://github.com/stephen-mi11er/opensurf)(영상 인식), [Location Matching](https://m.earticle.net/Article/A158894)(객체 추적)  

  - 오픈소스를 활용한 영상기반 객체추적 비행 시뮬레이션 비행 환경 구축

    - PIXHAWK 보드 전용 비행 시뮬레이터에서 제공하는 화면을 캡쳐하여, 해당 이미지 상에서 객체 인식 및 비행제어 명령을 전송하여 가상의 환경에서 비행 결과를 확인할 수 있는 테스트 베드를 구축하는 연구를 진행하였습니다.

    - 기술 요소 : C++, Java, Java 3D, OpenCV, Linux, QT(GUI), [MAVLink](https://github.com/mavlink/mavlink), [JMAVSim](https://github.com/PX4/jMAVSim
     
	![simulation-env](/assets/img/SimulationEnv.png)
	<br><br>
	![simulator-diagram](/assets/img/SimulatorDiagram.png)

- 결과물
    - [영상 기반 객체 추적 비행 알고리즘 구현 영상보기 1](https://www.youtube.com/watch?v=rUZeQo1Jiss)

    - [영상 기반 객체 추적 비행 알고리즘 구현 영상보기 2](https://www.youtube.com/watch?v=wVBL-0HvnYU)

    - [영상 기반 객체 추적 비행 시뮬레이션 환경 구축 영상보기](https://www.youtube.com/watch?v=pxsQ5IP9HO4)
  
<br><br>

# **대학교(2008.3 ~ 2015.2)**

## **안드로이드 테트리스 게임 앱 개발**

- 개요 : Java의 OOP 개념 및 Android App 개발 개념을 확립하기 위해 진행한 학부 개인 과제 

- 개발기간 : '13.05.01 ~ '13.06.30 (3개월)

- 주요역할 

  - Android용 테트리스 게임 개발

    - 추상화, 상속, 인터페이스, 캡슐화, 다형성 개념을 활용하여 S/W를 설계 및 구현하고, Android Component와 GDI를 활용하여 Graphic UI 구현하였습니다.

    - 기술 요소 : Java, Android 3.0.1, Android GDI

	![image-20210808210941608](/assets/img/image-20210808210941608.png)
<br><br>

## **안드로이드 어린이 집 종합관리용 서비스 개발**

- 개요 : 아동 폭행 사건 예방 및 어린이 집 관리자와 학부모와 소통하기 편리한 서비스를 구축하기 위해 진행한 프로젝트

- 개발기간 : '12.08.01 ~ '12.12.01 (4개월)

- 주요 역할

  - Android App 개발

    - 부드러운 화면전환을 위해 Fragment Library를 이용하여 Android UI를 구현하였습니다.

    - 어린이집 공지사항, 출석체크 등의 정보를 SQLite를 활용하여 모바일 Database에 저장하는 기능을 구현하였습니다.

    - IP Camera로부터 전송받은 MJPEG 이미지를 Android 화면으로 실시간 출력해주는 Viewer를 구현하였습니다. 

    - 서버의 Update 버전 점검 로직을 통해, 서버 DB data 동기화 또는 image Resourece파일을 다운받는 로직을 구현하였습니다.

    - 기술 요소 : Java, Android 2.3, Http API, SQLite, MJPEG, Fragment

  - Server 개발

    - Apache Tomcat 서버를 이용하여 데이터 CRUD를 수행하는 웹 서버를 구축하였습니다.

    - 어린이가 등하원 할 때, Http와 GCM API를 이용하여 Push 알람 메시지를 전송해주는 기능을 구현하였습니다.

    - 기술 요소 : PHP, MySQL, Apache Tomcat, GCM(=Google Cloud Message) API   

	![image-20210808193038964](/assets/img/image-20210808193038964.png) ![image-20210808193055479](/assets/img/image-20210808193055479.png)

<br><br>

## **다중 통신을 수행하는 캔위성 제작**

- 개요 : 위성의 수행하는 임무 중 하나를 구현하기 위해 소형 캔위성을 제작하는 프로젝트

- 개발기간 : '12.06.01 ~ '12.08.30 (3개월)

- 주요 역할

  - Firmware 개발

    - Piconet(1:N통신) 기능을 지원하는 Bluetooth을 활용하여 MCU register 프로그래밍을 통해 멀티 통신 기능을 구현하였습니다. 

    - 기술 요소 : C Language, Bluetooth Piconet (1:N 통신 구현), LABVIEW

	![image-cansat](/assets/img/cansat.png) 
<br><br>

## **칼만 필터를 적용한 GPS 기반의 UAV 추적 안테나 시뮬레이터 구현** 
- 개요 : 1Hz로 수신되는 항공기의 GPS 정보를 칼만필터를 적용하여 5Hz 주기로 GPS 데이터를 생성하여 항공기를 추적하는 지향성 안테나 시뮬레이터를 개발하는 학부 졸업과제.

- 개발기간 : '14.06.01 ~ '14.08.30 (3개월)

- 주요 역할

  - UAV 추적 안테나 시뮬레이터 구현

    - GPS 데이터의 위,경도 값을 예측하는 선형 Kalman Filter를 구현하였습니다.

    - GPS 위, 경도 데이터로 지향각과 고도각을 계산하는 식을 논문을 참조하여 구현하였습니다.

    - OpenGL을 이용하여 안테나 모형을 시각화 하였습니다.

    - 직교 좌표계에 해당하는 GPS데이터를 극좌표로 변환하는 식을 구현하였습니다.

    - X-PLANE에서 전송해주는 데이터는 빅 엔디안 구조이므로, Union 자료구조를 이용하여 데이터를 리틀 엔디안구조로 변경하는 데이터 송수신부를 구현하였습니다.

    - 기술 요소 : C Language, OpenGL, X-PLANE 
    
  - X-PLANE 비행시뮬레이터와 연동
    ![antena](/assets/img/Antena.png)

    ![image-20210808203851671](/assets/img/image-20210808203851671.png)
    
<br><br>
