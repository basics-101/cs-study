# DB/week1
1. [데이터베이스](#데이터베이스)
2. [관계대수와 SQL](#관계대수와-SQL)
3. [데이터베이스 설계와 ER모델](#데이터베이스-설계와-ER모델)
4. [물리적 데이터베이스 설계](#물리적-데이터베이스-설계)
5. [릴레이션 정규화](#릴레이션-정규화)
6. [트랜잭션](#트랜잭션)
7. [NoSQL](#NoSQL)
8. [ETC (안해도 됨)](#ETC)

&nbsp;
## 데이터베이스
### 1. 데이터베이스와 파일시스템
- 데이터베이스의 단점
- 무결성 제약조건
### 2. 데이터베이스의 특징과 제약 조건
## 관계대수와 SQL
### 3. SELECT
- ANSI-SQL
- SELECT에 사용되는 키워드들
- SELECT문의 문법 순서와 실행 순서
### 4. SQL
### 5. Join
- Join의 종류
- Left Outer Join과 Right Outer Join의 차이
- Inner Join
- Self Join
### 6. NULL
- NULL 연산
### 7. Trigger와 Procedure
- Trigger와 Procedure의 차이점
- Trigger의 단점
- Trigger를 사용하는 이유
- 무결성을 유지하기 위해 Trigger를 쓰는 예시

## 데이터베이스 설계와 ER모델
### 8. 데이터베이스 설계의 과정
- 각 과정의 설계 목적
### 9. 스키마, 엔티티, 릴레이션, 인스턴스
### 10. 키
- 유일성, 최소성
- 후보키 중에서 기본키를 정하는 기준
- 기본키의 개체 무결성 조건

### 11. 뷰
- 체크 옵션
- 뷰를 쓰는 이유
- 뷰의 단점(독립적인 인덱스를 가질 수 없다)
- 뷰를 읽어오는 과정

## 물리적 데이터베이스 설계
### 12. 데이터베이스와 메모리
- 데이터베이스와 페이징
### 13. 인덱스
- 인덱스를 사용했을 때의 검색속도
- 인덱스 자료구조 종류
- 인덱스 장단점
- 인덱스가 이미 걸려있는 테이블에 대량의 데이터를 삽입하는 경우 어떻게 처리할건가요?
- Table Full Scan VS Index Range Scan
### 14. B Tree와 B+ Tree
- B Tree와 B+ Tree의 차이
- B+ Tree의 장점
### 15. 해시
- 해시탐색, 순차탐색 차이
- 해시탐색의 단점
- 해시충돌이 발생했을때의 대처
- Java HashMap(혹은 각자 알고 있는 언어의 해쉬 관련 자료구조)에서 해시충돌이 발생했을 때의 대처

## 릴레이션 정규화
### 16. 이상현상
- 이상현상의 종류
- 이상현상의 예시
- 이상현상의 원인
### 17. 정규화
- 정규화 종류
- 정규화의 장단점
### 18. 역정규화
- 역정규화를 하는 이유
- 역정규화를 하는 방법

## 트랜잭션
### 19. 트랜잭션
- 트랜잭션의 성질
- Dirty Read
- Phantom Read
- Unrepeatable Read
- 트랜잭션 회복
- Commit, Rollback
- Save point
- 트랜잭션의 특성을 DBMS가 보장하는 방법
### 20. 트랜잭션 격리 수준
- 트랜잭션 격리 수준 각각 설명
- 트랜잭션 격리 수준이 어떻게 작동하는지
### 21. DB Deadlocks

## NoSQL
### 22. NoSQL
### 23. CAP
### 24. NoSQL vs RDB
- RDB를 굳이 사용하는 이유
- NoSQL에서 데이터를 찾는 방식
- NoSQL에서 데이터 중복을 해결하는 방법

## ETC
### Connection Pool
### Hint
### SQL Injection
### Optimizer
### Replication
### Partitioning
### Sharding
### 분산 환경과 트랜잭션
### ORM