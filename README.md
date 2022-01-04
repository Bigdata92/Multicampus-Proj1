# 빅데이터 지능형서비스 개발과정 팀프로젝트(1)

## 삼성 멀티캠퍼스, 서울

### 기간 : 21. 10. 19(화) ~ 10. 28(목)

**세부일정** 

| 단계 |                     활동                     |       수행기간        |
| :--: | :------------------------------------------: | :-------------------: |
| 기획 |       주제 정하기 / 아이디어 자료 찾기       | 10/19(화) ~ 10/20(수) |
| 분석 |     데이터 전처리 / EDA / 데이터 시각화      | 10/21(목) ~ 10/23(토) |
| 학습 |               CNN / 객체 인식                | 10/24(일) ~ 10/25(월) |
| 구현 | EfficientNetB0 / Vision Transformer / 앙상블 | 10/25(월) ~ 10/27(수) |
| 종료 |            PPT / 발표준비 / 발표             | 10/27(수) ~ 10/28(목) |

**팀이름 : 백견불여일조**

**프로젝트 역할**(공동 작업파트 : 주제선정 / 데이터 수집(자료조사 등) / 데이터 전처리 / PPT)

| 팀원   |                     역할                     |
| ------ | :------------------------------------------: |
| 고준수 |           이미지 전처리 / CNN 모델           |
| 구자호 | 이미지 분류 / 객체 검출 / 함수 작성 및 통합  |
| 류동훈 | 전이학습(ViT모델) / YOLO / 중복제거(ImgHash) |
| 송지섭 |      전이학습 / 앙상블 / 이미지 전처리       |
| 장근영 |            이미지 / 크롤링 / EDA             |
| 홍임경 |            CNN 모델 / EDA / 발표             |

**주제**

- 반려 동물 프로필 사진 인기도 예측


 **데이터 설명**

- 크롤링 이미지 데이터(Instagram, 동물보호관리시스템)
- Kaggle( Pawpularity Contest ) csv 파일
- Kaggle( Pawpularity Contest ) 이미지 데이터

**기대 효과**

- 딥러닝 모델 기본 프로필 사진의 인기도 및 데이터 분석
- 분석한 이미지의 개선이 필요한 부분을 제안하여 반려 및 유기동물의 프로필 사진의 조회수(인기도)증가
- 개선이 필요한 부분을 자동으로 향상시키는 솔루션

**분석 내용**

- **Selenium / Beautifulsoup**를 활용한 **데이터 크롤링**
- **파이썬 패키지**를(numpy, pandas등) 활용한 **데이터 전처리**
- **시각화 패키지**를(seaborn, matplotlib등) 활용한 **데이터 시각화**
- **Google Colab**를 활용한 **이미지 모델** 훈련 및 분석 

**사용 모델**

- **CNN**
- **전이학습 모델**( **EfficientNetB0**, **Vision Transformer** )
- **앙상블 모델**( **EfficientNetB0**, **meta data**)
- **객체 인식**( **YOLOv5** )
  - 강아지, 고양이 파일 분류
  - 동물 얼굴 범위 파악 및 시선처리 확인
  - 이미지 정형 데이터화


**참고자료 및 사이트 출처**

1. Kaggle( Pawpularity Contest ) / [https://www.kaggle.com/c/petfinder-pawpularity-score](https://blog.opensurvey.co.kr/trendreport/contents-2021/)
2. Instagram / https://www.instagram.com/explore/tags/%EC%9C%A0%EA%B8%B0%EA%B2%AC/?hl=ko
3. 동물보호관리시스템 / https://www.animal.go.kr/front/index.do





