# bigdata 빅데이터 
* 정승희
* 김주영

# 시각장애인 마트 쇼핑 서비스

## 목적

* 시각 장애인의 오프라인 쇼핑 편의 향상

## 방향

* 마트 물건 이미지 및 크롤링하여 마트내 제품 DB화, 사용자화

## 수행방법 및 도구

* 라이브러리: beautifulSoup(크롤링),selenium, pandas(데이터 정제), matplotlib, seaborn(시각화)
* API : 네이버지도API(위치정보)
* DB : MongoDB

## 필수기능
1. 사용자 위치 인식 - 어떤 마트에 와있는지 위치 정보 가지고 오기.
2. 사용자  쇼핑리스트 만들기 ,
3. 상품별 품목 정렬하기 (식품, 가전, 신선식품, 생활용품 등)
4. 쇼핑순서 정하기
5. 매장내 위치정보 만들기(각 상품별 코너 위치)

---

# 수어영상 한글 번역기
## 목적
* 수어를 모르는 사람과 청각 장애인 간의 원활한 의사 소통을 돕는다

## 방향
* 제품 이미지 학습 및 쇼핑 경로 안내

## 수행방법 및 도구
* 라이브러리 :Python + jupyter lab, matplotlib, numpy, pandas, seaborn, selenium
* DB : MongoDB

## 필수기능

수어 이미지 데이터 정제 :
단어와 문장 형태의 수어 이미지 데이터 분석 및 시각화.
여러 데이터셋을 수집 후 전처리.

수어 문장과 한글 문장 pair로 구성.


## 요구사항 
위치 데이터 없는경우-mediapipe, opencv, openpose 사용해서 분석
coco나mpii사용해서 body값 추출하고 거기에 
손keypoints들 추가로 더해서 bodyparts, pose pair만들기?


