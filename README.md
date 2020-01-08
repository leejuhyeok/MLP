인공지능 수업을 듣고 만든 필기체 인식 MLP 입니다.

## 학습 데이터
먼저 학습데이터는 총 10만개로 학습데이터 4만9천개와 데스트 데이터 2만1개로 구성되어 있습니다. 학습 데이터는 읽기 쉽게 txt파일로 변형시켜 28 X 28 의 바이너리 숫자로 구성되어 있습니다.

## MLP 구성
MLP의 구성으로는 hidden layer를 2개를 주었고, 휴리스틱은 적용을 시켜봤으나 알고리즘의 문제인지 아님 다른 문제가 있는지 학습 속도와 정답률에 큰 변화는 없었음으로 적용시키지 않기로 하였습니다.

## 최종 정답률
100회 정도 실행 해봤을때 평균 96%의 정답률을 보였다.

### 필기체 데이터는 용량문제로 압축하여 MultilayerPerceptron\src\main\resources\MNIST.zip 의 형태로 저장되어 있음으로 사용전에 압축을 풀어서 사용해야함

