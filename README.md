# team3_semi_project
Jeonse price prediction

23.09.11(월)
### 김주성
- 오늘 한 일
  - Regression Analysis와 여러 Statistical Metrics를 적용하는 방법 분석
- 오늘 못 한 일
  - 머신러닝 알고리즘 적용 방법 분석
- 내일 할 일
  - 머신러닝 알고리즘 코드 구현
  - 통계 분석을 통한 features 순서 결정

### 이길연
- 오늘 한 일 : 데이터 타입 고려하여 상관관계 분석 수정, VIF제거하고 회귀분석 진행 → Residual 그래프 약간의 개선, 캐글이나 교재에서 통계분석 과정 확인
- 오늘 못 한 일 : 통계분석 과정 조금 더 확인하고
  1. 회귀분석에서 데이터 타입이나 단위의 범위에 따라 스케일링이나 인코딩이 어떻게 적용될지
  2. 변수 선택에 있어 VIF나 상관계수 등을 얼마나 고려할지와 추가적으로 고려할 건 없을지
  3. 잔차분석 결과 개선 필요 ⇒ 회귀분석 마무리
- 내일 할 일 : 통계분석 과정 조금 더 확인하고
  1. 회귀분석에서 데이터 타입이나 단위의 범위에 따라 스케일링이나 인코딩이 어떻게 적용될지
  2. 변수 선택에 있어 VIF나 상관계수 등을 얼마나 고려할지와 추가적으로 고려할 건 없을지 ⇒ 총체적으로 보면 30000건의 매물 거래 데이터와 12000건의 월별 종합 데이터를 프로젝트 진행하면서 어떻게 활용할 지 의논이 필요해보임.

### 최동원
- 오늘 한 일
  - 데이터 분할 정리
        - 교차 검증 모델 정리
  - 모델 선택 정리
  - 머신러닝 용어 정리
  - 딥러닝과 머신러닝을 이용한 아파트 실거래가 예측 논문 분석
- 오늘 못한일
  - 머신러닝 예측 과정 정리 완성
- 내일 할 일
  - 딥러닝과 머신러닝을 이용한 아파트 실거래가 예측 논문 분석
  - 모델 학습, 모델 평가, 모델 향상에 대해 추가 정리

### 최선재
  - 금일 : 데이터 시각화
    - Seaborn 라이브러리를 통해 Heatmap 그래프 그려서 상관계수 시각화
    - Scatter Plot을 활용한 전세가와 임대면적, 면적 당 매매가의 산포도 확인
    - box plot을 활용한 X축 범주형 데이터, Y축 전세 가격을 두어 변동 추이 확인
    - box plot을 활용한 X축 범주형 데이터, Y축 전세 가격을 두어 범주별 차이 확인
    - 시계열 데이터에서 시각화는 변화의 추이 또는 범주열 데이터의 순위를 파악하는 용도 사용되는 것 같음.
    - Heatmap 상관계수 그래프를 제외하고서는 머신러닝할 때 크게 유용하지 않는듯 함.
  - 차일 : Streamlit 대쉬보드 구상
    - 1일차 : Streamlit 사이드 바 및 배치 기획하기 API 라이브러리 체크하여 사용할 포맷 체크
    - 1일차 : 사이드바 및 시각화, 머신러닝 어떻게 배치할지 디자인하기(웹 반영)
    - 2일차 : Streamlit 시각화 및 머신러닝 연동 ( iris 강습내용 참고하여 )
    - 3일차 : Streamlit 시각화 및 머신러닝 연동 ( iris 강습내용 참고하여 )
  - 예상 : 1일차 기획 시간이 제일 오래 걸릴 것 같음.. 1-2일차로 합치고 3일차에 시각화 및 머신러닝 연동 해볼수도 ??
  - 오늘 못한 일 : 없음

### 최연우
  - 오늘 한일 :
    - matplotlib, seaborn 라이브러리를 통해 구별 ‘면적 당 매매 가격’,  ‘임대 면적 당 전세 가격’ 시각화 해보기
    - 프로젝트 통계 분석 과정 보고 공부하기
  - 오늘 못한 일 :
    - 데이터 시각화 완성하기
  - 내일 할일 :
    - 데이터 시각화 완성하기
    - Streamlit 에 지도 시각화 나타내보기
