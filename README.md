# <div align="Center">Sentimental-Analysis-on-Movie_Reviews </div>

## 1. 프로젝트 주제 

도우반（豆瓣） 영화 리뷰데이터를 활용하여 NLP 모델을 기반 영화 리뷰 평점에 대한 감정 분석(분류) 프로젝트

## 2. 프로젝트 문제 정의 

생성한 딥러닝 모델링(학습)을 통해 프로젝트 데이터의 타겟 변수인 평점에 대해 특성 변수인 리뷰 데이터가 그에 대응하는 평점을 얼마나 잘 예측하는지에 대한 프로젝트를 진행한다. 

## 3. 프로젝트 데이터 

<P>
<div align="center"><IMG src='https://user-images.githubusercontent.com/78430460/146902418-8c87b6c9-f625-4565-b4df-b582abc95346.png' height=40% width=40%></div> </P>

### 데이터 미리보기
<P>
<div align="center"><IMG src='https://user-images.githubusercontent.com/78430460/146907378-2bea9f88-bdd2-4e35-b255-84f57c440efe.png' height=50% width=50%></div> </P>  
  
- star 컬럼의 수치가 클수록 긍정 리뷰값, 작을수록 부정 리뷰값
<br>
  
豆瓣电影은 중국의 영화 종합 사이트로서, 해당 사이트에서 가공한 약 210만 개의 영화 리뷰, 평점 데이터로 구성된 캐글 출처 데이터를 사용하여 일반적으로 쓰이는 영어 데이터가 아닌 중국어 데이터를 활용한 NLP 프로젝트를 수행함으로서, NLP(자연어 처리) 모델에 대한 이해를 확장시키는데 그 목적이 있다. 
  
데이터 출처 : https://www.kaggle.com/utmhikari/doubanmovieshortcomments
 
## 4. 프로젝트 분석 방법

<IMG src='https://user-images.githubusercontent.com/78430460/146906746-f04c86e2-ebf6-466c-92dc-40354793a46d.png' height=40% width=40%>

- "Jieba" 라이브러리를 사용한 리뷰 데이터(특성 변수) 분철화 
- "바이두 불용사전"을 적용한 불용어 전처리 수행
- 모델링 적용을 위한 각 단어 벡터화(수치화)
