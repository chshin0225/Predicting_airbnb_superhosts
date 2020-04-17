# AirBnB 데이터를 이용한 Superhost 예측하기

## 1. 프로젝트 소개

- AirBnB Superhost badge를 얻는 것은 호스트의 profit과 직결
- 현재 Airbnb의 superhost 선정기준은 host 중심이 아닌 guest 중심 (review와 숙박 일수는 guest에 의해 결정되는 요인이다). 따라서 새로운 host들은 superhost가 아니기 때문에 guest에게 선택될 확률이 낮음(high barrier to entry). Host가 superhost가 되기 위해서 무엇을 해야하는지 **host 중심적인 기준의 필요성!**
- **문제 제기**
  - 신생 Host가 Superhost가 되기 위해서는 어떻게 해야할까?
  - Superhost가 되기 위한 최적의 조건은 무엇인가?



## 2. 데이터 출처 및 설명 

- http://insideairbnb.com/get-the-data.html
- 2019 기준으로 홍콩에 있는 에어비엔비 리스팅 데이터를 사용
- 각 리스팅의 위치, 침실 수, 화장실 수, 가격, 예약 가능 기간 등과 같은 데이터와 함께 호스트가 슈퍼호스트인지의 여부가 담겨있음



## 3. 사용한 학습법

- `DecisionTreeClassifier`를 이용한 분류 모델링을 통해 주어진 데이터로 호스트가 슈퍼호스트인지 아닌지 예측
- **자세한 내용과 결과는 코드와 발표 자료 참고**