### 황신엽
- 오늘한 일:
    - 데이콘 아파트 매매가격 예측 프로젝트 코드 리뷰
    - 기존 전세 데이터 전처리 한것에 월별, 연도별 데이터 통합 진행
    - 통합한 파일 github data브랜치에 push 완료
- 오늘하지 못한 일:
    - 탐색적 데이터 분석(EDA)
- 내일 할 일
    - 탐색적 데이터 분석으로 통합된 데이터에서 인사이트 찾기
    - 다른 프로젝트 ppt 참고해서 구상하기
 
----------

23.09.12(화)
### 김주성
- 오늘 한 일: 
  - PCC, Mutual Info, LR, RF를 적용하여 가중치를 두고 각 features의 전체적인 순서를 결정
  - RF, LR, FNN을 이용하여 RMSE, MAPE 값을 확인하여 RF의 accuracy가 가장 높다고 확인
  - RF를 이용하여 JS_Price를 예측한 결과: 예측값 = 51635.31, 실제값 = 51672.92, Error: 0.07%
- 오늘 못 한 일:
  - 위치 데이터 계산과 주식 기법들 적용을 못 함
- 내일 할 일:
  - 1. 위치 데이터와 부동산과의 거리를 계산하여 통합 데이터에 병합하기
  - 2. 주식 가격 예측 기법들을 적용하기

### 이길연
- 오늘 한 일 :
  - 위치정보 데이터 전처리하여 월병합 데이터에 다시 병합
  - 표준화 함수와 인코딩 함수 만들어 데이터 전처리 진행
  - ANOVA와 범주형 데이터 인코딩으로 correlation_scipy마무리
  - regression analysis의 가정 중 정규성 확인하고 처리
  - 통계분석과 머신러닝에서 데이터 어떻게 처리할 지 → 다 병합하기보단 기존 월병합 데이터와 건축년도 데이터
  - 위도경도 데이터 따로 통계분석하고 결과를 머신러닝에 활용하기로 결정
- 오늘 못 한 일 :
  - 회귀분석의 등분산성/독립성 처리
- 내일 할 일 :
  - regression analysis결과에 노멀라이즈 처리
  - 건축년도 데이터가져와서 주성님 코드에서 실행
  - 회귀분석의 등분산성/독립성 처리

### 최동원
- 오늘 한일
    - Linear Regression을 사용하여 성능메트릭 측정
    - 딥러닝과 머신러닝을 이용한 아파트 실거래가 예측 논문 분석
- 오늘 못한일
    - Total_APT_for_Target_Features 데이터 XGBoost 사용하여 성능메트릭 측정
- 내일 할 일
    - Total_APT_for_Target_Features 데이터 XGBoost 사용하여 성능메트릭 측정
    - 
### 최선재
- 금일 : 스트림릿 레이아웃 작업 및 대시보드 구상안 기획
    - 스트림릿 배포 사이트 로고 찾기 및 스트림릿의 API 레퍼런스 탐색
- 차일 : 스트림릿에 데이터 불러오기 → 대쉬보드 형성, 시각화 연동
- 못한일 : 데이터 불러오기 및 대쉬보드 구상안 미흡

### 최연우
- 오늘 한일 :
    - streamlit documation API reference 보고 streamlit 구상해보기
    - streamlit 배포해보기
    - streamlit 한글 폰트 깨짐 해결해보기
    - streamlit 지도 시각화 나타내보기
- 오늘 하지 못한 일 :
    - EDA
- 내일 할 일 :
    - streamlit 에러 사항 해결해보기
    - EDA
### 황신엽
- 오늘 한 일:
  - ppt 대략적인 구상 완료(데이터 수집, 데이터 전처리 슬라이드 추가)
  - 전세 데이터 전처리 2023년 자료 추가, 건물연수 컬럼 생성
  - 기존 연구 참고하여 수집한 데이터 적절성 확인
- 오늘 못한 일:
  - 탐색적 데이터 분석
  - 위도, 경도 추가(카카오, 네이버 활용)
