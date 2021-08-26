# Network

- **Web의 동작 방식을 설명해보세요**

  1. 사용자가 브라우저에 URL을 입력

  2. 브라우저는 DNS를 통해 서버의 진짜 주소를 찾음 (Domain Name System : 도메인 이름을 IP로 변경해주는 서버)

  3. HTTP로 Request 메세지를 생성함

  4. TCP/IP 연결을 통해 서버로 전송됨

  5. 웹 서버는 HTTP Request에 대한 Response 메세지를 생성함

  6. TCP/IP 연결을 통하여 요청한 컴퓨터로 전송

  7. 도착한 HTTP Response는 웹페이지 데이터로 변환되고, 웹 브라우저에 의해 출력되어 사용자가 봄

- **HTTP에 대하여 설명해보세요**

  - Hyper Text Transfer Protocol의 약자로, 웹 상에서 사용되는 데이터 송수신 프로토콜

- **HTTP 통신방식**

  - 요청 / 응답 구조로 이루어져 있으며, 상태값을 저장하지 않음(Stateless)

- **HTTP 구조**

  - HTTP 메세지는 Method, Path, Version, Header, Body로 구성되어 있음

  - 평문으로 전송하여 데이터가 노출 될 수 있음
  
  - 

- **HTTP Request의 구조**

  - 시작라인  : 요청 Path, HTTP Method와 Version이 명시되어 있음

    - GET /search HTTP/1.1

  - Header : 요청에 대한 추가정보가 담겨있음, Key-Value로 데이터가 구성되어 있음 (Key:Value)

    - 대표적인 Header 
      - Host : 요청을 보낸 URL 
      - User-Agent : 클라이언트 정보, 웹 브라우저 정보
      - Accept : 해당 요청을 받을 수 있는 응답 타입 ex) application/json
      - Connection : 해당 요청이 끝난 후에 클라이언트와 서버간 커넥션 유지 여부를 나타냄 ex) Keep-alive
      - Content-Type : body의 타입
      - Content-Length : body의 길이

  - Body : 요청 내용

    - GET 요청은 주로 Body가 없음

      

- **HTTP Response의 구조**

  - 상태 라인 :  HTTP 버전, 상태 코드, 상태 메세지가 명시

    - HTTP/1.1 404 Not Found

  - Header : Request의 Header와 동일

  - Body : 응답 내용

- **HTTP 버전 별 특징**

  - HTTP 1.0 :

  - HTTP 1.1 :

  - HTTP 2.0 :

- **HTTPS** 

  - HTTP프로토콜에 암호화가 추가된 프로토콜
  


- **HTTP Method**

  - HTTP 데이터를 전송할 때 사용되는 방법. GET,POST, DELETE, PUT을 주로 사용

- **HTTP Status Code**

  - 200 OK : 

  - 301 Moved Permanetly : 

  - 400 Bad Request : 

  - 401 Unauthorized : 

  - 403 Forbidden : 

  - 404 Not Found : 

  - 500 Internal Server Error : 

- **REST, REST API**

- **OSI 7 Layers**

  - 네트워크에서 통신이 일어나는 과정을 7단계로 분류한 계층

  - 7 계층 (Application Layer) : 사용자와 직접 상호작용하는 응용 프로그램들이 포함된 계층

  - 6 계층 (Presentation Layer) : 데이터의 형식을 정의하는 계층

  - 5 계층 (Session Layer) : 컴퓨터끼리 통신하기 위해 세션을 만드는 계층

  - 4계층 (Transport Layer) : 최종 수신 프로세서로 데이터의 전송을 담당하는 계층 (UDP, TCP 이용)

  - 3 계층 (Network Layer) : 패킷을 목적지까지 가장 빠른 길로 전송을 담당하는 계층 (IP주소로 전송)

  - 2 계층 (Datalink Layer) : 데이터의 물리적인 전송과 에러 검출, 흐름제어를 담당하는 계층 (MAC주소로 전송)

  - 1 계층 (Physical Layer) : 데이터를 전기신호로 바꾸어주는 계층

- **TCP/IP**

  - TCP 프로토콜과 IP 프로토콜을 합쳐서 부르는 용어

  - IP는 네트워크에서 패킷을 교환할 때,  목적지까지 빠르게 전송하기 위한 프로토콜이며, TCP는 목적지까지 데이터 손실 없이 무사히 도착하였는지, 순서가 올바른지, 네트워크의 혼잡도 고려하는 역할을 하는 프로토콜 임. TCP와 IP를 같이 자주 쓰이므로, TCP/IP로 묶어서 말함

- **TCP와 UDP의 차이점**

  - TCP는 가상회선을 만들어 목적지까지 전송할 논리적인 연결을 만들고, 각 패킷은 가상 식별 번호가 부여되어 패킷들이 순서대로 도착하고, 신뢰성이 높 . 통신은 1:1로만 가능하며 UDP에 비해 속도가 느리다는 단점이 있음

  - UDP는 패킷에 목적지 주소만 이용하여 전송되므로, 동일 패킷이라 하더라도 목적지까지 도착하는 네트워크 경로는 다를 수 있음.  통신은 1:1 1:N N:N이 가능하며, 연결과정이 없으므로, TCP보다 빠르지만 데이터 신뢰성을 보장하지 못한다는 단점이 있음

  - TCP의 혼잡제어, 흐름제어, 순서 제어 등이 가능한 이유는 헤더에 정보가 포함되어 있기 때문임. UDP 헤더는 목적지 주소이외에 없다고 봐도 무방.
    

- **TCP 의 3-ways handshake**

  - 세션 만들때 사용됨

  - Client -> Server : TCP SYN 전송

  - Client <- Server : TCP SYN ACK 전송

  - Client -> Server : TCP ACK 전송

- **TCP 의 4-ways handshake** 

  - 세션 종료할 때 사용됨

  - Client -> Server : FIN 전송

  - Client <- Server : ACK 전송

  - Client <- Server : FIN 전송

  - Client -> Server : ACK 전송

- 암호화, 복호화 방식에 대해 설명해보세요

- Cookie와 Session에 대하여 설명해보세요

- 네트워크 보안에 대하여 설명해보세요
