# Tech Interview

**:book: Contents**
1. [Data Structure](#1-data-structure)
2. [Network](#2-network)
3. [Operating System](#3-operating-system)
4. [Database](#4-database)
5. [Design Pattern](#5-design-pattern)
6. [Algorithm](#6-algorithm)
7. [Java](#7-java)
8. [JavaScript](#8-javascript)
9. [Spring](#9-spring)
10. [Security](#10-security)
11. [ETC](#11-etc)

---

## 1. Data Structure
* Array
* LinkedList
* HashTable
* Stack
* Queue
* Graph
* Tree
* 그래프(Graph)와 트리(Tree)의 차이점
* Binary Heap
* Red-Black Tree
* B+ Tree

## 2. Network
* OSI 7계층 [(완료) 게시물 링크](https://learnote-dev.com/cs/OSI-7-Layer-Model/)
* TCP/IP의 개념 [(완료) 게시물 링크](https://learnote-dev.com/cs/TCP-IP/)
* TCP와 UDP [(완료) 게시물 링크](https://learnote-dev.com/cs/TCP%EC%99%80-UDP/)
* TCP와 UDP의 헤더 분석 [(완료) 게시물 링크](https://learnote-dev.com/cs/TCP%EC%99%80-UDP/)
* TCP의 3-way-handshake와 4-way-handshake
  * Q. TCP의 연결 설정 과정(3단계)과 연결 종료 과정(4단계)이 단계가 차이나는 이유?
  * Q. 만약 Server에서 FIN 플래그를 전송하기 전에 전송한 패킷이 Routing 지연이나 패킷 유실로 인한 재전송 등으로 인해 FIN 패킷보다 늦게 도착하는 상황이 발생하면 어떻게 될까?
  * Q. 초기 Sequence Number인 ISN을 0부터 시작하지 않고 난수를 생성해서 설정하는 이유?
* HTTP와 HTTPS
* HTTP 요청/응답 헤더
* HTTP와 HTTPS 동작 과정
* CORS란
* GET 메서드와 POST 메서드
* 쿠키(Cookie)와 세션(Session)
* DNS
* REST와 RESTful의 개념
* 소켓(Socket)이란
* Socket.io와 WebSocket의 차이
* Frame, Packet, Segment, Datagram

## 3. Operating System
* 프로세스와 스레드의 차이(Process vs Thread) [(완료) 게시물 링크](https://learnote-dev.com/cs/%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%EC%99%80%EC%8A%A4%EB%A0%88%EB%93%9C%EC%9D%98-%EC%B0%A8%EC%9D%B4/)
* 멀티 프로세스 대신 멀티 스레드를 사용하는 이유 [(완료) 게시물 링크](https://learnote-dev.com/cs/%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%EC%99%80%EC%8A%A4%EB%A0%88%EB%93%9C%EC%9D%98-%EC%B0%A8%EC%9D%B4/)
* Thread-safe
* 동기화 객체의 종류
* 뮤텍스와 세마포어의 차이
* 스케줄러
* 동기와 비동기
* 프로세스 동기화
* 메모리 관리 전략
* 가상 메모리
* 캐시의 지역성
* 교착상태(데드락, Deadlock)의 개념과 조건
* 사용자 수준 스레드와 커널 수준 스레드
* 외부 단편화와 내부 단편화
* Context Switching
* Swapping

## 4. Database
* 데이터베이스 풀 [(완료) 게시물 링크](https://learnote-dev.com/cs/커넥션-풀/)
* 정규화(1차 2차 3차 BCNF)
* 트랜잭션(Transaction) 이란
* 트랜잭션 격리 수준(Transaction Isolation Level)
* Join
* SQL injection
* Index란
* Statement와 PrepareStatement
* RDBMS와 NoSQL
* 효과적인 쿼리 저장
* 옵티마이저(Optimizer)란
* Replication
* 파티셔닝(Partitioning)
* 샤딩(Sharding)
* 객체 관계 매핑(Object-relational mapping, ORM)이란
* java JDBC

## 5. Design Pattern
* 디자인 패턴의 개념과 종류
* Singleton 패턴
* Strategy 패턴
* Template Method 패턴
* Factory Method 패턴
* MVC1 패턴과 MVC2 패턴

## 6. Algorithm 
* BigO
* DFS와 BFS의 차이
* Fibonacci에서의 세 가지(Recursion, Dynamic Programming, 반복) 방식에 대한 시간복잡도와 공간복잡도 차이
* 정렬 알고리즘의 종류와 개념
* Greedy 알고리즘
* 최소 신장 트리(MST, Minimum Spanning Tree)란
* Kruskal MST 알고리즘
* Prim MST 알고리즘

## 7. Java
* java 프로그래밍이란
* Java SE와 Java EE 애플리케이션 차이
* java와 c/c++의 차이점
* java 언어의 장단점
* java의 접근 제어자의 종류와 특징
* java의 데이터 타입
* Wrapper class
* OOP의 4가지 특징
  * 추상화(Abstraction), 캡슐화(Encapsulation), 상속(Inheritance), 다형성(Polymorphism)
* OOP의 5대 원칙 (SOLID)
* 객체지향 프로그래밍과 절차지향 프로그래밍의 차이
* 객체지향(Object-Oriented)이란
* java의 non-static 멤버와 static 멤버의 차이
  * Q. java의 main 메서드가 static인 이유
* java의 final 키워드 (final/finally/finalize)
* java의 제네릭(Generic)과 c++의 템플릿(Template)의 차이
* java의 가비지 컬렉션(Garbage Collection) 처리 방법
* java 직렬화(Serialization)와 역직렬화(Deserialization)란 무엇인가
* 클래스, 객체, 인스턴스의 차이
* 객체(Object)란 무엇인가
* 오버로딩과 오버라이딩의 차이(Overloading vs Overriding)
* Call by Reference와 Call by Value의 차이
* 인터페이스와 추상 클래스의 차이(Interface vs Abstract Class)
* JVM 구조
* Java Collections Framework
  * java Map 인터페이스 구현체의 종류
  * java Set 인터페이스 구현체의 종류
  * java List 인터페이스 구현체의 종류
* Annotation
* String, StringBuilder, StringBuffer
* 동기화와 비동기화의 차이(Syncronous vs Asyncronous)
* java에서 '=='와 'equals()'의 차이
* java의 리플렉션(Reflection) 이란
* Stream이란?
* Lambda란?

## 8. JavaScript
* JavaScript Event Loop
* 함수 선언식과 함수 표현식
* 화살표 함수(Arrow Function)
* 향상된 객체 리터럴(Enhanced Object Literals)
* Modules
* 디스트럭처링(Destructuring)
* 전개 연산자(Spread Operator)
* 호이스팅(Hoisting)
* Closure
* this
* Promise
* Async/Await

## 9. Spring
* 스프링 프레임워크란
* Spring, Spring MVC, Spring Boot의 차이
* Bean이란
* Container란
* IOC(Inversion of Control, 제어의 역전)란
* MVC 패턴이란
* DI(Dependency Injection, 의존성 주입)란
* AOP(Aspect Oriented Programming)란
* POJO
* DAO와 DTO의 차이
* Spring JDBC를 이용한 데이터 접근
* Filter와 Interceptor 차이

## 10. Security 
* 대칭키와 비대칭키 차이
* 패스워드 암호화 방법 
* SQL Injection 공격 
* CSRF 공격 
* XSS 공격
* OAuth

## 11. ETC
* TDD란
* 웹 브라우저에서 서버로 어떤 페이지를 요청하면 일어나는 일련의 과정을 설명
  * Ex. url에 'www.naver.com' 을 입력했다. 일어나는 현상에 대해 아는대로 설명하라.
* 컴파일러와 인터프리터
* 분산락
* 프레임워크와 라이브러리의 차이
* 64bit CPU와 32bit CPU 차이
* CVS, SVN, Git
* Git Branch 종류(5가지)
* 웹 서버(Web Server)와 웹 어플리케이션 서버(WAS)의 차이
* 애자일 방법론이란
* Servlet과 JSP
* Redis와 Memcached의 차이
* Maven과 Gradle의 차이
* Blocking과 Non-Blocking
* 함수형 프로그래밍이란
* 이벤트 기반 프로그래밍이란
* Mock이란

---