- 내일 할 일:
  - 탐색적 데이터 분석
  - 위도, 경도 추가(카카오, 네이버 활용)
  - ppt 데이터 전처리 슬라이드 채우기(어떤 단계를 걸쳤는지, 결측치 처리 방식)

-----
23.09.13(수)
### 김주성
- 오늘 한 일: 통계 분석을 통한 features의 중요도를 결정하고 p-value와 regression analysis를 전세가격 예측에 대한 유효성 확인
- 오늘 못한 일: 새로운 자료(좌표 데이터)에 대한 전처리 작업
- 내일 할 일: 전체적으로 머신러닝 모델링을 구현하고 수치를 확인하여 모델 선택하기
  
### 이길연
- 오늘한 일:
  - apt, officetel, townhouse 데이터에 대해 상관분석 진행
  - apt 데이터에 대해 회귀분석 진행
  - 정규성을 만족시키기 위해 극단값제거, 종속변수 로그변환 하여 어느정도 정규화 진행했으나 이로 인해 선형성이 안 좋아짐…
- 오늘 못한 일:
  - 등분산성, 선형성은 어떻게 개선해야 할지…
- 내일 할 일:
  - 등분산성, 선형성 개선 방법 질문
  
### 최동원
- 오늘 한 일
  - Linear Regression Model, Deep Learning Model, LightGBM Model, XGBoost Model, Random Forest Model 성능 예측
- 오늘 못한 일
  - 각 모델의 하이퍼파라미터 튜닝
- 내일 할 일(여기 중 최대한 빠르게 해결)
  - 각 모델 평가(Cross-Validation)
    1. RandomForest
    2. Linear Regression
    3. XGBoost
    4. LightGBM
     
### 최선재
- 금일 : 시각화 함수 코딩 및 mpl 한글폰트 적용, 레이아웃 수정
- 차일 : 한글폰트를 기본폰트로 변경 및 시각화 함수 추가
- 못한일 : 한글폰트 기본폰트로 변경( 함수파일, 메인파일 두개로 나눠서 관리하다보니 설정이 조금 꼬이는듯??)
    
### 최연우
- 오늘 한 일 :
  - streamlit 예시 코드 살펴보기
  - streamlit 함수 구현
  - streamlit 한글폰트 깨짐 해결
- 오늘 못 한 일 :
  - EDA
- 내일 할 일 :
  - streamlit 에 지도시각화 부분 어떻게 구상할지 생각해보기
  - EDA 공부하고 우리 프로젝트에 실행해보기
    
### 황신엽(끝)
- 오늘한 일:
  - 데이터 전처리(매매가격 평균을 구하여 위도,경도 전처리한 데이터에 병합)
  - ppt 구상(데이터 전처리 슬라이드 내용 구상 완료)
  - 데이콘 EDA 코드 리뷰
- 오늘 못한 일:
  - EDA 실행
- 내일 할 일:
  - 다른 프로젝트 EDA 리뷰
  - ppt 데이터 전처리 슬라이드 작성 및 통계 분석 슬라이드 구상
  - EDA 실행

-----
23.09.14(목)
### 김주성
- 오늘 한 일: 
  - 전체적인 데이터 오류 체크
  - 좌표를 활용한 각 부동산 위치로부터 각 위치(e.g. 지하철)까지의 최단거리 추출
  - 데이터 전처리 후 5000개의 샘플 추출 완료
    
- 오늘 못 한 일: 
  - ML Validation
  - Hyperparameter tuning
- 내일 할 일: 
  - Validation과 Tuning 수행
  - Prophet, LSTM으로 예측 수행
  - 최종적인 모델 선택

### 이길연
- 오늘 한 일 :
  - 지하철역, 학교에 대한 위치데이터가 업데이트 된 데이터 기반으로 상관분석, 회귀분석 진행
  - 범주형 데이터 타겟인코딩하여 상관분석, 회귀분석 진행
  - 강사님과 상담하며 회귀분석의 가정을 만족시키기 위해 데이터를 지역별로 나누거나 z값을 기준으로 극단치를 나눠 모델을 여러개 만들어 회귀분석 진행해 봄. 선형성과 등분산성은 어느정도 해결됨.
- 오늘 못 한 일 :
  - 회귀분석 모델의 정규성 해결이 필요
