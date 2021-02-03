# Inbound Tourist Prediction
한국관광공사에서 제공한 일별 내한 외국인 통계를 활용한 딥러닝 기반 예측알고리즘입니다.

## Setup
파이썬3이 설치되어있어야합니다.

패키지 dependency를 설치합니다. 패키지 설치에 시간이 다소 소요될 수 있습니다.
```
pip install -r requirement.txt
```
제공하고있는 테스트 프로그램을 실행합니다.

## data
사용한 data가 들어있는 폴더입니다.

### tourist_daily.csv
tourist_daily.csv에 있는 값들은 다음과 같습니다.

Date : 날짜
Total_entry : 일별 총 입국자 수
China : 일별 중국 입국자 수
Japan : 일별 일본 입국자 수
US : 일별 미국 입국자 수
China_exchange_rate : 중국 환율
Japan_exchange_rate : 일본 환율
USA_exchange_rate : 미국 환율
KOSPI : 코스피 지수
Oil_price : 원유 가격
China_GDP : 중국 GDP(연간)
Japan_GDP : 일본 GDP(연간)
USA_GDP : 미국 GDP(연간)
apple_driving : 애플 이동성 트렌드(운전)
apple_walking : 애플 이동성 트렌드(보행)
retail_and_recreation :구글 이동성 트렌드(소매점 및 여가시설)
grocery_and_pharmacy : 구글 이동성 트렌드(식료품점, 약국)
parks : 구글 이동성 트렌드(공원)
transit_station : 구글 이동성 트렌드(대중교통 정거장)
workplace : 구글 이동성 트렌드(직장)
residential : 구글 이동성 트렌드(주거지)
seoul_hotel: 구글 트렌드 '서울 호텔'
incheon_airport: 구글 트렌드 '인천 국제공항'
myeongdong: 구글 트렌드 '명동'
korea_tour: 구글 트렌드 '한국 관광'
seoul: 구글 트렌드 '서울'
incheon: 구글 트렌드 '인천'
busan: 구글 트렌드 '부산'
suwon: 구글 트렌드 '수원'
jeju: 구글 트렌드 '제주'
disease: 질병 더미변수
season: 계절 더미변수 
politics: 정치 더미변수