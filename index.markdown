---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: post
---

# **자기소개**
- 안녕하세요. 우물안에서 벗어나고 싶은 개구리같은 개발자입니다.

<br>

# **수상 및 논문게재 이력**

- 재능기부 S/W 챌린지 우수상 ('12. 11. 28')

- 캔위성 경연대회 장려상 ('12. 9. 6')

- [문용호, **천승현**, 하석운, “이동보안시스템에서 폐색영역에서의 소형무인비행체 위치 및 방향 추적”, 대한임베디드공학회, 제 10권 제5호 2015년 10월](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002043955)

- [**S.H. Cheon**, I.K. Eom, S.W. Ha, Y.H. Moon, "An enhanced SURF algorithm based on new interest point detection procedure and fast computation technique", Journal of Real-Time Image Processing, June. 2016. (SCIE)](https://dl.acm.org/doi/abs/10.1007/s11554-016-0614-y)

- [**S.H. Cheon**, I.K. Eom, Y.H. Moon, "Fast descriptor extraction method for a SURF-based interest point", Electronics Letters, vol.52, Issue 4, pp.274-275, Feb. 2016. (SCI)](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/el.2015.3055)

- [**S.H. Cheon**, S.W. Ha, Y.H. Moon, "Hardware In-the-Loop Simulation Platform for Image-based Object Tracking Method using Small UAV", The 35th IEEE Digital Avionics System Conference, Sep. 2016](https://ieeexplore.ieee.org/document/7778031)

<br><br><br>

# **개발자 성장이력 - 대학교**

#### **1. 안드로이드 테트리스 게임 앱 개발**
- 개요 : Java의 OOP 개념 및 Android App 개발 개념을 확립하기 위해 진행한 학부 개인 과제 

- 개발기간 : '13.05.01 ~ '13.06.30 (3개월)

- 주요역할 : Object Oriented Programming 지향 S/W 구조 설계 및 Android App 개발 

	- 개발언어 : Java, Android 3.0.1 (Icecream Sandwitch)

	- API 및 라이브러리 : Android GDI, Java swing/awt

	- 개발 Tool : Android Studio, Eclipse

	![image-20210808210941608](/assets/img/image-20210808210941608.png)

<br><br>

#### **2. 안드로이드 어린이 집 종합관리용 앱, 서버 개발**

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

#### **3. 다중 통신을 수행하는 캔위성 제작**

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

#### **4. 칼만 필터를 적용한 GPS 기반의 UAV 추적 안테나 시뮬레이터 구현** 

- 개요 : 5Hz로 수신되는 항공기의 GPS 정보를 칼만필터를 적용하여 25Hz 주기로 GPS 데이터를 생성하여 항공기를 추적하는 지향성 안테나 시뮬레이터를 개발하는 학부 졸업과제.

- 개발기간 : '14.05.01 ~ '12.10.30 (6개월)

- 주요 역할

  - 시뮬레이터 개발 

    - 개발언어 : C언어

    - API 및 라이브러리 : OpenGL

    - 개발 Tool : Visual Studio 2012
  
  - X-PLANE 비행시뮬레이터와 연동
  
    ![antena](/assets/img/Antena.png)

    ![image-20210808203851671](/assets/img/image-20210808203851671.png)


      
<br><br><br>


# **개발자 성장이력 - 대학원**

#### **1. 영상기반 객체 검출 , 인식 , 추적 기법 연구** 

- 개요 : 드론으로 영상기반 객체추적 비행 알고리즘 개발을 위한 영상 인식 알고리즘 성능 분석

- 주요 역할
  
  - 객체 검출(특징점 추출, 차영상), 인식 (SURF, Template Matching), 추적(KLT 추적기, Meanshift) 기법 연구
	
	- 개발 언어 : C++

	- API 및 라이브러리 : OpenCV

- 연구 결과

  - 특징점 추출 기반의 영상 인식 알고리즘(SURF)이 객체 추적 비행알고리즘에 가장 적합함을 확인
  
  - 추적 알고리즘으로 이미지 내에 연산범위를 축소가능함을 확인

	![image-20210808204524745](/assets/img/image-20210808204524745.png)


<br><br><br>

#### **2. 객체 검출 및 인식 알고리즘(SURF) 성능 개선 연구**

- 개요 : SURF 알고리즘 성능 최적화를 위한 연구

- 주요 역할 : OpenSURF 소스를 활용한 알고리즘 병목현상 분석 및 개선

	- 개발 언어 : C++

	- API 및 라이브러리 : OpenCV, OpenSURF

- 연구 결과
	- 기존 알고리즘 계산시간 대비 23% 시간을 절감
	
	- 알고리즘 메모리 사용율 5~10% 정도 절약
	
	- SCI, SCIE 논문 게재
	
	
	![SCI_Paper](/assets/img/SCI_Paper.png)
	<br><br><br><br>
	![SCIE_Paper](/assets/img/SCIE_Paper.png)
	


#### **3. 영상기반 객체 추적 비행 알고리즘 연구 및 플랫폼 개발 **

- TODO


# 개발자 성장이력 - 회사

## 슈어소프트테크 (재직기간 : '17.7월 ~ 18년 7월')

### AMOS for Android 솔루션 개발  (Android KitKat 버전 기반 메모리 누수 검출 솔루션)

- Android NDK 영역에서 발생하는 메모리 누수검출 모듈 개발 (C/C++, Android)
  - 메모리 누수 로그 수집 모듈 개발 (C/C++, Java, Android)
- VISTA 솔루션 개발 (차량용 인포테인먼트 시스템 UI 테스트 자동화 도구)
  - Target Agent 영상 캡쳐 모듈 개발 (C/C++, Android PDK, )
  - Deep Learning 학습 파이프라인 구축 ( Tensorflow Object Detection API, Python,)



## 삼성SDS ('18년 7월 ~ 현재')

### 1. 반도체 후공정 일 생산 계획 서비스 운영

- 반도체 기준정보 처리 모듈 개발 (Oracle DB, PL/SQL)
- MOZART Framework를 활용한 반도체 생산 계획 수립 비즈니스 로직 개발 (C#, MOZART Framework (VMS Solutions 기업에서 제공))
- 반도체 일생산 계획 조회 UI 개발 (Java, SpringFramework)

# Appendix