- 내일 할 일:
  - 정규성 해결을 위해 → EDA, 데이터 비모수적 구별필요, 데이터 분할을 좀 더 상세하게 진행해보기.

### 최동원
- 오늘 한 일
  - 모델 평가 함수 만들기
  - 랜덤 포레스트 하이퍼파라미터 튜닝(**GridSearchCV, RandomizedSearchCV)**
  - Prophet 조사
- 오늘 못 한 일
  - CatBoost 모델 학습
  - 내일 할 일
    - 교차검증 수행
    - 최종 모델 선택
    - CatBoost, Prophet 모델 학습

### 최선재
- 금일 : 한글폰트를 기본폰트로 설정완료, 스트림릿 페이지 설정완료, 스트림릿 데이터 처리 각 담당 업무분장 토론 및 시각화 구현(셀렉 박스 옵션값 대로 시각화 구현)
- 차일 : 시각화 방법 및 함수화 디테일화 및 스트림릿 디테일 챙기기
- 못한일 : 시각화 방법 및 함수화 디테일화 및 스트림릿 디테일 챙기기
    
### 최연우
- 오늘 한 일 :
  - EDA, 데이터 시각화 코드 리뷰하며 공부하기
  - 우리 프로젝트 csv파일에 EDA, 데이터 시각화 실행해보기
- 오늘 못 한 일 :
  - streamlit 에 지도시각화 부분 어떻게 구상할지 생각해보기
    
### 황신엽
- 오늘 한 일:
  - 데이터 전처리: 전세수급동향, 인구수, 매매 가격 최신 반영
  - EDA: 결측치 시각화, 분포 시각화, 히트맵 시각화 진행
- 오늘 못한 일:
  - EDA: 산점도, 박스 플롯 시각화
    - ppt: 데이터 전처리 슬라이드
- 내일 할 일:
  - ppt: 데이터 전처리 슬라이드 작성, 통계 분석 내용 학습
  - EDA: 산점, 박스 플롯 시각화 진행 및 추가 여부 논의 후 진행

-----
23.09.15(금)
### 김주성
- 오늘 한 일:
  - Meta에서 개발한 Prophet tool을 이용하여 부동산 전세 가격의 그래프로 구현
- 오늘 못 한 일:
  - 전체적인 알고리즘을 모두 구현하여 모델들을 비교하지 못함
- 내일 할 일:
  - 알고리즘 모델들을 비교하여 최종적으로 선택 후 모델 평가하기
    
### 이길연
- 오늘 한 일 :
  - 변수선택법 정리하여 코드화(회귀계수의 p-value값과 vif고려하는 선택법)
  - 다중선형회귀분석모델의 4가지 가정을 체크하기 위해 잔차분석을 한다는 정보 파악
  - 정규성과 등분산성의 해결을 위해 가중치행렬 이용한 WLS모델활용, 변수선택법을 Stepwise로 진행 등 여러가지 시도해보았으나 실패
- 오늘 못 한 일 :
  - 잔차분석에서 정규성과 등분산성을 잡기 위해서 잔차를 변환하라고 나오는 경우가 많은데 잔차를 변환해서 정규성과 등분산성을 만족한다해도 원본데이터는 그대로이기 때문에 다중선형회귀모델을 개선하는 데 도움이 되는지 의문
- 내일 할 일 :
  - 잔차를 변환해서 정규성과 등분산성을 만족하는 것이 그냥 단순히 가정을 만족하기 위함인지 다중선형회귀모델 개선에 직접적으로 영향이 있는건지 찾아봐야 함.
        
### 최동원
- 오늘 한일
  - RandomForest, XGBoost, LightGBM 교차검증 코드, 하이퍼파라미터 튜닝 코드 작성
  - 이상치 처리 방법 탐색
- 오늘 못한일
  - 이상치 처리
- 내일 할 일
  - 각 머신러닝 모델의 교차검증, 하이퍼파라미터 튜닝의 성능 확인
    
### 최선재
- 금일 :
  - 시각화 관련 사이트 및 자료 수집
- 못한일 :
  - 시각화 활용
- 차일 :
  - 시각화 및 맵 구현
    
