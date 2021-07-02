# 1장 TensorFlow

### 1.1 TensorFlow란

텐서플로(TensorFlow)는 구글(Google)에서 만든, 딥러닝 프로그램을 쉽게 구현할 수 있도록 다양한 기능을 제공해주는 라이브러리다.

텐서플로 자체는 기본적으로 C++로 구현 되어 있으며, 아래의 그림과 같이 Python, Java, Go 등 다양한 언어를 지원한다. 하지만,  파이썬을 최우선으로 지원하며 대부분의 편한 기능들이 파이썬 라이브러리로만 구현되어 있어 Python에서 개발하는 것이 편하다.

또한, 브라우저에서 실행가능한 시각화 도우인 텐서보드(TensorBoard)를 제공하여, 딥러닝 학습 과정을 추적하는데 유용하게 사용된다.

### 1.2 TensorFlow의 의미

TensorFlow에서 **Tensor(텐서)**란 딥러닝에서 데이터를 표현하는 방식이라고 할 수 있다. 즉, 텐서는 **행렬로 표현할 수 있는 2차원 형태의 배열을 높은 차원으로 확장한 다차원 배열**이다. 

TenorFlow에서 계산은 **데이터 흐름 그래프(dataflow graph)**로 이루어 진다.  즉, 텐서 형태의 데이터들이 딥러닝 모델을 구성하는 연산들의 그래프를 따라 흐르면서 연산이 일어난다.

따라서, 딥러닝에서 데이터를 의미하는 **Tensor** 와 DataFlow Graph를 따라 연산이 수행되는 형태(**Flow**)를 합쳐 **TensorFlow** 란 이름이 나오게 되었다.

### 1.3 TensorFlow 특징

코드 수정 없이 CPU/GPU모드로 동작한다.

아이디어 테스트에서 서비스 단계까지 이용 가능하다.

분산(distributed) 실행환경이 가능하다.

계산 구조와 목표 함수만 정의하면 자동으로 미분 계산을 처리한다.

Python/C++를 지원하며, SWIG를 통해 다양한 언어 지원이 가능하다.

### 1.4 Installing TensorFlow

**1.4.0 파이썬 설치**

**1.4.1 아나콘다 설치**

본인의 OS에 맞게 다운로드(https://www.anaconda.com/products/individual#download-section)한다.

**1.4.2 텐서플로우 설치**

TensorFlow를 설치하기 위해 아나콘다를 관리자 권한으로 실행시켜 아래의 명령어를 입력한다.

- tensorflow 설치할 가상환경 구성

   👉 conda create -n "가상환경 명" python="파이썬버전"

- 가상환경 접속

   👉 conda activate "가상환경 명"

- tensorflow 다운로드

   👉 pip install tensorflow

혹은 source로 설치하기

👉 bazel