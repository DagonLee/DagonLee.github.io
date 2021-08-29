---
title: "Keras vs Tensorflow vs Pytorch"
categories: 
  - MachineLearning
last_modified_at: 2021-08-28
toc: true
---
## Keras

Tensorflow, Theano, MXNet 등 딥러닝 프레임워크 위에서 동작하는 High-level API로 사용자 친화적으로 개발되어 있기 때문에 비교적 간단한 신경망을 구축할 때 혹은 빠른 시간 내에 테스트를 해야만하는 경우 좋은 선택이 될 수 있습니다. 

하지만 Tensorflow, Pytorch에서와 같은 디테일한 조작이 불가능하다는 단점이 있습니다.

## Pytorch VS Tensorflow

두 프레임워크 모두 low-level api로 대표적인 딥러닝 프레임워크입니다.

두 프레임워크의 대표적인 차이점은 computation graph를 생성하는 방법의 차이입니다.

Tensorflow의 경우 static computation graph 방식을 사용하여 그래프를 먼저 정의하고 실행하는 define and run 형태의 실행이 이루어집니다. 

반면 PyTorch는 dynamic computation graph방식을 사용하여 define by run 형태의 실행이 이루어집니다.

define by run 방식으로 모델의 흐름을 동적으로 제어할 수 있다는 장점은 debugging을 용이하게하여 연구 및 개발에 효과적이고 실제로 Pytorch로 쓰여지는 논문이 Tensorflow보다 많습니다.

![스크린샷 2021-08-17 오후 10.42.35.png](Keras,%20Tensorflow,%20Pytorch%20de76d79a166f4bb8a83ab21d92701953/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2021-08-17_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_10.42.35.png)

## Reference

---

[www.imaginarycloud.com/blog/pytorch-vs-tensorflow/](https://www.imaginarycloud.com/blog/pytorch-vs-tensorflow/)

[https://smilegate.ai/2021/07/05/tensorflow-vs-pytorch/](https://smilegate.ai/2021/07/05/tensorflow-vs-pytorch/)