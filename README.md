## 데이터 시각화 📊
### 📚 교재

: 태블로 굿모닝 굿애프터눈 (강승일,송재환) 
<br><br>

### PART 01: 태블로 굿모닝 🌞

#### 📌 CHAPTER 01: 태블로란?

- 태블로란 무엇인가?

  : 데이터 분석 및 시각화하는 Business Intelligence(BI) 솔루션

- 태블로 제품 소개

  (1) Tableau Public

  (2) 학생용 Tableau

  (3) 그 외

#### 📌 CHAPTER 02: 태블로 시작하기

- Tableau 파일 유형

  (1) **twb**(통합 문서) : 파일 크기 작음/데이터 원본 포함X

  (2) **twbx**(패키지 통합 문서) : 파일 크기 큼/데이터 원본 포함O 👉🏻 패키지 해제 > 'twb/데이터 원본'으로 분리

  (3) 그 외 : hyper/tde(추출), tds(데이터 원본), tdsx(패키지 데이터 원본)

- 작업영역

- 데이터 패널

- Tableau 기본 개념 1 - 차원 vs 측정값

  (1) **차원**: 정성적인 값 → 만들어진 차트를 어떻게 나눠서 볼 것인가를 결정

  (2) **측정값**: 정량적인 값 → 측정할 수 있는 값이기에 집계를 통해 차트를 만든다!

- Tableau 기본 개념 2 - 연속형 vs 불연속형
  
  (1) 연속형 : 초록색 필드/무대한 범위
  
  (2) 불연속형: 파란색 필드/유한한 범위

#### 📌 CHAPTER 03: 기본 차트 만들기

> (Num) : Num은 책에 정렬된 기준을 바탕으로 함

- **기초적인 차트 만들기**

  (1) 막대 차트

  (2) 라인 차트

  (3) 파이 차트

  (6) 분산형 차트

  (7) 트리맵 차트

  (8) 하이라이트 테이블

  (11) 간트 차트

  (12) 히스토그램

  (15) 라운드형 막대 차트

  (17) 워드 클라우드

  (18) 캘린더 차트

- **영역 구별하는 차트 만들기**

  (4) 도넛 차트

  (9) 영역 차트

  (10) 누적 막대 차트

- **지도** 🌍

  (21) 지리적 역할 부여

  (22) 채워진 맵

  (23) 기호 맵

  (24) 밀도 맵

  (25) 이중 축 맵(면+기호)

- **활용**

  (5) 임시 계산 : 직접 계산 입력하는 방법

  (13) 이중 축(Dual axis)

  (14) 결합된 축(Combined axis)

  (16) 평균 라인

  (19) 총계

  (20) 계층

  (26) 그룹과 집합 차이

  (27) 데이터 설명

<br>

### PART 02: 태블로 굿애프터눈 1 🌝

#### 📌 CHAPTER 01: 퀵 테이블 계산 만들기

- 퀵 테이블 계산 종류

  (1) 누계(Running Total)

  (2) 차이

  (3) 비율 차이

  (4) 구성 비율(Percent of Total)

  (5) 순위

  (6) 백분위수(Percentile)

  (7) 이동 평균(Moving Average)

  (8) YTD 총계

  (9) 통합 성장률(Compound Growth Rate)

  (10) 전년 대비 성장률

  (11) YTD 성장률

- 적용 - 전월 대비 및 전년 대비 성장률

#### 📌 CHAPTER 02: 계산된 필드 만들기

- 집계 계산식 만들기

- IF로 계산된 필드 만들기

  > 필드명: `매출 200 구분`
  >
  > ** 표현 방식에 대한 차이에 주목 ** 

  (1) IF

  ```python
  IF SUM([매출]) >= 200 THEN "200 이상 매출"
  ELSE "200 미만 매출"
  END
  ```

  (2) IIF

  ```python
  IIF(SUM([매출])>=200,"200 이상 매출","200미만 매출")
  ```

  (3) T/F

  ```
  SUM([매출]) > 200
  ```

#### 📌 CHAPTER 03: 매개 변수 만들기

#### 📌 CHAPTER 04: 대시보드 액션 적용하기

