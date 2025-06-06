# 🍴 간편식 시장에서 살아남기 위한 간편식 소비 트렌드 분석


## 개요
- 주제
    - 간편식 소비 현황 및 트렌드 분석
- 배경
    - 간편성, 편리성을 지향하는 식품소비 트렌드는 지난 10년을 대표하는 트렌드로 자리잡음
    - 기존의 간편식 관련 선행 연구는 간편식 소비 동향을 파악하는데 그침
- 목표
    - 간편식 상품 기획 및 제조 시 고려해야할 사항들과 타겟 소비 집단 제시


## 데이터 설명
- 국가통계포털(KOSIS)에서 제공하는 공공데이터 활용
    - 간편식(HMR) 품목별 구입경험 및 구입변화(즉석조리식품, 즉석섭취식품, 신선편의식품) (2018-2020, 2021-2022): `shape (678, 44)`
    - 간편식(HMR) 구입 이유 (2018, 2019-2022): `shape (50, 24)`
    - 간편식(HMR)을 구입하지 않는 이유 (2021-2022): `shape (20, 24)`
    - 연도별 소비자물가 등락률 (2018-2022): `shape (5, 6)`
    - 성 및 거처의 종류별 1인가구 - 시군구 (2018-2022): `shape (5, 23)`, `shape (17, 6)`

- 사용 라이브러리
  - 전처리: `NumPy`, `Pandas`
  - 시각화: `Tableau`


[👉 자세한 내용 보러가기](https://www.notion.so/49d5555952e64bf591b21dbb3139d676)
