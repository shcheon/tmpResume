---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

안녕하세요.<br>
S/W R&D에 관심이 많은 천승현 입니다.

**Table of Contents**
* TOC
{:toc}

<br><br>

# **수상 및 논문게재 이력**

- [재능기부 S/W 챌린지 우수상 ('12. 11. 28')](#안드로이드 어린이 집 종합관리용 앱, 서버 개발)

- [캔위성 경연대회 장려상 ('12. 9. 6')](#다중-통신을-수행하는-캔위성-제작)

- [문용호, **천승현**, 하석운, “이동보안시스템에서 폐색영역에서의 소형무인비행체 위치 및 방향 추적”, 대한임베디드공학회, 제 10권 제5호 2015년 10월](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002043955)

- [**S.H. Cheon**, I.K. Eom, S.W. Ha, Y.H. Moon, "An enhanced SURF algorithm based on new interest point detection procedure and fast computation technique", Journal of Real-Time Image Processing, June. 2016. (SCIE)](https://dl.acm.org/doi/abs/10.1007/s11554-016-0614-y)

- [**S.H. Cheon**, I.K. Eom, Y.H. Moon, "Fast descriptor extraction method for a SURF-based interest point", Electronics Letters, vol.52, Issue 4, pp.274-275, Feb. 2016. (SCI)](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/el.2015.3055)

- [**S.H. Cheon**, S.W. Ha, Y.H. Moon, "Hardware In-the-Loop Simulation Platform for Image-based Object Tracking Method using Small UAV", The 35th IEEE Digital Avionics System Conference, Sep. 2016](https://ieeexplore.ieee.org/document/7778031)

<br><br>

# **대학교**

## **안드로이드 테트리스 게임 앱 개발**

- 개요 : Java의 OOP 개념 및 Android App 개발 개념을 확립하기 위해 진행한 학부 개인 과제 

- 개발기간 : '13.05.01 ~ '13.06.30 (3개월)

- 주요역할 : Object Oriented Programming 지향 S/W 구조 설계 및 Android App 개발 

	- 개발언어 : Java, Android 3.0.1 (Icecream Sandwitch)

	- API 및 라이브러리 : Android GDI

	- 개발 Tool : Android Studio, Eclipse

	![image-20210808210941608](/assets/img/image-20210808210941608.png)

<br><br>

## **안드로이드 어린이 집 종합관리용 앱, 서버 개발**

- 개요 : 아동 폭행 사건 예방 및 어린이 집 관리자와 학부모와 소통하기 편리한 서비스를 구축하기 위해 진행한 프로젝트

- 개발기간 : '12.08.01 ~ '12.12.01 (4개월)

- 주요 역할

  - Client 개발
  
    - 개발언어 : Android 2.3 (gingerbread), Java
	
    - API 및 라이브러리 : Http API, SQLite, MJPEG, Fragment UI 구성
	
    - 개발 Tool : Eclipse, Android SDK
	
  - Server 개발
  
    - APM Server 로 서버 구축
	
    - 개발언어 : PHP, MySQL
	
    - 웹 어플리케이션 서버 : Apache Tomcat
	
    - API 및 라이브러리 : GCM(=Google Cloud Message) Server

	![image-20210808193038964](/assets/img/image-20210808193038964.png) ![image-20210808193055479](/assets/img/image-20210808193055479.png)

<br><br>

## **다중 통신을 수행하는 캔위성 제작**

- 개요 : 위성의 수행하는 임무 중 하나를 구현하기 위해 소형 캔위성을 제작하는 프로젝트

- 개발기간 : '12.06.01 ~ '12.08.30 (3개월)

- 주요 역할

  - Firmware 개발 

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

    - 개발 언어 : C언어

    - API 및 라이브러리 : OpenGL

    - 개발 Tool : Visual Studio 2012
  
  - X-PLANE 비행시뮬레이터와 연동
  
    ![antena](/assets/img/Antena.png)

    ![image-20210808203851671](/assets/img/image-20210808203851671.png)
    
<br><br>

# **대학원**

### **영상기반 객체 검출 , 인식 , 추적 기법 연구** 

- 개요 : 드론으로 영상기반 객체추적 비행 알고리즘 개발을 위한 영상 인식 알고리즘 성능 분석

- 주요 역할
  
  - 객체 검출(특징점 추출, 차영상), 인식 (SURF, Template Matching), 추적(KLT 추적기, Meanshift) 기법 연구
	
	- 개발 언어 : C++

	- API 및 라이브러리 : OpenCV

- 연구 결과

  - 특징점 추출 기반의 영상 인식 알고리즘(SURF)이 객체 추적 비행알고리즘에 가장 적합함을 확인
 
  - 추적 알고리즘으로 이미지 내에 연산범위를 축소 가능함을 확인

	![image-20210808204524745](/assets/img/image-20210808204524745.png)

<br><br>

## **객체 검출 및 인식 알고리즘(SURF) 성능 개선 연구**

- 개요 : SURF 알고리즘 성능 최적화를 위한 연구

- 주요 역할 : OpenSURF 소스를 활용한 알고리즘 병목현상 분석 및 개선

	- 개발 언어 : C++

	- API 및 라이브러리 : OpenCV, OpenSURF

- 연구 결과
	- 기존 알고리즘 계산시간 대비 30% 시간을 절감
	
	- 기존 알고리즘 대비 메모리 사용율 35% 절감
	
	- SCI, SCIE 논문 게재
	
	
	![SCI_Paper](/assets/img/SCI_Paper.png)
	<br><br><br><br>
	![SCIE_Paper](/assets/img/SCIE_Paper.png)
	
<br><br>

## **영상기반 객체 추적 비행 알고리즘 연구 및 플랫폼 개발**

- 개요 : 드론으로 영상기반 객체추적 비행알고리즘 구현 및 시뮬레이션 환경 구축

- 주요 역할

  - 개발 언어 : C++
  
  - API 및 라이브러리 : OpenCV, [MAVLink(Data Protocol)](https://github.com/mavlink/mavlink), [PX4](https://github.com/PX4/PX4-Autopilot)
  
  - 개발환경 : Linux
  
  - 사용 알고리즘 : PID Controller(제어), [SURF](https://github.com/stephen-mi11er/opensurf)(영상인식), [Location Matching](https://m.earticle.net/Article/A158894)(객체추적)
  
  - 개발 Tool : Intellij

- 오픈소스를 활용한 영상기반 객체추적 비행 시뮬레이션 비행 환경 구축
  
  - 개발 언어 : C++, Java
 
  - 개발 환경 : Linux
  
  - API 및 라이브러리 : Java 3D, OpenCV, QT(GUI), [MAVLink](https://github.com/mavlink/mavlink), [JMAVSim](https://github.com/PX4/jMAVSim)
 
  - 개발 Tool : IntelliJ, QtCreator

	![simulation-env](/assets/img/SimulationEnv.png)
	<br><br>
	![simulator-diagram](/assets/img/SimulatorDiagram.png)

- 연구 결과

  - [영상 기반 객체 추적 비행 알고리즘 구현 영상보기 1](https://www.youtube.com/watch?v=rUZeQo1Jiss)
  
  - [영상 기반 객체 추적 비행 알고리즘 구현 영상보기 2](https://www.youtube.com/watch?v=wVBL-0HvnYU)
  
  - [영상 기반 객체 추적 비행 시뮬레이션 환경 구축 영상보기](https://www.youtube.com/watch?v=pxsQ5IP9HO4)
  
<br><br>

# **회사**

## **슈어소프트테크**

- 재직기간 : 1년 ('17.07 ~ '18.07)

- 수행업무

  - [PROV for Android 솔루션 개발](https://www.suresofttech.com/ko/html/tool/secure_prov.php)  
  
  - [VISTA 솔루션 개발](https://www.suresofttech.com/ko/html/tool/inter_vista.php)

### **PROV for Android 솔루션 개발**

- 개요 : 안드로이드 기반 인포테인먼트 시스템에서 발생하는 메모리 누스를 검출하는 모듈 개발

- 주요 역할

  - Native 메모리 누수 검출 모듈 개발
  
    - 개발 언어 : C++
	
    - 개발 환경 : Linux OS, Android PDK (Kitkat 4.4.2), SVN(형상관리)
	
	- API 및 라이브러리 : [Malloc Debug](https://android.googlesource.com/platform/bionic/+/master/libc/malloc_debug/README.md), UDS Socket(Inter-Process Commnication)
	
    - 개발 Tool : Android Open Source에 내장된 Build Script 활용
	
  - 메모리 누수 로그 수집용 App 개발
  
    - 개발 언어 : Java
	
    - 개발 환경 : Android NDK, Android SDK (Kitkat 4.4.2)
	
    - API 및 라이브러리 : Android Component
	
    - 개발 Tool : Android Studio

    ![MemoryLeak](/assets/img/MemoryLeak.png)

<br><br>

### **VISTA 솔루션 개발**

- 개요 : 차량용 인포테인먼트 시스템 UI 테스트 자동화 도구 개발

- 주요 역할

  - 인포테인먼트 화면 캡쳐 모듈 개발

    - 개발 언어 : C++, Java 
    
    - 개발 환경 : Android PDK (Kitkat 4.4.2), SVN (형상관리) 
    
    - API 및 라이브러리 : [Android Debug Bridge](https://developer.android.com/studio/command-line/adb)
    
    - 개발 Tool : Ecilpse
    

  - Deep Learning 학습 파이프라인 구축

    - 개발 언어 : Python

    - API 및 라이브러리 : [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)

    ![DeepLearning2](/assets/img/DeepLearning2.png)
    <br><br>
    ![DeepLearning3](/assets/img/DeepLearning3.png)
    

<br><br>     

## **삼성SDS**

- 재직기간 : '18.07 ~ 현재

### **반도체 Backend 공정 Factory Planning 서비스 운영**

- 개요 : 반도체 주문 납기 준수를 위한 일(Daily) 공장 생산 계획 수립 및 시뮬레이션

- 주요 역할

  - 반도체 기준정보 가공 및 처리 모듈 개발(Sub업무)
  
    - 개발 언어 : PL/SQL
	
    - 개발 환경 : SunOS, Dimension(형상관리)
	
    - API 및 라이브러리 : Procedure/Package 구현, Oracle Database 19c, cron
	
    - 개발 Tool : Toad, SQL Developer
	
  - 일 생산 계획 수립 모듈 비즈니스 로직 구현(Main업무)
  
    - 개발 언어 : C#
	
    - 개발 환경 : .NET Framework 4.6, SVN(형상관리)
	
    - API 및 라이브러리 : [MOZART Framework](http://www.vmsmozart.com/index.php?mc=a&md=04&t=)
	
    - 개발 Tool : Visual Studio 2012, MOZART IDE Plugin

    ![mozart](/assets/img/Mozart.png)
	
  - 일 생산 계획 보정 및 기준정보 조회용 UI 개발(Sub업무)
  
    - 개발 언어 : Java 6
	
    - 개발 환경 : Jetty 6.1.26 (Local 개발), WebLogic 10.3.6(운영) Oracle Http Server, Dimension(형상관리), XPlatform
	
    - API 및 라이브러리 : Springframework 3.0, Slf4j, [Anyframe-core, Anyframe-xp-query, Anyframe-xplatform, Anyframe-datasource](https://github.com/anyframejava)
	
    - 개발 Tool : Eclipse, UX Studio
