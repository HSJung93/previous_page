---
title: "운영체제 속 프로세스 속 스레드"
date: 2021-10-01T14:24:00+09:00
categories:
  - 메모
tags:
  - 프로세스
  - 스레드
header:
  teaser: /assets/images/slipBox.jpg
---

## 운영 체제
- 컴퓨터의 하드웨어를 사용하게 해주는 프로그램
- 동시에 여러 프로그램을 사용할 수 있도록 해준다.

## 프로세스
- 현재 실행되고 있는 프로그램
- 자바 프로그램을 실행시키는 JVM도 프로그램, 운영체제의 입장에서 프로세스로 실행되는 것이다.

## 스레드
- 하나의 프로세스 안에서도 여러 개의 흐름이 동작할 수 있다. 이 하나의 흐름이 한 스레드이다. 
- 자바 프로그램 안에서도 여러 흐름이 동작할 수 있다. 자바 프로그램을 만들 때에 여러 흐름을 동시에 실행시키고 싶다면 스레드를 사용한다. 