# Network/week1
1. [Internet Network](#internet-network)
2. [HTTP Concepts](#http-concepts)
3. [HTTP Method, State Code and Header](#http-method-state-code-and-header)
4. [HTTP Versions](#http-versions)
5. [REST](#rest)
6. [ETC](#etc)

&nbsp;
## Internet Network
### 1. OSI 7계층
- 왜 계층형 구조로 아키텍처를 구성했나요?
### 2. IP와 IP 주소
- TCP, UDP와 IP의 차이점
- 왜 IP주소만으로 HTTP 통신이 이루어지지 않을까?
- 3계층의 다른 프로토콜
- ARP
- ICMP
### 3. TCP와 UDP
- TCP와 UDP를 쓰는 예시
- 왜 DNS는 UDP를 기반으로 처리할까?
- TCP의 장점과 UDP의 단점
- TCP의 흐름제어, 혼잡제어
- 3-way Handshake, 4-way Handshake
- 연결과 연결해제 간에 왜 한 단계의 차이가 날까?
- 왜 굳이 3단계 4단계를 거쳐서 연결을 하고 연결해제를 할까?
### 4. 로드밸런싱
- 로드밸런싱의 목적
- 로드밸런싱의 종류
- L4 로드밸런서, L7 로드밸런서
### 5. 라우팅
- 라우팅 프로토콜의 종류
- 라우팅을 사용하는 이유
- 라우팅 중 오류에 대응하는 법
- 패리티 검사는 통과했는데, 결국 패킷이 손상된 경우?
### 6. DNS
- DNS 구성 요소
- DNS 동작 방식(iterative, recursive)
### 7. NAT
- NAT를 쓰는 이유
- IP주소를 왜 절약하는지
### 8. DHCP
- DHCP를 왜 쓰는가?
- DHCP 과정
- DHCP 예시
- DHCP 정보?
### 9. 서브넷 마스크와 게이트웨이
### 10. 소켓
- 포트 번호란
- 소켓과 포트의 연관성?

## HTTP Concepts
### 11. HTTP
- HTTP 특징(Stateless, connectionless)
- 왜 Stateless인데 왜 사용자의 정보를 저장하는지?
### 12. 쿠키와 세션
- 쿠키와 세션의 life cycle
- 세션을 사용하는 이유
- 세션이 저장되는 위치(서버의 어떤 곳)
- 다중 서버 구조일 때, 각 서버에서 하나의 사용자를 구분하는 방법
### 13. URI, URL, URN

## HTTP Method, State Code and Header
### 14. HTTP Method
- GET, POST 차이
    - 캐시 여부
- POST, PUT 차이
- PUT, PATCH 차이
- HTTP 메소드의 멱등성
### 15. HTTP 응답코드
- 401/403 차이
### 16. HTTP 헤더
- HTTP 헤더의 종류

## HTTP Versions
### 17. HTTP/1.1과 그 이전
### 18. HTTP/2.0
- 헤더 압축
### 19. HTTP/3.0
- UDP
- HTTP/3.0
- 지원하지 않는 HTTP 버전
### 20. HTTPS
- SSL?
- 인증서를 사용하는 이유
- TLS Handshake
- SSL과 TLS

## REST
### 21. REST API
- REST API를 사용하는 이유
- REST API 권장 설계 규칙
### 22. RESTful
- RESTful의 목적

## ETC
### 23. 웹 서버와 WAS의 차이점
- 웹 서버와 WAS의 대표적인 예시
- 웹 서버와 WAS는 상호 배타적인 관계인가?
### 24. OAuth
- 기존 로그인의 단점
- OAuth 인증 과정
- OAuth와 JWT
### 25. www.kakao.com을 브라우저에 입력하고 엔터를 쳤을 때, 네트워크상 어떤 일이 일어나는지 설명해 주세요.
- 요청 및 응답 메시지가 유실된 경우 어떻게 처리하는지