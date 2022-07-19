## 주관 데이콘 

<br>


![image](https://user-images.githubusercontent.com/86671456/179655651-e010c2d9-b55d-4457-8a04-be74dfa71e4c.png)


## Abstract

| 분석명 |목적|결과|
|:-----:|----------|-----|
|쇼핑몰 평점 리뷰 데이터| 리뷰데이터를 기반으로 평점 예측|미정|

|  소스 데이터 |     데이터 입수 난이도    |      분석방법     |데이터 출처|
|:------------------:| -----|:---------------:|-----------|
|CSV, txt|하 |supervised Learniing,NLP    |데이콘|
|  분석 적용 난이도  |     분석적용 난이도 사유    |      분석주기     | 분석결과 검증 Owner|
|중| 긍/부정 분류는 많이 했지만 다중 분류의 경험은 적음|Daily|Dacon |



<br>

### Machine Learning Project 

---
**진행: 애자일 방법론**

|  프로젝트 순서 |     Point    | 세부 내용 |  
|:------------------:| -----|------|
|문제 정의|해결할 점, 찾아내야할 점 |텍스트 데이터를 통해서 평점을 예측할 수 있는가|
|데이터 수집|공개 데이터, 자체 수집, 제공된 데이터 |데이콘data, |   
|데이터 전처리|문제에 따라서 처리해야할 방향 설정 |결측치는 없지만, 텍스트의 전처리는 필요|
|Feature Engineering|모델 선정 혹은 평가 지표에 큰 영향|텍스트 데이터 전처리, 패딩, 토크나이저 활용|
|연관 데이터 추가|추가 수집 |텍스트 리뷰를 하는 다각도의 방법을 활용할 때 사용한 데이터와 대회의 데이터 연관성 파악 |
|알고리즘 선택| 기본적, 현대적|TF-IDF, BERT, Transformer|   
|모델 학습|모델을 통해서 얻고 싶은 것 |비정형 데이터인 리뷰 데이터를 활용하여 평점 예측|
|모델 평가|확률 | 
|모델 성능 향상|성능 지표, 하이퍼파라미터, 데이터 리터러시 재수정 |하이퍼파라미터 조정 및 추가 Ensembling, Top5%   |

<br>

### Basic information

**공식기간: 2022.07.11 ~ 2022.08.05**


- 인원: [이세현](https://github.com/qsdcfd)
- 직책: 
- 데이터: Dacon 데이터(train, val, test, submission)
- 주 역할:
- 보조 역할: 
- 추가 역할:
- 협업장소: Github, GoogleMeet
- 소통: Slack, Notion,Git project, Google OS
- 저장소: Github, Google Drive
- 개발환경: Visual studio code, Juypter Notebook, colab
- 언어 :python 3.8.x
- 라이브러리:Numpy,Pandas, Scikit-learn 1.1.x, lazypredict, Pycaret,Keras, Tensorflow, Pytorch
- 시각화 라이브러리: Seaborn, Matplotlib, Plot,Plotly, Tensorboard
- 시각화 도구: Tableau, GA
- 웹 크롤링: Slunimue

<br>

#### 파일 설명


- docs: 문서화 작업
- conf: 환경설정 관련
- build: 데이터 집산
- Definition: 프로젝트의 전반적인 문제 정의 및 내용 설정
- Data: 전처리 파일 및 모델링을 위한 파일
- models: 여러 모델들의 집합
- src :scripts
