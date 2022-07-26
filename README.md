#### 기초 수학
|분류|주제|설명|참조|
|:--:|:--:|--|--|
|순열|등차수열||[geogebra](https://www.geogebra.org/m/tpwcuzuj)|
|순열|조화수열|등차수열 역수||
|-|-|-|-|

#### 확률 + 통계
| 분류 | 주제 | 설명 |작성 | 데이터 | 이해 | 참조 |
| :---: | :---: | --- | :---: | :---: | :---: | :---: |
|통계|통계 각종 수치||[link](https://m.blog.naver.com/cni1577/221720979015),|[link](https://docs.google.com/spreadsheets/d/10TfbZuxD1Xn4hhDS8zpCkFw7i9V-3jQ5Qxk_NJ8PSKs/edit#gid=0)|[geogebra](https://www.geogebra.org/classic/snrdcwmz)|[youtube](https://youtu.be/m1b6-WY6A2A), [link](http://www.kmooc.kr/asset-v1:SNUk+SNU212.204.1k+2016+type@asset+block/2.2_%ED%91%9C%EC%A4%80%ED%8E%B8%EC%B0%A8%EC%99%80_%EC%9E%90%EC%9C%A0%EB%8F%84.pdf)|
|통계|정규분포||||[geogebra](https://www.geogebra.org/classic/xkmassdx)|[youtube 29:17](https://youtu.be/Xj5ylagamb8)|
|통계|공분산|||[link](https://docs.google.com/spreadsheets/d/10TfbZuxD1Xn4hhDS8zpCkFw7i9V-3jQ5Qxk_NJ8PSKs/edit#gid=239546892)|[?geogebra](https://www.geogebra.org/classic/d7rqhg7u)|[youtube](https://youtu.be/YEdscCNsinU)|
|통계|다변량정규분포|||-|-|[link](https://namyoungkim.github.io/probability/statistics/2017/09/11/probability_2/),[link](https://dhpark1212.tistory.com/entry/%EB%8B%A4%EB%B3%80%EB%9F%89-%EA%B0%80%EC%9A%B0%EC%8B%9C%EC%95%88-%EB%B6%84%ED%8F%ACMultivariate-Gaussian-Distribution)|

#### 선형대수학
+ refer 
  + [선형대수-youtube](https://youtube.com/playlist?list=PL5yujGYFVt0BCu7DXfEgD7M51Tj6S7s4A)
  + [데이터사이언스 스쿨-Doc](https://datascienceschool.net/intro.html)

| 분류 | 주제 | 설명 |작성 | 데이터 | 이해 | 참조 |
| :---: | :---: | --- | :---: | :---: | :---: | :---: |
| 가우시안 소거 |  | --- |  |  |  | [youtube](https://youtu.be/Ov7fetr-qg8), [doc](https://youtu.be/Ov7fetr-qg8) |
| 데이터형 | 데이터 형태 | 스칼라, 벡터,행렬,텐서 |[ipynb](./codes/LinearAlgebra_데이터형태.ipynb)| MNIST digits | |  |
|백터|백터연산|전치,영벡터,일벡터,정방행렬,대치행렬,대각행렬,항등행렬|[ipynb](./codes/LinearAlgebra_연산.ipynb)|sklearn.iris|[geogebra](https://www.geogebra.org/classic/bweyhzbf)|[youtube](https://youtu.be/R-XHrNq9Ff4), [*other pdf](https://github.com/insightcampus/sesac-nlp/blob/main/13%20%EA%B0%95%EC%9D%98%20-%20%EC%84%A0%ED%98%95%EB%8C%80%EC%88%98%20%EA%B8%B0%EC%B4%88.pdf)|
|행렬| 행렬 연산 |벡터-행렬 덧셈과 뺄셈, 스칼라-벡터/행렬 곱셈,브로드캐스팅|[ipynb](./codes/LinearAlgebra_데이터형태간연산.ipynb)|-|-| [*other pdf](https://github.com/insightcampus/sesac-nlp/blob/main/13%20%EA%B0%95%EC%9D%98%20-%20%EC%84%A0%ED%98%95%EB%8C%80%EC%88%98%20%EA%B8%B0%EC%B4%88.pdf) |
|벡터| 벡터 내적 | 내적 구하기, 제곱합 |[ipynb](codes/LinearAlgebra_내적.ipynb) |  |  |  |
|행렬| 행렬간 곱셈 | 행렬간 곱셈, 일반/전치 행렬 교환 법칙과 분배 법칙,항등행렬 곱셈,행렬과 벡터의 곱, 모핑(morphing) 효과  |[ipynb](./codes/LinearAlgebra_행렬간곱셈.ipynb) | | | |
|행렬|행렬식|행렬놈, 행렬식|[ipynb](./codes/LinearAlgebra_행렬식.ipynb)||||
| 유사도 | 유사도(similarity) | cosine |[ipynb](./codes/LinearAlgebra_유사도.ipynb) | sklearn.load_digits | 이해 | 참조 |
|선형회귀|선형회귀| 회귀 모델,가중합,다중 가중합, 가중평균,선형조합|[ipynb](./codes/LinearAlgebra_선형회귀.ipynb)|?아파트 가격|-|-|
|행렬|공분산행렬|-|-|-|-|-|
|행렬|고유값,고유벡터|-|-|-|[?geogebra](https://www.geogebra.org/classic/v2ysejp4)|[youtube](https://youtu.be/YEdscCNsinU), [*other pdf](https://github.com/insightcampus/sesac-nlp/blob/main/13%20%EA%B0%95%EC%9D%98%20-%20%EC%84%A0%ED%98%95%EB%8C%80%EC%88%98%20%EA%B8%B0%EC%B4%88.pdf)|
|행렬분해|고유값분해, SVD|-|[other SVD](https://github.com/insightcampus/sesac-nlp/blob/main/ipynb/14%20%E1%84%89%E1%85%B5%E1%86%AF%E1%84%89%E1%85%B3%E1%86%B8%20-%20%E1%84%89%E1%85%A5%E1%86%AB%E1%84%92%E1%85%A7%E1%86%BC%E1%84%83%E1%85%A2%E1%84%89%E1%85%AE%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9.ipynb)|-|-|[*other pdf](https://github.com/insightcampus/sesac-nlp/blob/main/13%20%EA%B0%95%EC%9D%98%20-%20%EC%84%A0%ED%98%95%EB%8C%80%EC%88%98%20%EA%B8%B0%EC%B4%88.pdf)|
|성분분석|PCA|+coding, linalg.eig, decomposition(sklearn)|[other ipynb](https://github.com/insightcampus/sesac-nlp/blob/main/ipynb/16%20%E1%84%89%E1%85%B5%E1%86%AF%E1%84%89%E1%85%B3%E1%86%B8%20-%20%E1%84%8E%E1%85%A1%E1%84%8B%E1%85%AF%E1%86%AB%E1%84%8E%E1%85%AE%E1%86%A8%E1%84%89%E1%85%A9.ipynb)|-|-|[*other pdf](https://github.com/insightcampus/sesac-nlp/blob/main/15%20%EA%B0%95%EC%9D%98%20-%20%EC%B0%A8%EC%9B%90%EC%B6%95%EC%86%8C.pdf)|
|-|-|-|-|-|-|-|

