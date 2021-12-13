---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


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

- 재직기간 : '18.09 ~ '21.12 (3년 3개월)

### **반도체 Backend 공정 Factory Planning Backend서버 운영**

- 개요 : Week 단위의 반도체 생산 계획을 Day 단위로 설비의 Capacity를 고려하여 생산계획을 생성하는 Backend 서버를 운영하였습니다.

- 주요 역할

  - Factory Planning 기준정보 데이터 관리
  
    - PL/SQL로 작성된 DB 프로그램 유지보수

    - SQL Tuning

    - 기술 요소 : Oracle Database, PL/SQL, SunOS, Cron(Scheduling)

  - 일 생산 계획 생성 시뮬레이션 S/W 개발

    - Demand Smoothing 로직 개발

    - Pegging 로직 개발

    - 일 생산 목표(Target) 전개 로직 개발

    - Capacity Bucketing Simulation 기반 반도체 생산 계획 생성 로직 개발

    - PowerShell을 이용한 로그파일 자동 삭제 스크립트 작성 및 배포

    - 기술 요소 : C#, .NET Framework 4.6, [MOZART Framework](http://www.vmsmozart.com/index.php?mc=a&md=04&t=), IIS

    ![mozart](/assets/img/Mozart.png)
    
  - 반도체 생산 계획 Web UI 운영

    - 웹 서버 및 웹 어플리케이션 운영

    - 기술 요소 : Javascript, JSP, Java 6, Spring, Jetty, WebLogic, Oracle Http Server, XPlatform 

  - 단위 테스트 작성 및 리팩토링 업무 수행

    - 테스트 코드 작성활동 문화 도입 및 코드 리팩토링

    - 기술 요소 : C#, MSTest, Github, SVN

<br><br>

## **슈어소프트테크**

- 재직기간 : 1년 ('17.07 ~ '18.07)

