## 애니메이션 데이터와 사용자 평점 데이터를 활용한 애니메이션 추천 모델
### 프로젝트 설명
이 데이터 세트에는 캐글의 데이터로 12,294개 애니메이션에 대한 73,516명의 사용자 선호도 데이터에 대한 정보가 포함되어 있습니다. 이 데이터 사용하여 데이터 세트에 있는 사용자가 입력한 애니메이션와 유사한 애니메니션을 추천해주는 모델을 만들었습니다.
- (1) Data
  - 애니메이션 정보 데이터 (anime.csv)
    - 애니메이션 ID, 이름, 장르, 타입(TV, 영화 등), 에피소드 수, 평점, 회원 수 포함

  - 사용자 평점 데이터 (rating.csv)
    - 사용자 ID, 애니메이션 ID, 평점 정보 포함

- (2) Data Preprocessing
  - 평점 데이터에서 -1(미평가) 데이터를 제거
  - 애니메이션 데이터에서 결측값 처리 및 유의미한 변수 선정
  - type와 genre 데이터를 다중 분류 형태로 변환하여 분석에 활용 가능하도록 전처리

- (3) Data Analysis
  - 애니메이션 평점 및 장르별 분포 분석
  - 사용자 선호 장르 및 평점 분포 파악
  - 협업 필터링 및 콘텐츠 기반 추천 시스템을 활용한 애니메이션 추천 모델 구축
  - Full Matrix 구조 
  
- (4) Report
  - 사용자 입력 기반 추천 결과 제시
  - SVD 기반 모델 생성

- (5) Review
  - 데이터 기반 추천 시스템 개발 경험을 통해 데이터 분석 및 모델링 역량 강화
  - 협업 필터링 및 콘텐츠 기반 추천 모델의 장단점 비교 및 개선 방향 모색
  - Full Maxtrix 메모리 차지에 대한 대처방안 모색
  - 추후 애니메이션 한글 이름을 추가하여 웹에서 추천을 할 수 있도록 서비스 제공

- 참고 사이트
[블로그 바로가기](https://blog.naver.com/khjkhj2804/223750358335)
