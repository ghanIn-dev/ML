# 1. supervised , unsupervise

supervised learing : 데이터에 대한 명시적인 정답이 주어진 상태에서 컴퓨터를 학습시키는 방법

supervised learing : 데이터에 대한 명시적인 정답이 주어지지 않은 상태에서 컴퓨터를 학습시키는 방법

# 2. regression

regression analysis : 회귀 분석
- 회귀의 사전적 의미 : 다시 예전의 상태로 돌아감
- 주어진 데이터가 어떤 함수로부터 생성됐는가를 알아보는 "함수관계"를 추측하는 것

# 3. classification

classification : 분류
- 입력이 어떤 카테고리에 해당하는지 나누는 것
- ex) 스팸 메일, 학점이A,B,C,D 중 어느 것인지



-----------------------------------------

# 4. Lab1 TensorFlow

설치 : http://solarisailab.com/archives/384

1. tensorflow는 그래프를 먼저 빌드하고
2. sess.run을 통해서 그 그래프를 실행해야
3. 그래프 변수의 값이 변한다.

==

1. build graph
2. feed data and run
3. update value

### placeholder
그래프를 정의할때 placeholder로 만들게되면 sess을 실행할때 feed_dict={x:x_data} 의 형태로 값을 넘겨준다.

### tensor
rank : 차원
shape : 각각의 element 갯수  ex) [[1,2,3],[4,5,6],[7,8,9] 는 [3,3] 으로 나타냄
data-type: 보통 tf.float32