- 수행업무

  - [PROV for Android 솔루션 개발](https://www.suresofttech.com/ko/html/tool/secure_prov.php)  

  - [VISTA 솔루션 개발](https://www.suresofttech.com/ko/html/tool/inter_vista.php)

### **PROV for Android 솔루션 개발**

- 개요 : 안드로이드 OS기반의 인포테인먼트 시스템에서 발생하는 메모리 누수를 검출하는 모듈 개발

- 주요 역할

  - Native 메모리 누수 검출 모듈 개발 

    - 기술 요소 : C++, Linux OS, Android Platform Development Kit, [Malloc Debug](https://android.googlesource.com/platform/bionic/+/master/libc/malloc_debug/README.md), IPC Communication (UDS Socket)
	
  - 메모리 누수 로그 수집용 안드로이드 App 개발 
   
    - Android App 버전 호환을 위한 API 사용 코드 유지보수

    - Native Process 프로세스로부터 전송하는 로그 수집 모듈 구현

    - CPU/Memory 사용율 수집을 위한 C프로그램 작성

    - 기술 요소 : Java, C/C++, Android NDK, Android SDK (Kitkat 4.4.2),  Android Component

    ![MemoryLeak](/assets/img/MemoryLeak.png)

<br><br>

### **VISTA 솔루션 개발**

- 개요 : 차량용 인포테인먼트 시스템 UI 테스트 자동화 도구 개발

- 주요 역할

  - 인포테인먼트 화면 캡쳐 모듈 개발  

    - 기술 요소 : C++, Java, Android PDK (Kitkat 4.4.2), [Android Debug Bridge](https://developer.android.com/studio/command-line/adb)        

  - Deep Learning 모델 학습 환경 구축

    - Tensorflow Object Detection API를 활용한 딥러닝 파이프라인 환경 셋업 및 테스트 진행

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

    - SURF 알고리즘 메모리 사용 및 계산량 최적화 연구 수행

    - 기술 요소 : C++, OpenCV, OpenSURF

	![SCI_Paper](/assets/img/SCI_Paper.png)
	<br><br>
	![SCIE_Paper](/assets/img/SCIE_Paper.png)
<br><br>

## **영상기반 객체 추적 비행 알고리즘에 관한 연구**

- 개요 : 특징점 기반 영상 인식 알고리즘을 연구하고, 이를 바탕으로 드론으로 객체추적 비행을 구현하는 연구를 수행함 .

- 주요 역할

  - 무인 비행체 펌웨어 분석 

    - 오픈소스 플랫폼 분석 (외부 데이터 프로토콜, IPC 프로토콜, API 분석)
   
    - 객체 추적 비행모드 구현

    - 기술 요소 : C++, CMake, [PX4](https://github.com/PX4/PX4-Autopilot), [MAVLink(Data Protocol)](https://github.com/mavlink/mavlink), uORB Library

  - 객체 추적 비행 알고리즘 구현

    - 객체 인식 및 추적 기능 개발

    - 비행 알고리즘 개발

    - 기술 요소 : C++, OpenCV, Linux, PID Controller(제어 알고리즘), [SURF](https://github.com/stephen-mi11er/opensurf)(영상 인식), [Location Matching](https://m.earticle.net/Article/A158894)(객체 추적)  

  - 오픈소스 기반 객체 추적 비행 시뮬레이션 환경 구축

    - 비행 시뮬레이터 소스 분석
    
    - 비행제어 알고리즘 테스트 프로그램 개발

    - TCP/IP 기반 영상 전송 기능 구현

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

- 개요 : Java의 OOP 개념 및 Android App 개발 개념을 확립하기 위해 학부생 때 진행한 개인 프로젝트입니다.

- 개발기간 : '13.05.01 ~ '13.06.30 (3개월)

- 주요역할 

  - Android용 테트리스 게임 개발

    - 기술 요소 : Java, Android 3.0.1, Android GDI

	![image-20210808210941608](/assets/img/image-20210808210941608.png)
<br><br>

## **안드로이드 어린이 집 종합관리용 서비스 개발**

- 개요 : 아동 폭행 사건 예방 및 어린이 집 관리자와 학부모와 소통하기 편리한 서비스를 구축하기 위해 공모전에 참여하여 진행한 프로젝트 입니다.

- 개발기간 : '12.08.01 ~ '12.12.01 (4개월)

- 주요 역할

  - Android App 개발

    - Fragment기반 Android GUI 개발

    - RFID 기반 자동출석기능 구현
  
    - 어린이집 공지사항 Push알람 구현

    - IP 카메라 이미지 뷰어 기능 구현

    - 기술 요소 : Java, Android 2.3, Http API, SQLite, MJPEG, Fragment, Google

  - Server 개발

    - 학부모-어린이 정보 저장 DB 스키마 설계
    
    - 어린이 등하원 정보 수집 기능 구현

    - 기술 요소 : PHP, MySQL, Apache Tomcat, GCM(=Google Cloud Message) API   

	![image-20210808193038964](/assets/img/image-20210808193038964.png) ![image-20210808193055479](/assets/img/image-20210808193055479.png)

<br><br>

## **다중 통신을 수행하는 캔위성 제작**

- 개요 : 위성의 임무를 수행하는 소형 캔위성을 제작하는 공모전에 참여하여 진행한 프로젝트입니다.

- 개발기간 : '12.06.01 ~ '12.08.30 (3개월)

- 주요 역할

  - 1:N 통신 펌웨어 개발

    - 1:N통신 기능을 지원하는 Bluetooth 모듈과 MCU register 프로그래밍을 통해 멀티 통신 기능 구현 

    - 기술 요소 : C Language, Bluetooth Piconet (1:N 통신)

	![image-cansat](/assets/img/cansat.png) 
<br><br>

## **칼만 필터를 적용한 GPS 기반의 고정익 UAV 추적 안테나 시뮬레이터 구현** 
- 개요 : 1Hz의 주기로 생성되는 GPS 정보를 5Hz 주기의 데이터를 생성하는 로직을 구성하여 고정익 항공기를 추적하는 지향성 안테나의 동작을 구현한 학부 졸업과제입니다.

- 개발기간 : '14.06.01 ~ '14.08.30 (3개월)

- 주요 역할

  - UAV 추적 안테나 시뮬레이터 구현

    - GPS 데이터의 위,경도 값 예측용 선형 Kalman Filter 구현

    - 지향각 및 고도각 계산 로직 구현

    - 안테나 모형 시각화

    - 비행 시뮬레이터 프로그램과 연동을 통한 안테나 지향 및 고도각 검증 수행
    
    - 마이크로컨트롤러를 이용한 지향 안테나 모의 동작 구현

    - 기술 요소 : C Language, OpenGL, X-PLANE 
    
  - X-PLANE 비행시뮬레이터와 연동
    ![antena](/assets/img/Antena.png)

    ![image-20210808203851671](/assets/img/image-20210808203851671.png)
    
<br><br>
