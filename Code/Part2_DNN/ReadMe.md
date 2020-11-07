인공신경망의 학습에 대한 세부적인 사항을 다룬다.

인공신경망의 학습을 향상시켜주는 방법의 타겟은 다음과 같다.

인공신경망의 흐름에 따라서 정리하면..

1) 학습데이터의 처리

2.1) 신경망의 아키텍쳐

2.2) 신경망의 가중치 초기화 기법
Xavier, He initialization (Normal, Uniform Distribution)

2.3) 신경망의 활성함수 선택
- sigmoid, tanh, ReLU, leaky ReLU ...

2.4) 신경망의 비용함수 선택
- Mean Square Error(MSEloss), Cross-Entropy(CossEntropyLoss), Binary Cross-Entropy(BCELoss)

2.5) 신경망 오차역전파의 수치최적화 기법들
Steepest Gradient Descent(SGD), RMSprop, Nestrov, Adam...

3) 신경망의 과적합 문제 (Overfitting)
Dropout : 

간혹 반복문 구성을 잘못해서 GPU 메모리 부족 문제가 발생하는데,
차차 공부해보는게 좋을 것 같다.
