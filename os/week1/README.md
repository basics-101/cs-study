# OS/week1
1. [Operating System](#Operating-System)
2. [Process and Thread](#Process-and-Thread)
3. [CPU Scheduling](#CPU-Scheduling)
4. [Synchronization and Deadlocks](#Synchronization-and-Deadlocks)
5. [Memory Management](#Memory-Management)

&nbsp;
## Operating System
### 운영체제
- 운영체제가 관리하는 시스템 자원의 종류
### 커널
- 커널의 역할/목적/특성/장점
- 커널 종류
- 계층형 구조 커널의 형태
- 계층형 구조 커널의 장점
### 인터럽트
- 인터럽트 과정
- 인터럽트의 종류
- 인터럽트가 없다면 달라지는 점
### 캐시, 레지스터, 버퍼
- 캐시의 지역성
- 캐시를 읽는 과정 (저장?)
- 캐시를 쓰는 이유
- 캐시 메모리가 가득 찼을 때

## Process and Thread
### 프로세스
- 실행되지 않고 있는 프로그램은 프로세스가 아닌가요?
- 프로세스 메모리 구조 (BSS, Code, Data, Stack, Heap)
- BSS 영역에 해당되는 예시
- Stack, Heap의 차이
- PCB에 저장되는 프로세스 정보 종류
- 프로세스 생명주기(프로세스 상태와 함께)
### 스레드
- 스레드의 유형
- 스레드의 메모리 구조
- Stack과 PC를 독립적으로 할당하는 이유
### 멀티 프로세스와 멀티 스레드 차이
- Context Switching이 언제 발생?
- Overhead에 대한 해결책
### IPC
- 메세지 전달 방식에 대해서 설명
- Shared Memory 방식의 단점

## CPU Scheduling
### Context Switching
- Context Switching 과정과 Context 정보가 어디에 저장되는지?
- PCB는 그러면 언제 생성이 되나요?
### 스케줄링

## Synchronization and Deadlocks
### 동기와 비동기
- Blocking and Non-Blocking
### 임계 구역(Critical Section)
- 동시성 문제?
- 임계 구역 문제 해결
### 기아상태와 교착상태
- 결코 일어나지 않을 이벤트?
- 다중 프로그래밍 시스템 예시
- 교착 상태의 조건
- 교착 상태 해결 알고리즘
### 동기화 도구
- 동기화 도구가 필요한 이유
- 동기화 문제?
- Mutex
- Semaphore

## Memory Management
### 페이징과 세그멘테이션
- 페이징과 세그멘테이션을 쓰는 이유
- 페이징과 세그멘테이션의 차이
### 가상메모리
- 매핑 테이블
### 페이지 교체
- 페이지 교체 알고리즘 종류