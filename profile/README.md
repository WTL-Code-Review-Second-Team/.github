선택한 주제
주제: CS (Java/JVM/JDK 중심)
선택 이유: Java는 문법만 익혀도 개발은 가능하지만, JVM과 JDK까지 이해하면
성능, 메모리, 컴파일/실행 과정, 디버깅에 대한 설명력이 크게 올라갑니다.
스터디 형식: 주 1회 발표 + 주간 과제 + PR 리뷰
스터디 대상과 수준
대상: Java 기본 문법, 클래스, 객체지향 개념을 알고 있는 사람
수준: 초급 후반 ~ 중급 초반
전제 지식: 변수, 조건문, 반복문, 클래스, 메서드, 컬렉션 기초
목표
Java 소스가 .class 파일로 바뀌고 JVM에서 실행되는 흐름을 설명한다.
JDK, JRE, JVM의 역할 차이를 구분한다.
메모리 구조, GC, class loading, bytecode 기초를 이해한다.
공식 문서와 레퍼런스를 읽고 요약하는 습관을 만든다.
4주 계획
1주차: Java 전체 구조 이해
세부 주제JDK, JRE, JVM 차이
Java 컴파일과 실행 흐름
javac, java, jar 기본 사용

스터디 목표Java 프로그램이 어떤 단계로 실행되는지 말할 수 있다.

산출물"Java 실행 흐름 1장 요약"
Hello World를 통해 컴파일/실행 과정 실습

2주차: JVM과 바이트코드
세부 주제.class 파일 구조 개요
bytecode란 무엇인가
class loader의 역할

스터디 목표소스 코드와 바이트코드, JVM 역할을 구분할 수 있다.

산출물javap로 바이트코드 확인 후 해설
클래스 로딩 과정을 그림으로 정리

3주차: 메모리와 GC
세부 주제stack, heap, method area 개념
GC가 필요한 이유
대표적인 GC 용어 이해

스터디 목표객체가 어디에 생성되고 왜 GC가 필요한지 설명할 수 있다.

산출물메모리 구조 다이어그램
GC 핵심 용어 정리표

4주차: 실전 정리와 회고
세부 주제자주 헷갈리는 개념 정리
JVM 관점에서 코드 읽기
면접 질문 형태로 복습

스터디 목표Java/JVM/JDK 개념을 연결해서 말할 수 있다.

산출물최종 발표 자료
회고 및 다음 단계 학습 계획

운영 방식
매주 1명 또는 1팀이 발표
나머지 구성원은 질문 2개 이상 준비
발표자는 정리 문서와 예제 코드를 PR로 제출
리뷰는 Issue/PR 템플릿을 활용
레퍼런스
아래 자료를 우선 추천합니다.
Java Language Specification
Java 문법과 언어 규칙의 공식 기준입니다. "왜 이 문법이 가능한가"를 확인하기 좋습니다.

Java Virtual Machine Specification
JVM, class file, bytecode, 실행 모델을 공식적으로 설명합니다.

Java SE Documentation
javac, java, jar, javadoc 등 JDK 도구와 표준 API를 확인할 수 있습니다.

OpenJDK
실제 JDK 구현과 릴리스 흐름을 이해하는 데 도움이 됩니다.

Effective Java, 3rd Edition
문법을 넘어 Java를 "잘 쓰는 법"을 익히는 보조 자료로 적합합니다.