### 최연우
- 오늘 한 일 :
  - streamlit 에 지도 시각화 부분 어떻게 구상할지 생각해보기
  - Folium 라이브러리 활용하여 위치 간의 직선, 거리, 원 그리기
  - Folium 라이브러리 활용하여 지도 클릭 시, 위도와 경도가 바로 나타내도록 표현 → streamlit 배포 완료
  - Folium 라이브러리 활용하여 특정 위치에 가까운 지하철, 공원, 초중고등학교, 대학교 나타내기 → 계속 오류 발생
- 오늘 못 한 일 :
  - EDA 마저 끝내기
- 내일 할 일 :
  - Folium 라이브러리 활용하여 특정 위치에 가까운 지하철, 공원, 초중고등학교, 대학교 나타내기

### 황신엽
- 오늘한 일:
  - 탐색적 데이터 분석 코드 리뷰 및 실행
  - 데이터 전처리 슬라이드 초안 작성 완료
  - 통계 분석 관련 이론 학습
- 오늘 못한 일:
  - 탐색적 데이터 분석 완료
- 내일 할 일:
  - 탐색적 데이터 분석 완성
  - 데이터 전처리 슬라이드 작성 완료
  - 탐색적 데이터 분석 슬라이드 초안 작성
  - 통계 분석 ppt 구상

-----
23.09.18(월)
### 김주성
- 오늘 한 일:
  - ANN, LSTM 알고리즘을 돌리면서 결과를 도출하고 RF, LightGBM, XGBoost와의 결과값 비교
  - LightGBM이 속도가 빠르고 XGBoost는 속도가 느리지만 성능이 약간 더 좋음
  - ANN과 LSTM에 대해서 속도는 비슷했지만 LSTM의 성능이 더 좋았음.
- 오늘 못 한 일:
  - 데이터가 APT, Officetel, Townhouse로 분리되어 모델 평가가 진행되었으므로 아직 복합적으로 완전한 비교가 이루어지지 못함
- 내일 할 일:
  - 전체적인 알고리즘들의 성능 비교를 통해 모델을 선택하고 학습시키기
  - APT 데이터의 크기를 확장하고, 두 알고리즘을 합쳐서 모델을 생성하는 Ensemble 기법에 대해 확인하기
    
### 이길연
- 오늘 한 일
  - pingouin 라이브러리로 outlier데이터에 대해 상관분석, 선형회귀, Post-hoc tests 진행해봄
  - before Encoded 5000.csv를 범주형 데이터 3가지인 YearMonth는 datetime으로 RegionName은 미정, BuildingUse는 제거하여 공통 데이터로 진행
  - Features_Ranking에서 하위 7가지 변수를 Logistic Regression, VIF로 필터링하여 머신러닝에 넣을 변수 선정 완료
- 오늘 못 한 일
  - Post-hoc tests는 구현하지 못 함
  - Logistic Regression 과적합 체크 및 해결
- 내일 할 일
  - Features_Ranking에 쓰인 알고리즘들이 RegionName을 인코딩해야하는지 범주형으로 해도되는지 체크
  - Logistic Regression 과적합 체크 및 해결
  - RegionName 타겟인코딩할지 그냥 범주형으로 할지(서칭해보고 Logistic Regression에서 데이터 타입만 바꿔서 돌려봐도 될 듯)

### 최동원
- 오늘 한일
  - RandomForest모델 RandomizedSearchCV 하이퍼파라미터 튜닝
  - XGBoost모델 RandomizedSearchCV 하이퍼파라미터 튜닝
  - LightGBM모델 RandomizedSearchCV 하이퍼파라미터 튜닝
- 오늘 못한일
  - RandomForest 하이퍼파라미터 튜닝
  - XGBoost 하이퍼파라미터 튜닝
- 내일 할 일
  - 가장 성능 좋은 모델 선택 후 성능 개선

### 최선재
- 오늘할일
  - EDA 관련 시각화 코드 함수화 해서 스트림릿 연동
  - 그동안 시각화 한 것 스트림릿 연동
- 내일할일
  - 스트림릿 서비스 구현 PPT 프로토 타입 작성
- 못한일 :
  - 나머지 시각화 연동 및 인프라 지도 탭 연동 → 셀렉박스로 바꿈

