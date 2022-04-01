# SINGLAB 테크로스 프로젝트

[![made-with-r](https://img.shields.io/badge/Built%20with-R-1f425f.svg)](https://www.r-project.org/)
[![made-with-python](https://img.shields.io/badge/Built%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-numpy](https://img.shields.io/badge/Built%20with-numpy-1f425f.svg)](https://numpy.org/)
[![made-with-pandas](https://img.shields.io/badge/Built%20with-pandas-1f425f.svg)](https://pandas.pydata.org/)
[![made-with-matplotlib](https://img.shields.io/badge/Built%20with-matplotlib-1f425f.svg)](https://matplotlib.org/)
[![made-with-seaborn](https://img.shields.io/badge/Built%20with-seaborn-1f425f.svg)](http://seaborn.pydata.org/)
[![made-with-sklearn](https://img.shields.io/badge/Built%20with-sklearn-1f425f.svg)](https://scikit-learn.org/)
[![made-with-jupyter](https://img.shields.io/badge/Built%20with-Jupyter-1f425f.svg)](https://jupyter.org/)

## 목적

- [ ] 데이터 정제:
    - ERD 정리 : 데이터베이스간 연관관계를 파악하여, 서로의 병합 여부를 파악
    - 학습데이터 확보 : 데이터간 병합을 통한 하나의 큰 학습데이터 셋 확보

- [ ] 오류 예측

## Dataset

- Techross DB ver.1.1 [보안문제로 인한 데이터베이스 공유 금지]
- [ ] DATA : PMU, TSU, ECU, ANU 요약치 제공
- [ ] DATA_DEVICE : DATA, OPTIME, PMU, TSU, ECU, ANU 테이블 간 상호 연결
- [ ] EVENT : 이벤트 메세지 기록
- [ ] OPTIME : 작동 내역 기록
- [ ] OPTIME_EVENT : OPTIME, EVENT 테이블 연결
- [ ] CITY : 도시 정보
- [ ] MESSAGE : 메세지, 에러 연결
- [ ] UNKNOWN_SHIP : 누락 내용 기록
- [ ] SHIP_INFO : 선박 정보
- [ ] PMU : 전력분배기
- [ ] TSU : TRO 농도
- [ ] ECU : 전해조 장치
- [ ] ANU : 중화제 투입 장치

## Modeling Techniques

- [ ] PCA : 차원 축소 시 이용
- [ ] DECISION TREE CLASSIFIER : 변수의 결과도출 과정 판별(ECU테이블의 CONTROL)

## File Structure

```{}
TECHLOSS_SIGNLAB
├── WAIT                    <- 작업중인 코드
├── DATA_JOIN               <- 데이터병합, 분할에 대한 모든 작업
├── DATA_BASIC_STAT         <- 데이터 정제에서 기초통계에 대한 모든 작업(BOXPLOT, SCATTERPLOT,...)
├── DATA_SEARCH             <- 데이터 써칭에 대한 모든 작업
└── DATA_MODELING           <- 데이터 모델링에 대한 모든 작업(PCA,...)
```

## Process

### 1. 데이터 베이스 정제

- [x] 이상치 탐지

- [x] 데이터 베이스 간 연관관계 파악

- [x] 데이터 베이스간 병합, 분할 여부 파악

- [ ] TODO: 차원 축소 여부 파악

- [ ] TODO : 시계열 데이터로의 전환

### 2. 학습 데이터 셋 구성

- [ ] TODO:

### 3. 모델링

- [ ] TODO: 

### 4. 특성 엔지니어링

- [ ] TODO: 

### 5. 평가 및 검증

- [ ] TODO: 
