# 리슐랭, 진(짜)리(뷰)를 찾아서
![리슐랭_메인_이미지](https://user-images.githubusercontent.com/29910793/173190189-4af05db6-7020-4b03-946d-9697e9bc79a0.jpg)
# 2022 1학기 캡스톤 프로젝트

### 1. 개요
요즘 현대사회에서 배달 앱은 거의 모든 사람들의 폰에 깔려 있다고 해도 과언이 아닙니다. 이러한 배달 앱에서 가장 주목 해야 할 부분은 역시 소비자의 메뉴와 음식점 선택에 큰 영향을 미치는 별점과 리뷰가 아닐까 싶습니다. 대부분의 소비자들은 그 전 소비자들이 남긴 리뷰를 보고 결제를 고민합니다. 점주들 또한 가게의 리뷰와 별점에 따라 배달 앱 속 노출 순위가 달라지고 그것이 매출과 직결되기 때문에 신경을 쓰지 않을 수 없습니다. 이렇게 경쟁이 치열한 배달 업계에서 리뷰의 중요도는 점점 올라가는데, 요즘 리뷰들을 과연 모두 신뢰할 수 있을까요? 

리슐랭, 진리를 찾아서 에서는 블랙컨슈머나 리뷰이벤트 등으로 온전히 믿을 수 없게 된 별점과 리뷰를 제외하고 감정분석 모델학습을 통해 한번 더 필터링한 진실된 리뷰들의 키워드과 별점을 확인하실 수 있습니다.



### 2. 동기
현재 배달의 민족, 요기요와 같은 유명 배달앱의 리뷰 별점이 리뷰이벤트 참여 등으로 대부분 상향 평준화 되어 있습니다. 그로 인해 실제로 높은 별점을 가지고 있는 음식점에도 불구하고 그 품질이나 서비스가 기대에 못 미치는 경우가 상당히 자주 발생합니다. 반대로, 꽤 괜찮은 배달 음식점이지만, 악질적인 블랙컨슈머들의 리뷰로 훨씬 저평가 되는 곳도 존재합니다. 이러한 각각의 상황에서 배달 음식점에 대한 진실된 평가가 제대로 보여지지 않기 때문에 위와 같은 문제를 해결하고자 아이디어를 제안하게 되었습니다.



### 3. 목표
배달 음식점의 리뷰를 긍/부정 평가 및 감정분석을 통해 한번 더 필터링해서 소비자와 점주에게 도움이 되는 새로운 리뷰점수를 도입하는 것이 저희가 기획한 앱 리슐랭의 목표입니다. 이 앱은 소비자들의 음식점 선택에 올바른 근거를 제시해 줌과 동시에 음식점의 자체적인 발전에도 기여할 것으로 예상됩니다. 



### 4. 수행 방안

![1](https://user-images.githubusercontent.com/29854638/159894496-6295273d-c0e6-4db4-b78d-cecaf1ccc06e.jpg)
![2](https://user-images.githubusercontent.com/29854638/159894500-1e2f6640-637c-4679-961c-593317fcda4a.jpg)
![3](https://user-images.githubusercontent.com/29854638/159894504-ad392547-8829-47ae-b462-92f2a72c6d70.jpg)
#### 리뷰 크롤러 
매장의 리뷰 데이터 수집하는 크롤러 제작에 python 사용 예정

#### 모델 개발
Tensorflow lite를 이용한 감정분석모델 개발 예정

#### 사용자 어플 개발
분석할 매장 선정 및 모델 결과값 출력 용도의 어플 개발 예정

#### 어플 예상 디자인
<img src = "https://user-images.githubusercontent.com/29854638/159910752-31b66a92-9aa4-4df3-b7d3-b17af906676a.jpg" width="100%" height="100%">



### 5. 주요 개발 프로세스
![4](https://user-images.githubusercontent.com/29854638/159895179-63e62196-434f-4f41-8f65-ebe88b862b30.jpg)