### 최연우
- 오늘 한 일 :
  - EDA 관련 코드들 리뷰하며 우리 프로젝트에 직접 진행하기
  - 서울시 지하철 노선도 역 주소 데이터 다시 찾아서 전처리 진행
  - 서울시 지하철 노선도 역 주소 데이터를 활용해 위도, 경도 나타내기
- 오늘 못한 일 :
  - Folium 라이브러리 활용하여 특정 위치에 가까운 지하철, 공원, 초중고등학교, 대학교 나타내기 → 계속 오류 발생
- 내일 할 일 :
  - EDA 정리하기
  - Folium 오류 해결책 찾아서 계속 해결해보기
  
### 황신엽
- 오늘 한 일:
  - 탐색적 데이터 분석 완료
  - 데이터 전처리 슬라이드 작성 완료
  - 통계 분석 코드 리뷰
- 오늘 못한 일:
  - 탐색적 데이터 분석 슬라이드 초안 작성
- 내일 할 일:
  - EDA 슬라이드 작성
  - 통계 분석 리뷰 및 슬라이드 초안 작성
  - 머신러닝, 딥러닝 코드 리뷰

-----
23.09.19(화)
### 김주성
- 오늘 한 일:
  - LightGBM, XGBoost, RandomForest, ANN, LSTM의 성능을 확인해보고 최종적으로 LightGBM과 LSTM의 비교하기 위해 코드를 수정함
- 오늘 못 한 일:
  - LightGBM은 결과가 나왔지만, LSTM은 현재 코드 작동 중이라 결정하지 못함
- 내일 할 일:
  - LSTM 결과 확인 후에 모델을 결정하고, 팀원들과 Streamlit 구현을 시작하기
    
### 이길연
- 오늘 한 일
  - 범주형 데이터 어떻게 처리할 지 계속 서치
  - 서울시정개발연구원 보고서 고려하여 Region_Name을 9개로 묶은 상태로 원핫인코딩 진행해보았으나 유의미한 결과 X
  - 타겟인코딩으로 진행
  - target encoding에서의 data leakage를 피하기 위해 코드 수정
  - Logistic Regression 과적합 체크
- 오늘 못 한 일
  - 코드 수정한 효과 확인
  - Logistic Regression 과적합 체크했으나 그래프가 애매해 좀 더 세세한 확인 필요
- 내일 할 일
  - data leakage가 방지되었는지 확인, 안 되었으면 Cross Validation도 적용 고려
  - Logistic Regression 과적합 체크 및 해결
        
### 최동원
- 오늘 한일
  - Streamlit에서 ML파트 정리
  - LightGBM 시각화 진행
- 오늘 못한일
  - LightGBM 시각화
  - XGBoost 하이퍼파라미터 튜닝
- 내일 할 일
  - XGBoost 하이퍼파라미터 튜닝
        
### 최선재
- 오늘한 일 :
  - 나머지 시각화 연동 및 PPT 스트림릿 대쉬보드 구상안 프로토 타입 작성
- 내일할 일 :
  - 위 내용 보충 및 스트림릿 보완 사항 생각하기 ⇒⇒⇒ PPT 도식화 양식 작성
- 못한 일 :
  - 스트림릿 대쉬보드 도식화(최종 전처리(변수설정) 및 최종 모델선정 필요)
    
### 최연우
- 오늘 한 일 :
  - EDA 정리 완료. 수치 요약과 시각화를 사용하여 데이터를 탐색하고 변수 간 잠재적 관계를 나타냄
  - Folium 라이브러리 활용하여 특정 위치에 가까운 지하철, 공원, 초중고등학교, 대학교 나타내기 → 계속 오류 발생
- 오늘 못한 일 :
  - Folium 라이브러리의 Circle 함수는 location을 바꿨을 때, 그려지지 않음. 이로 인해 계속된 오류가 발생한 것임.
- 내일 할 일 :
  - Folium 오류 해결책 찾아서 계속 해결해보기
        
### 황신엽
- 오늘 한 일:
  - 데이터 전처리 슬라이드 수정
  - 탐색적 데이터 분석 완료
  - 탐색적 데이터 분석 슬라이드 구상
  - 머신러닝, 딥러닝 코드 리뷰
