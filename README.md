# 타이타닉 데이터셋 심층 분석 프로젝트

## 목차
1. [프로젝트 개요](#프로젝트-개요)
2. [데이터셋 설명](#데이터셋-설명)
3. [분석 목표](#분석-목표)
4. [주요 분석 내용](#주요-분석-내용)
5. [기술 스택](#기술-스택)
6. [프로젝트 구조](#프로젝트-구조)
7. [설치 및 실행 방법](#설치-및-실행-방법)

## 프로젝트 개요
"Titanic - Machine Learning from Disaster" 데이터셋을 활용하여 타이타닉 침몰 사고의 생존자 특성을 분석하고 잠재적 인사이트를 도출하는 것을 목표로 합니다.

## 데이터셋 설명

타이타닉 데이터셋 특성:

- PassengerId: 승객 고유 식별 번호
- Survived: 생존 여부 (0 = 사망, 1 = 생존)
- Pclass: 객실 등급 (1 = 1등급, 2 = 2등급, 3 = 3등급)
- Name: 승객 이름
- Sex: 성별
- Age: 나이
- SibSp: 함께 탑승한 형제자매 또는 배우자의 수
- Parch: 함께 탑승한 부모 또는 자녀의 수
- Ticket: 티켓 번호
- Fare: 요금
- Cabin: 객실 번호
- Embarked: 승선 항구 (C = Cherbourg, Q = Queenstown, S = Southampton)

## 분석 목표

1. 승객의 다양한 특성과 생존율 간의 상관관계 파악
2. 통계적 검증을 통한 가설 검정 및 새로운 인사이트 도출

## 주요 분석 내용

1. **데이터 전처리 및 탐색적 데이터 분석 (EDA)**
   - 결측치 처리 및 이상치 탐지
   - 기술 통계량 분석
   - 변수 간 상관관계 분석

2. **고급 데이터 시각화**
   - 다변량 분석을 위한 복합 그래프 생성

## 기술 스택

- **프로그래밍 언어**: Python 3.8+
- **데이터 처리**: pandas, numpy
- **데이터 시각화**: matplotlib
