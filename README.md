# movie-review-classification
&lt; IMDB 영화 리뷰 Binary Classification >

### 영화 리뷰의 텍스트 감성을 분석해서 긍정(Positive)과 부정(Negative)으로 이진 분류

> **< 자연어 전처리 과정 >**
> 1. HTML 태그 제거
> 2. 문장기호와 특수기호 제거
> 3. Stopword 제거
> 4. Lemmatization

### 데이터 벡터화

> BOW(Bag of Words)
> 1. CountVectorizer
> 2. TfidfVectorizer

### 모델 훈련

> **Logistic Regression**

### 교차 검증
> - cross_validate()
> - GridSearchCV()