- 오늘 못 한 일:
  - 통계분석 슬라이드 초안 작성
  - 탐색적 데이터 분석 슬라이드 초안 작성
- 내일 할 일:
  - 탐색적 데이터 분석 슬라이드 초안 작성
  - 통계분석 슬라이드 초안 작성
  - 머신러닝, 딥러닝 코드 리뷰

-----
23.09.20(수)
### 김주성
- 오늘 한 일:
  - 각 알고리즘들에 대한 평가 지표를 엑셀 파일로 정리하고 최종 선택된 LightGBM의 코드를 수정
- 오늘 못 한 일:
  - Streamlit 구현 중에 몇 가지 독립변수들을 사용자 편의를 위해 미리 입력시키는 함수를 구현하는 작업
- 내일 할 일:
  - Streamlit에 함수를 적용하여 구현하고, 테스트한 알고리즘들에 대한 설명을 PPT에 작성
    
### 이길연
- 오늘 한 일
  - data leakage 방지를 위해 StandardScaler 관련해 데이터 전처리 다시 하여 Logistic_analysis_final코드 진행
  - Logistic_analysis_final을 바탕으로 내용 정리
  - Logistic_analysis_final과 별개로 pipeline으로 코드 재구축 보다 안정적인 결과 도출, 이미 프로젝트가 어느 정도 진행되어 시간 부족으로 다음 프로젝트 때부터 pipeline 활용
- 내일 할 일
  - 정리한 내용 바탕으로 ppt 작성
  - 다른 프로젝트 참고하여 통계분석 좀 더 작성할 내용 없을지 파악
  - regression analysis 실패한 부분을 ppt에 올려야 할지, 한계점으로 적어야 할지
      
### 최동원
- 오늘 한일
  - LightGBM 하이퍼파라미터 튜닝
  - XGBoost 모델 학습
- 오늘 못한일
  - 최적의 하이퍼파라미터 탐색
- 내일 할 일
  - LightGBM 최적의 하이퍼파라미터 탐색
  - 머신러닝, 딥러닝 PPT 작성
        
### 최선재
- 금일 한 일 :
  - 모델 평가 및 모델 스트림릿 연동 준비
- 내일 할 일 :
  - 상동
- 다 못한 일 :
  - 상동 ( 입력한 주소 값으로 최단거리 계산 )
    
### 최연우
- 오늘 한 일 :
  - Folium 라이브러리 활용하여 특정 위치에 가까운 지하철, 공원, 초중고등학교, 대학교 나타내기 → 주소를 입력하였을 때, 그 주소를 중심으로 가까운 인프라를 설정하는 것으로 변경
  - 시각화 코드 찾아보면서 공부
  - 스트림릿 코드 리뷰
- 오늘 못한 일 :
  - PPT 에 들어갈 시각화 생각해보기
- 내일 할 일 :
  - PPT 에 들어갈 시각화 생각해보기

### 황신엽
- 오늘 한 일:
  - 탐색적 데이터 분석 슬라이드 초안 작성
  - 탐색적 데이터 분석 내용에 알맞게 다시 데이터 전처리
  - 머신러닝, 딥러닝 코드 리뷰
- 오늘 못 한 일:
  - 통계분석 슬라이드 초안 작성
- 내일 할 일:
  - 통계분석 슬라이드 초안 작성
  - 탐색적 데이터 분석 슬라이드 완성
     
-----
23.09.21(목)
### 김주성
- 오늘 한 일:
  - 층수 칼럼을 추가하고 결측치 처리를 위해 KNN, RF, LGBM, XGB를 활용하여 각각의 변경값을 확인함
- 오늘 못 한 일:
  - 전세가격 예측을 위해 LightGBM 모델을 생성하기 위한 데이터를 아직 처리 중임
- 내일 할 일:
  - LightGBM 모델을 생성하고 저장하여 Streamlit에 적용
    
### 이길연
- 오늘 한 일
  - ppt 통계분석 파트 :  모델의 진단과 성능 부분 / 데이터에 대해 다중 로지스틱 회귀분석을 통한 통계량으로 나누어서 기재하기로 결정
  - ppt에 넣을 내용 정리를 위해 코드 수정
  - regression analysis 실패한 부분 한계점으로 ppt에 올리기로 결정
