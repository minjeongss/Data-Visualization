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

