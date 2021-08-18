---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

안녕하세요.<br>
여러 분야의 레거시 프로젝트를 분석하며, S/W 아키텍쳐, 자료구조, 알고리즘을 빠르게 이해하는 역량과 다양한 개발환경에서의 디버깅 경험을 보유하고 있습니다.


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

- 개요 : Week 단위의 반도체 생산 계획을 Day 단위로 설비의 Capacity를 고려하여 생산계획을 생성하는 Backend 서버를 운영함

- 주요 역할

  - SQL Join을 이용한 데이터 전처리 및 가공 및 SQL Tuning 수행
  
    - 기술 요소 : Oracle Database, PL/SQL, SunOS, CRON
	
  - MOZART Framework를 활용한 일 생산 계획 수립 비즈니스 로직 구현
  
    - 개발 언어 : C#
	
    - 개발 환경 : .NET Framework 4.6
	
    - API 및 라이브러리 : [MOZART Framework](http://www.vmsmozart.com/index.php?mc=a&md=04&t=)
	
    - 개발 Tool : Visual Studio 2012, MOZART IDE Plugin

    ![mozart](/assets/img/Mozart.png)
	
  - 반도체 생산 계획 보정 및 기준정보 등록/수정/삭제 용 UI 유지보수
  
    - 개발 언어 : Java 6
	
    - 개발 환경 : Jetty 6.1.26 (Local 개발), WebLogic 10.3.6(운영) Oracle Http Server, Dimension(형상관리), XPlatform
	
    - API 및 라이브러리 : Springframework 3.0, Slf4j, [Anyframe-core, Anyframe-xp-query, Anyframe-xplatform, Anyframe-datasource](https://github.com/anyframejava)

  - JDBC API를 이용한 DB to DB 간 데이터 전송 프로그램 운용
    
    - 기술 요소 : Java 6, OJDBC jar, SunOS
  
  - 레거시 프로젝트 TDD 개발환경 구축 및 리팩토링 업무 수행
    
    - 기술 요소 : C# - MStest,Moq / Java - JUnit, Mockito, spring-test

## **슈어소프트테크**

- 재직기간 : 1년 ('17.07 ~ '18.07)

- 수행업무

  - [PROV for Android 솔루션 개발](https://www.suresofttech.com/ko/html/tool/secure_prov.php)  
  
  - [VISTA 솔루션 개발](https://www.suresofttech.com/ko/html/tool/inter_vista.php)

### **PROV for Android 솔루션 개발**

- 개요 : 안드로이드 기반 인포테인먼트 시스템에서 발생하는 메모리 누수를 검출하는 모듈 개발

- 주요 역할

  - Native 메모리 누수 검출 모듈 개발
    
    - malloc, calloc, free, memalign, new, delete 등 C/C++에서 사용하는 동적메모리 할당 키워드가 사용될 때, 호출되는 함수를 Hooking하여 메모리 누수를 감지하는 로직을 구현함
      
    - 개발 언어 : C++
	
    - 개발 환경 : Linux OS, Android Platform Development Kit (Kitkat 4.4.2)
	
    - API 및 라이브러리 : [Malloc Debug](https://android.googlesource.com/platform/bionic/+/master/libc/malloc_debug/README.md), UDS Socket(Inter-Process Commnication)
	
  - 메모리 누수 로그 수집용 App 개발
    
    - Android에서 실행되는 여러개의 Native Process로부터 전송하는 메모리 할당/해제 사용 로그를 수집하고 파일 형태로 기록하는 로직을 Thread, Queue, 임계영역, IPC를 이용하여 로그를 수집하는 기능 구현
  
    - 개발 언어 : Java, C/C++
	
    - 개발 환경 : Android NDK, Android SDK (Kitkat 4.4.2)
	
    - API 및 라이브러리 : Android Component

    ![MemoryLeak](/assets/img/MemoryLeak.png)

<br><br>

### **VISTA 솔루션 개발**

- 개요 : 차량용 인포테인먼트 시스템 UI 테스트 자동화 도구 개발

- 주요 역할

  - 인포테인먼트 화면 캡쳐 모듈 개발
  
    - ADB jar를 이용하여 안드로이드 화면 캡쳐 및 이미지 파일로 추출하는 모듈 개발
    
    - Android Platform 빌드때 사용하는 라이브러리를 이용하여 화면을 캡쳐하는 Native용 프로그램 개발

    - 개발 언어 : C++, Java 
    
    - 개발 환경 : Android PDK (Kitkat 4.4.2)
    
    - API 및 라이브러리 : [Android Debug Bridge](https://developer.android.com/studio/command-line/adb)
        

  - Deep Learning 모델 학습 환경 구축

    - Tensorflow Object Detection API를 활용하여, 딥러닝 모델 학습 및 Image Labeling Tool을 이용하여 인포테이먼트 장비 이미지 Dataset 생성

    - 개발 언어 : Python

    - API 및 라이브러리 : [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)

    ![DeepLearning2](/assets/img/DeepLearning2.png)
    <br><br>
    ![DeepLearning3](/assets/img/DeepLearning3.png)
    

<br><br>     

# **대학원(2015 ~ 2017.2)**

## **객체 검출 및 인식 알고리즘(SURF) 성능 개선 연구**

- 개요 : SURF 알고리즘 성능 최적화를 위한 연구

- 주요 역할
   
   - SURF(=Speeded-Up Robust Features) 알고리즘을 C++로 구현된 OpenSURF 소스 프로젝트를 활용하여, 알고리즘의 병목현상을 분석하여 중복 연산 제거, 메모리 재사용율 개선을 통해 알고리즘 성능을 개선함.
     
     - 개발 언어 : C++
     
     - API 및 라이브러리 : OpenCV, OpenSURF

- 성과

   - 기존 알고리즘 계산시간 대비 30% 시간을 절감
	
   - 기존 알고리즘 대비 메모리 사용율 35% 절감
	
   - SCI, SCIE 논문 게재
	
	![SCI_Paper](/assets/img/SCI_Paper.png)
	<br><br><br><br>
	![SCIE_Paper](/assets/img/SCIE_Paper.png)
	
<br><br>

## **영상기반 객체 추적 비행 알고리즘 연구 및 플랫폼 개발**

- 개요 : 드론으로 영상기반 객체추적 비행 알고리즘 구현 및 시뮬레이션 환경 구축

- 주요 역할

  - 비행 제어용 Board인 PIXHAWK H/W에 탑재되는 RTOS 및 내부 S/W 아키텍쳐 분석

     - 개발 언어 : C+++
     
     - API 및 라이브러리 : CMake, [PX4](https://github.com/PX4/PX4-Autopilot), [MAVLink(Data Protocol)](https://github.com/mavlink/mavlink), uORB (Inter-Process Communication 용 Message 전송 API)

  - 카메라 영상을 활용한 드론 객체 추적 비행 알고리즘 구현

     - 개발 언어 : C++
  
     - API 및 라이브러리 : OpenCV,
  
     - 개발환경 : Linux
  
     - 사용 알고리즘 : PID Controller(제어), [SURF](https://github.com/stephen-mi11er/opensurf)(영상인식), [Location Matching](https://m.earticle.net/Article/A158894)(객체추적)
  
     - 개발 Tool : Intellij

   - 오픈소스를 활용한 영상기반 객체추적 비행 시뮬레이션 비행 환경 구축
     
     - PIXHAWK 보드 전용 비행 시뮬레이터에서 제공하는 화면을 캡쳐하여, 해당 이미지 상에서 객체 인식 및 비행제어 명령을 전송하여 가상의 환경에서 비행 결과를 확인할 수 있는 테스트 베드를 구축함.
  
     - 개발 언어 : C++, Java
     
     - 개발 환경 : Linux 
     
     - API 및 라이브러리 : Java 3D, OpenCV, QT(GUI), [MAVLink](https://github.com/mavlink/mavlink), [JMAVSim](https://github.com/PX4/jMAVSim)
     
     - 개발 Tool : IntelliJ, QtCreator

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
    - Tetris 게임 자료구조 설계 및 이벤트 처리 및 Graphic UI 구현
       
       - 개발언어 : Java, Android 3.0.1 (Icecream Sandwitch)
       
       - API 및 라이브러리 : Android GDI
       
       - 개발 Tool : Android Studio

	![image-20210808210941608](/assets/img/image-20210808210941608.png)

<br><br>

## **안드로이드 어린이 집 종합관리용 서비스 개발**

- 개요 : 아동 폭행 사건 예방 및 어린이 집 관리자와 학부모와 소통하기 편리한 서비스를 구축하기 위해 진행한 프로젝트

- 개발기간 : '12.08.01 ~ '12.12.01 (4개월)

- 주요 역할

  - Android App 개발

    - 화면전환 Animation을 사용하지 않고자, Fragment UI로 구성.
    - 서버로부터 전송받은 데이터를 Android 내장된 SQLite를 활용하여 Database에 저장하는 기능 구현
    - IP Camera로부터 전송받은 MJPEG 이미지를 Android 화면으로 실시간 출력해주는 View기능 구현
      
    - 개발언어 : Android 2.3 (gingerbread), Java
	
    - API 및 라이브러리 : Http API, SQLite, MJPEG, Fragment UI 구성
	
    - 개발 Tool : Eclipse, Android SDK
	
  - Server 개발
    
    - 서버로부터 전송받은 데이터를 Android 내장된 SQLite를 활용하여 Database에 저장하는 기능 구현
    - Google Cloud Message API를 이용하여 Android Push 메세지 전송 기능 구현, MySql Database로 데이터를 CRUD하는 기능 구현
  	
    - 개발언어 : PHP, MySQL
	
    - 웹 어플리케이션 서버 : Apache Tomcat
	
    - API 및 라이브러리 : GCM(=Google Cloud Message) API 활용

	![image-20210808193038964](/assets/img/image-20210808193038964.png) ![image-20210808193055479](/assets/img/image-20210808193055479.png)

<br><br>

## **다중 통신을 수행하는 캔위성 제작**

- 개요 : 위성의 수행하는 임무 중 하나를 구현하기 위해 소형 캔위성을 제작하는 프로젝트

- 개발기간 : '12.06.01 ~ '12.08.30 (3개월)

- 주요 역할

  - Firmware 개발 
    
    - Piconet(1:N통신) 기능을 지원하는 Bluetooth 칩 구매 후 MCU register 프로그래밍을 통해 At Command를 전송하는 펌웨어 개발 

    - 개발언어 : C언어 

    - API 및 라이브러리 : Bluetooth Piconet (1:N 통신 구현)

    - H/W : Atmega 2560

    - 개발 Tool : AVR Studio, LABVIEW

	![image-cansat](/assets/img/cansat.png) 

<br><br>

## **칼만 필터를 적용한 GPS 기반의 UAV 추적 안테나 시뮬레이터 구현** 

- 개요 : 1Hz로 수신되는 항공기의 GPS 정보를 칼만필터를 적용하여 5Hz 주기로 GPS 데이터를 생성하여 항공기를 추적하는 지향성 안테나 시뮬레이터를 개발하는 학부 졸업과제.

- 개발기간 : '14.06.01 ~ '14.08.30 (3개월)

- 주요 역할

  - GPS 기반 지향 및 고도각 계산, Antena 동작 시각화 구현
    
    - OpenGL을 이용하여 구현한 안테나 모형을 직교좌표계에 해당하는 GPS데이터를 극좌표로 변환하여 안테나의 지향방향을 시각화 함.

    - 개발 언어 : C언어

    - API 및 라이브러리 : OpenGL

    - 개발 Tool : Visual Studio 2012
  
  - X-PLANE 비행시뮬레이터와 연동
  
    ![antena](/assets/img/Antena.png)

    ![image-20210808203851671](/assets/img/image-20210808203851671.png)
    
<br><br>