- 내일 할 일
  - 수정하여 도출한 엑셀 파일이나 그래프를 정리하여 ppt에 올리고 보기좋게 하기
        
### 최동원
- 오늘 한일
  - LightGBM 최적의 하이퍼파라미터 탐색
  - 머신러닝, 딥러닝 PPT 작성
- 오늘 못한일
  - LightGBM 세팅값 수정
- 내일 할 일
  - LightGBM 세팅값 수정
  - 머신러닝, 딥러닝 PPT 작성

### 최선재
- 오늘한 일 :
  - 머신러닝 모델 스트림릿 연동
- 내일할 일 :
  - 입력 주소를 기반으로 위도 경도, 자치구 받아오는 api 변경 ( 받아오는 정보 한계 )
- 못했던 일 :
  - 내일할 일과 상동
    
### 최연우
- 오늘 한 일 :
  - 시각화 공부 하기
  - 통계분석 코드 리뷰
  - 머신러닝 / 딥러닝 코드 리뷰
    
### 황신엽
- 오늘 한 일:
  - 통계분석 슬라이드 초안 작성
- 오늘 못 한 일:
  - 탐색적 데이터 분석 슬라이드 완성
- 내일 할 일:
  - 탐색적 데이터 분석 슬라이드 완성

-----
23.09.22(금)
### 김주성
- 오늘 한 일:
  - 층수 칼럼을 추가하여 데이터 전처리 완료, Feature Ranking 파트 PPT 작성, 머신러닝 알고리즘 정리
- 오늘 못 한 일:
  - Streamlit 구현 작업을 못함
- 내일 할 일:
  - Streamlit 구현 작업을 팀원과 수행
    
### 이길연
- 오늘 한 일
  - ppt에 내용 기재하고 다듬기
  - 중간중간 용어가 불명확한 부분들(통계량이 어떤 통계량인지 등) 수정
- 내일 할 일
  - 피드백 받아서 내용 수정하기

### 최동원
- 오늘 한일
  - PPT 딥러닝, 머신러닝 파트 작성
- 오늘 못 한 일
  - PPT 딥러닝, 머신러닝 정리
- 내일 할 일
  - PPT 딥러닝, 머신러닝 마무리

### 최선재
- 오늘 한 일 :
  - 코드 직관적으로 정리 및 대쉬보드 구상안 계획
- 내일 할 일 :
  - 코드 직관적으로 정리 및 대쉬보드 구상안 계획, 대쉬보드 도식화
- 못다 한 일 :
  - 대쉬보드 도식화
    
### 최연우
- 오늘 한 일 :
  - 다시 데이터 전처리 된 파일 EDA 진행하기
  - ppt 에 들어갈 시각화 한 눈에 잘 들어오게 다시 그리기
- 내일 할 일 :
  - 피드백 받고 PPT에 넣기
        
### 황신엽
- 오늘 할일:
  - EDA 슬라이드 작성
  - EDA 수행 및 인사이트 찾기
- 오늘 못한 일:
  - ppt 작성 완료
- 내일 할일:
  - ppt 피드백 내용대로 수정하기

-----
23.09.25(월)
### 김주성
### 이길연
- 오늘 한 일
  - ppt 최종 피드백 및 디자인 변경
### 최동원
- 오늘 한 일
  - PPT 머신러닝, 딥러닝 파트 작성
- 오늘 못 한 일
  - 
- 내일 할 일
  - 프로젝트 마무리
### 최선재
- 오늘 한 일 :
  - 스트림릿 최종 배포 준비 및 내용 다듬기
- 못다 한 일 :
  - 스트림릿 최종 배포 준비(XGBoost 활용한 예측값 연동)
- 이따 할 일 :
  - 못다한 일 연동하기
    
### 최연우
- 오늘 한 일
  - 지도 시각화 추가로 넣기
  - PPT 최종 피드백 및 디자인 변경
        
### 황신엽
- 오늘 한 일
  - 데이터 전처리 슬라이드 수정
  - 부록 작성
  - ppt 전반적으로 검토
- 내일 할 일
  - ppt 검토 및 오류 수정
