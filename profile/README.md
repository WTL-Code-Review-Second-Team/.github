<div align="center">

# ☕ CS Study
# Java · JVM · JDK

> **Java 문법을 넘어 실행 원리까지 이해하는 4주 스터디**

![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk)
![Study](https://img.shields.io/badge/Study-4Weeks-blue)
![Level](https://img.shields.io/badge/Level-Beginner~Intermediate-success)
![License](https://img.shields.io/badge/Docs-GitHub%20Pages-brightgreen)

</div>

---

# 📚 목차

- [📖 스터디 소개](#-스터디-소개)
- [🎯 스터디 목표](#-스터디-목표)
- [🗓️ 4주 스터디 계획](#️-4주-스터디-계획)
- [👨‍💻 운영 방식](#-운영-방식)
- [📚 레퍼런스](#-레퍼런스)
- [📂 GitHub 구성](#-github-구성)
- [🤖 AI 활용 기록](#-ai-활용-기록)

---

# 📖 스터디 소개

Java 문법을 넘어서,

> **"Java 코드가 어떻게 실행되는가?"**

를 이해하기 위한 CS 스터디입니다.

Java를 한 번 이상 학습한 사람을 대상으로

- ☕ Java 실행 구조
- ⚙ JVM
- 📦 JDK / JRE
- 🧠 메모리 구조
- ♻ Garbage Collection
- 📄 Bytecode

까지 연결해서 학습합니다.

---

# 👀 한눈에 보기

| 항목 | 내용 |
|------|------|
| 📌 선택 주제 | **CS (Java/JVM/JDK 중심)** |
| 👨‍🏫 형식 | 발표 + 과제 + PR 리뷰 |
| 👨‍💻 대상 | Java 기본 문법 학습자 |
| ⭐ 수준 | 초급 후반 ~ 중급 초반 |
| 🎯 목표 | JVM 실행 흐름을 설명할 수 있는 수준 |

---

# ❓ 왜 이 주제인가?

## 🚀 Java를 "사용"하는 것과 "이해"하는 것은 다릅니다.

많은 개발자가 Java 문법은 알고 있지만

- JVM이 무엇인지
- 메모리가 어떻게 동작하는지
- GC가 언제 실행되는지

설명하지 못합니다.

이 스터디에서는

**문법 → 실행 구조 → 메모리 → 성능**

까지 연결해서 학습합니다.

---

# 🎯 스터디 목표

✅ Java 실행 과정을 설명할 수 있다.

✅ JDK / JRE / JVM 차이를 설명할 수 있다.

✅ Bytecode와 Class Loading을 이해한다.

✅ Stack / Heap / GC를 연결해서 설명할 수 있다.

✅ 공식 문서를 읽는 습관을 만든다.

---

# 🗓️ 4주 스터디 계획

| 주차 | 주제 | 목표 | 결과물 |
|------|------|------|---------|
| 📅 Week1 | Java 실행 구조 | 컴파일부터 실행까지 이해 | 실행 흐름 정리 |
| 📅 Week2 | JVM & Bytecode | Class Loader와 Bytecode 이해 | javap 분석 |
| 📅 Week3 | Memory & GC | Stack / Heap / GC 이해 | 메모리 다이어그램 |
| 📅 Week4 | Review | JVM 관점으로 코드 읽기 | 발표 자료 |

---

# 🗺️ 학습 흐름

```text
Java Source (.java)
        │
        ▼
 javac Compiler
        │
        ▼
Bytecode (.class)
        │
        ▼
   JVM
        │
        ▼
 Class Loader
        │
        ▼
 Runtime Data Area
        │
        ▼
 Garbage Collector
        │
        ▼
 Program Execution
```

---

# 👨‍💻 운영 방식

### 🔀 GitHub

- Issue 작성
- PR 제출
- 코드 리뷰 진행
- 
### 💬 토론

- 질문 2개 이상 준비
- 리뷰 후 토론
