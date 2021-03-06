---
layout: single
permalink: /about/
title: "About Me"
category: etc
author_profile: true
header:
  teaser : /assets/images/category/subin.jpg
  overlay_image : /assets/images/category/subin.jpg
  overlay_filter: 0.1
---

# 둥둥 (Floating218)

## Link

- [블로그 프로필](http://floating218.github.io/about/)
- [Github](http://github.com/floating218)
- 소속: 서울대학교 [인지컴퓨팅 연구실](http://cclab.snu.ac.kr/) 소속

## 스킬

- 프로그래밍 언어: Python, R, javascript, HTML, C#, SQL, Java
- 데이터 분석: Spark, Hadoop, R studio, Rapidminer, Knime
- 딥러닝 프레임워크: Pytorch
- 개발: Django, Unity
- 자격증: 정보처리기사

## 공부

- [알고리즘 공부 정리](https://floating218.github.io/categories/algorithm)
- [프로그래밍 언어 공부 정리](https://floating218.github.io/categories/cheatsheet)
- [OS 공부 정리](https://floating218.github.io/categories/os)

## 참여 과제/프로젝트

### **대용량 비정형 데이터 분석 기법을 통한 교육용 게임 로그 데이터 분석** (2018.9 - 2020.2)

- 과제 개요 및 목표: 교육용 게임 회사 “Enuma”와 협업을 하여 "Kitkit school"이라는 어린이 교육용 게임으로부터 수집한 데이터를 전처리하고 분석하는 연구 과제입니다. 과제 목표는 비정형 대규모 데이터를 이용해서 기계학습 분석 모형을 개발하는 것입니다.
- 제가 맡은 업무
    - 연구실에서 보유한 2개 서버 컴퓨터에 hadoop 파일 시스템과 spark 분산 처리 시스템을 구축
    - Spark 분산 처리 시스템을 통해 json형태의 대용량 비정형 로그 데이터 (약 1TB 규모) 전처리
    - 통계분석모델(Correlation,T-test,Anova) 및 기계학습모델(Random forest, Logistic regression) 구축을 통한 교육용 게임 앱 개선 방향 제안
- 결과물 (코드)
    - [깃허브 레퍼지토리](https://github.com/floating218/spark_kitkit_project)
    - [블로그](https://floating218.github.io/categories/spark)
        - [프로젝트 소개](https://floating218.github.io/kitkit-school/)
        - [로그 데이터 전처리하기](https://floating218.github.io/spark-kitkitprocessing/)
        - [간단한 모델링 하기](https://floating218.github.io/spark-kitkitmodelling/)
- 결과물 (논문)
    - “[Should students use digital scratchpads? Impact of using a digital assistive tool on arithmetic problem-solving](https://link.springer.com/chapter/10.1007/978-3-030-23207-8_29)”. The 20th International Conference on Artificial Intelligence in Education (AIED 2019).
        - 요약: 게임에서 제공하는 scratchpad UI와 학습 성취도 간에 존재하는 상관관계를 인지과부하와 결부시켜 설명하였습니다.
    - “Gaming detection using touch interactions” 석사 학위 논문
        - 요약: 교육용 게임에서 발생할 수 있는 현상인 “시스템 게이밍” 행동 여부를 판별할 수 있는 데이터를 구축하고, 기계학습 모델을 구현하는 연구입니다. "시스템 게이밍"이란, 성실하게 게임에 임하지 않고 시스템의 특성을 이용해 요령껏 레벨을 클리어하는 행동을 의미합니다. 이런 행동을 detect하기 위해, 본 연구에서는 화면 상에서 어떻게 드래그 & 드롭했는지를 묘사하는 touch behavior 특성을 추출하였으며, 이 특성을 기계학습 알고리즘에 학습시켜서 "시스템 게이밍"여부를 예측할 수 있는 모델을 구현하였습니다.

### **인터넷중독 유형분석 및 원인분석 모델 개발 프로젝트**:(2018.9 - 2019.9)

- 과제 개요 및 목표: 청소년들의 개인적, 사회적, 가정적 요인 데이터를 수집하여 그들의 인터넷 과사용 유형을 분류하고 그 원인을 통한 유형을 분류하는 기계학습 모델을 구현하는 프로젝트
- 제가 맡은 업무
    - 상담 데이터로부터 인터넷 과사용 유형을 분류해서 Label로 제작
    - 설문 데이터로부터 수집한 “개인적 요인”, “사회적 요인”, “가정적 요인” 정보를 통해 기계학습 모델(SVM) 구축
    - Django 프레임워크, Mysql DB를 통한 설문 조사 사이트 구축
- 결과물 (웹사이트)
    - [프로젝트 결과물 (설문 조사 사이트)](http://detox.snu.ac.kr/)
- 결과물 (논문)
    - “청소년의 스마트 미디어 과의존과 인터넷 콘텐츠 유형의 연관 관계에 대한 연구”. Korea Computer Congress 2019.
        - 요약: 인터넷중독 유형분석 및 원인분석 모델 개발 프로젝트에 참여하면서 제출한 논문으로, 스마트 미디어 과의존 여부가 사용하는 컨텐츠 유형에 따라 여떻게 변하는지를 설명하고자 하였습니다.

### **추천시스템 구현 과제** (2018.1 - 2018.2)

- 과제 개요 및 목표: 예약 데이터와 검색 데이터와 유저 프로필 데이터를 바탕으로 추천 시스템을 구현하는 과제를 수행하였음.
- 제가 맡은 업무
    - Pandas, Numpy 라이브러리를 활용한 사용자 데이터 가공 (300만건의 예약 데이터, 400만건의 전화 데이터, 3만건의 식당업체 데이터, 80만명의 사용자 데모 데이터, 80만명의 상위 만개 검색어 데이터)
    - 협업필터링(Collaborative filtering), 컨텐츠기반필터링을 결합한 혼합형 추천 모델 구현
    - 구현한 추천 모델을 웹사이트에 이식
    - Flask 프레임워크, 네이버지도API를 통해 웹사이트에 검색 기능, 지도 기능 구현
- 결과물
    - [프로젝트 발표 자료](https://github.com/floating218/restaurant_recommendation_project)

### **문장형 수학 문제 풀이 프로젝트** (2019.1 – present)

- 과제 개요 및 목표: 이 프로젝트는 문장형(서술형) 수학 문제를 자동으로 풀어주는 인공지능 알고리즘을 개발하는 프로젝트입니다.
- 제가 맡은 업무
    - 수학 문제의 해답 데이터 수집을 보조
    - 프로젝트에서 사용하는 문장형 수학 문제 풀이 모델 구현
    - 수업 중에 프로젝트 내용 발표.
- 결과물
    - [깃허브 레퍼지토리에 정리한 내용](https://github.com/floating218/nlp_projects)

### **설문 조사 전용 챗봇 시스템 개발 프로젝트** (2019.3 – 2020.1)

- 과제 개요 및 목표: 인터넷중독 유형분석 및 원인분석 모델 개발 프로젝트의 연구비를 받아 수행한 프로젝트입니다.
- 제가 맡은 업무
    - 설문 조사를 위한 챗봇 개발 및 실험을 보조
    - 수집한 데이터를 분석
    - 논문 작성
- 결과물(논문)
    - “Application of humanization to survey chatbots: Change in chatbot perception, survey data quality, and interaction experience”(Conference on Human Factors in Computing Systems, 제2저자, CHI 2021 제출한 상태)
        - 요약: 논문 주제는 인간형 챗봇과 기계적 챗봇 사이의 효과를 비교하는 것이었습니다. 인간형 챗봇이 기계적 챗봇에 비해 설문자의 솔직한 대답을 이끌어낼 수 있다는 가설을 검증하였습니다.

### **삼성전자DS 사원 교육프로그램 조교** (2019.4 – present)

- 과제 개요 및 목표: 삼성전자 사원을 대상으로 서울대학교 공학 분야 교수진들이 참여하는 강의에 조교로 참여하였습니다. 이 강의는 데이터 분석 및 데이터 시각화 전용 SW인 “Rapid*minder”와 “Knime”의 사용법을 교육하는 강의였습니다. 강의의 내용은 데이터 전처리 및 기계학습*의 개론 및 소프트웨어의 사용법 안내, 실습 등이었습니다.
- 제가 맡은 업무
    - 강의 자료 제작
    - 실습 진행
    - 시험 문항 제작 및 채점

## 전공 학업 내역

- 정보융합 (통계) (2019.2) : CS 분야 연구를 위해 필요한 통계적 지식을 습득하였습니다. 선형대수, 회귀분석, 상관분석, t-test, ANOVA 등에 대해 학습하였습니다.
- 정보융합 기계학습 (2020.1) : 기계학습(머신러닝)에 대한 전반적인 지식을 습득함. 선형회귀, 로지스틱회귀, 의사결정나무, 앙상블, SVM, Nearst neighbor, Clustering, Principle component analysis 등 classic한 기계학습 알고리즘을 학습하였습니다.
    - [정리 포스팅 작성중](https://floating218.github.io/categories/ml)
- 정보융합 특강 (HCI) (2018.2) : Human computer interaction 분야의 연구를 수행하는 방법을 습득하고, 프로젝트를 수행하였습니다. 프로젝트 결과물로, 기숙사 구성원 간 집안일을 분배하기 위한 모바일 애플리케이션 프로토타입을 제작하고, 실험을 수행함. 그 결과를 Mobile HCI conference의 poster로 발표하였습니다.
- 인지컴퓨팅 특강 (2018.2) : Spark 분산 처리 시스템 이용 방법과 기계학습을 적용한 데이터 마이닝 분석 기법에 대해 학습하였습니다. 모바일 교육용 게임을 통해 수집한 대용량 비정형 데이터를 가공, 분석하여 AIED (Artificial intelligence in education) conference의 short paper를 제출, 발표하였습니다.
- 정보융합 뉴럴네트워크 (2019.2) : 딥러닝 기법의 매커니즘에 대해 학습함. Multiple Layer Perceptron을 비롯해서 CNN, RNN, LSTM, GAN, 등을 학습하였습니다. 수업 중에 조원들과 함께 연구실에서 진행중인 문장형 수학 문제 풀이 프로젝트에 적용한 BERT 모델에 대해 발표하였습니다.
- 컴퓨터언어학입문1 (2019.2) : Natural language processing 연구 분야의 전반에 대해 학습함. LSTM 뿐만 아니라, encoder-decoder 모델, attention, transformer, bert, xlnet등의 언어모델을 학습하였습니다. 실습과제로는 sentimental analysis(감정분석) task에 여러가지 언어모델을 적용하였습니다. Pytorch 프레임워크를 사용하였습니다.
- 정보융합 연구조사방법론 (2020.1) : 연구 및 논문 작성 방법에 대한 전반을 학습함. 조원들과 함께 프로젝트를 진행하여 논문을 작성하였습니다. 프로젝트 주제는 모바일 알림 애플리케이션을 제작하는 것이었습니다.

## 논문

- “WithDorm: Dormitory Solution for Linking Roommates”. MobileHCI 2019 Late Breaking Results (Poster) : 정보융합 특강(HCI) 수업의 결과물로 작성한 late breaking results(poster paper)입니다. 기숙사에 거주하는 학생들을 대상으로 가사일을 분배하는 것을 도와주는 모바일 애플리케이션 프로토타입을 구현하고 이것의 효과성을 검증하는 HCI 연구였습니다. 작성된 짧은 논문은 2019년도 Mobile HCI conference (국제 학회)에서 발표하였습니다.
- “Should students use digital scratchpads? Impact of using a digital assistive tool on arithmetic problem-solving”. The 20th International Conference on Artificial Intelligence in Education (AIED 2019). : 교육용 게임으로부터 수집한 비정형 대용량 데이터를 통해 학생들의 학습 특성을 분석한 연구입니다. 게임에서 제공하는 scratchpad UI와 학습 성취도 간에 존재하는 상관관계를 인지과부하와 결부시켜 설명하였습니다. 본 paper는 AIED 2019 (국제 학회)에서 발표하였습니다.
- “청소년의 스마트 미디어 과의존과 인터넷 콘텐츠 유형의 연관 관계에 대한 연구”. Korea Computer Congress 2019. : 인터넷중독 유형분석 및 원인분석 모델 개발 프로젝트에 참여하면서 제출한 논문으로, 스마트 미디어 과의존 여부가 사용하는 컨텐츠 유형에 따라 여떻게 변하는지를 설명하고자 하였습니다. 본 paper는 kcc (국내 학회)에서 발표하였습니다.
- “Application of humanization to survey chatbots: Change in chatbot perception, survey data quality, and interaction experience”. In Proceedings of the SIGCHI Conference on Human Factors in Computing Systems (CHI ’21 심사중) : 챗봇 시스템 개발 프로젝트에서 작성한 논문으로 논문 주제는 인간형 챗봇과 기계적 챗봇 사이의 효과를 비교하는 것이었습니다. 두가지 유형의 챗봇에 대해, 사용자가 자신의 개인 정보를 얼마나 솔직하게 공개할 수 있는지 그리고 사회적인 기준에 맞춰서 거짓된 답변을 하는지 등을 측정하고 분석하였습니다. 본 논문은 CHI 2021 (국제 학회)에 제출하였으며, 현재 심사 중입니다.
- 작성 중인 학위 논문 “Gaming detection using touch interactions” : 교육용 게임에서 발생할 수 있는 현상인 “gaming the system” 행동 여부를 판별할 수 있는 데이터를 구축하고, 기계학습 모델을 구현하는 연구입니다. Gaming the system이란, 성실하게 게임에 임하지 않고 시스템의 특성을 이용해 요령껏 레벨을 클리어하는 행동을 의미합니다. 이런 행동을 detect하기 위해, 본 연구에서는 화면 상에서 어떻게 드래그 & 드롭했는지를 묘사하는 touch behavior 특성을 이용하였습니다.