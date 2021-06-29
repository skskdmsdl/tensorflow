# 1장 머신러닝


### 1.1 머신러닝이란

기계 학습또는 머신 러닝은 **인공 지능**의 한 분야로, **컴퓨터가 학습할 수 있도록 하는 알고리즘과 기술을 개발하는 분야**를 말한다. 가령, 기계 학습을 통해서 수신한 이메일이 스팸인지 아닌지를 구분할 수 있도록 훈련할 수 있다.

기계 학습의 핵심은 **표현(representation)**과 **일반화(generalization)**에 있다. 표현이란 데이터의 평가이며, 일반화란 아직 알 수 없는 데이터에 대한 처리이다. 이는 **전산 학습 이론** 분야이기도 하다.

### 1.2 Supservised Learning과 Unsupervised Learning

**지도 학습(Supervised Learning)**

- 지도학습이라는 이름에서 알 수 있듯이 입력 데이터에 대한 정답(label 또는 class)이 함께 주어진다.
- 모델의 입력값으로 각각의 데이터에 대한 정답이 함께 주어진다.
- Binary-Classification 분류 모델이 그 예시이다.

**비지도 학습(Unsupervised Learning)**

- 반면 Unsupervised Learning에서는 모델의 입력값으로 오직 입력 데이터만 주어진다.
- 즉 정답이 없는 학습을 모델에게 요구하는 것이다.

- 데이터를 탐색하여 내부 구조를 파악하는 것이 목적이며 비지도 학습은 트랜잭션 데이터에서 특히 효과적이다.


- 특징으로는 데이터 분석을 통해 unknown pattern을 학습할 수 있게 된다.

      그 결과로 우리는 새로운 데이터가 입력으로 주어졌을 때 분류할 수 있게 된다.

- 예를 들어 데이터 간의 유사도(similarity), 패턴(pattern), 차이(difference) 등으로 데이터를 분류할 수 있는 학습을 진행하는 것이다.

### 1.3 Types of supervised learning

**1️⃣ 회귀(regression)**

Predicting final exam score based on time spent

**2️⃣ 이진 분류(binary classification)**

Pass/non-pass based on time spent

**3️⃣ 다중 라벨 분류(multi-label classification)**

Letter grade (A, B, C, E and F) based on time spent
