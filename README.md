# 나의 공부 기록에 오신걸 환영합니다

캐글 데이터를 활용한 프로젝트를 저장하는 공간입니다.


# 1. Bike Sharning Demand : 자전거 수요 예측 프로젝트

- [최종 목표] test 데이터의 대여량(count) 값을 예측하자.
- 문제 : 회귀 / 평가지표 : RMSLE
- [캐글 자전거 수요 예측 컴퍼티션 바로가기](https://www.kaggle.com/competitions/bike-sharing-demand/overview)

1. EDA
- train data를 바탕으로 사용자들의 사용 패턴을 알아보았다.
- 수치형 변수, 범주형 변주에 따라 나눠 시각해았으며, target인 count와의 관계도 확인하였다
- 포스팅 연결하기

2. ML
- 데이터 전처리 : 이상값, 수치형변수 스케일링, target 변수 로그변환 등
- EDA 결과 반영해서 target이 casual일 때와 registered일 때로 나눠 예측했다.
- 첫 번째 모델 :   Linear Regression
- 두 번째 모델 : XGBRegressor
4. Test RMSLE




[표시할 내용] (링크)
[공공데이터 활용 분석 공부할 것](https://github.com/corazzon/open-data-analysis-basic)
