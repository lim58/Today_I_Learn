# [3/28] http  https

생성일: 2023년 3월 29일 오전 8:24

### HTTP

(Hyper Text Transfer Protocol)

: **인터넷에서 데이터를 주고받을 수 있는 프로토콜** 

> **www** (월드 와이드 웹) 의 토대
> 

> 하이퍼텍스트 링크를 사용하여 웹페이지를 로드함
> 

> **웹 서버와 브라우저 상호 간 데이터를 전송 및 통신함**
> 

   🔗 텍스트, 이미지, 비디오, 음성 등 

- **http 특징**
    - **요청 및 응답 메세지가 대응**되는 구조
    - **메세지 교환 형태**  (http 메세지를 주고받으며 통신함)
    - **비연결성 프로토콜**
    
           → 클라이언트 요청에 대해 서버가 응답을 마치면 맺었던 연결을 끊음, 이전 상태 유지X
    
- **http 동작**
    
    : 사용자가 브라우저를 통해 서비스를 요청할 시 
    
     서버에서 해당 사항에 맞는 결과를 찾아 사용자에게 응답함
    
    ---
    
    - **http 요청** (client → server)
        
        :  인터넷 통신 플랫폼에서 웹사이트를 로드하는데 필요한 정보를 요청하는 방법   
        
         🔗 버전유형, URL, HTTP 매서드, 요청헤더, 본문을 포함
        
    - **http 응답** (server → client)
        
        : 인터넷 서버로부터 수신하는 응답 , http 요청에 대한 응답
        
        🔗 HTTP 상태코드, 응답헤더, 본문을 포함
        

### http 매서드

: **요청 / 응답 데이터 전송 방식** (client ↔ server)

서버가 수행해야 할 동작을 지정하여 요청을 보냄

- **GET** - 리소스 조회
- **POST** - 요청 데이터 처리
- **PUT** - 리소스를 대처하는 매서드
- **PATCH** - 리소스 부분 변경
- **DELETE** - 리소스 제거

⇒  **데이터에 대한 조회, 생성, 변경, 삭제 동작을 HTTP 요청 매서드로 정의**함

### HTTPS

(Secure Hyper Text Transfer Protocol) 

: **http의 보안 버전**                                                                                               

> SSL / TLS 등 데이터를 암호화하는 **인증서를 통해 통신 내용을 암호화** 시킴
> 

> **보안성이 높아지고, 검색엔진이 최적화**됨
> 

    ex) 계정 로그인, 전자 상거래 등에서 사용됨

### HTTP / HTTPS 차이점

|  |         http |         https |
| --- | --- | --- |
|        암호화 |           X |            O |
|         속도 |         빠름 |          느림 |
|         비용 |            - | 추가 비용 발생 |

**http** : **암호화 되지 않은 프로토콜**

**https** : 데이터 **암호화를 추가한 프로토콜**

*→ https는 데이터가 변경되거나 손상되는 것을 방지하지만* 

    *http보다 속도가 느리고 인증서를 발급하면서 추가 비용이 발생한다는 단점이 있음*