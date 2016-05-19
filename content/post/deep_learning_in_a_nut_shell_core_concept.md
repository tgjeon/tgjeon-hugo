+++
categories = ["Translation"]
date = "2016-04-23T16:58:51+09:00"
tags = ["Deep Learning", "Translation"]
title = "Deep Learning in a Nutshell: Core Concepts"
+++

> [Original post] is written by Tim Dettmers

이 포스트는 [Parallel ForAll] 에 작성하는 시리즈 중 첫 글이며, [딥 러닝](https://developer.nvidia.com/deep-learning)에 대해 직관적이고 가볍게 소개하고자 한다. 본 포스트는 딥 러닝의 가장 중요한 개념을 다루고 있으며, 수학적 이론 지식보다 기본적인 개념의 전달을 목적으로 한다. 수식과 함께라면 더 깊은 이해가 가능하겠지만, 이 포스트는 비유와 그림을 통해 더욱 이해하기 쉬운 직관적인 개요를 전달하고자 한다. 
이 글들은 단어사전식으로 작성되어 딥러닝 개념을 위한 참고자료로 사용 될 수 있다.

[Part 1]에서는 딥 러닝의 중요한 개념에 대해서 소개한다. [Part 2]에서는 딥 러닝의 역사적 배경과 학습 과정, 알고리즘, 실용적인 기법 등을 살펴본다. [Part 3]에서는 자연어 번역을 위한 sequence learning 에 대해 알아본다. recurrent neural networks, LSTMs, encoder-decoder system을 포함한다.

### Core Concepts (핵심 개념)
----

#### Machine Learning (기계 학습)
기계 학습을 통해 우리는 (1) 데이터를 획득하여, (2) 데이터를 통해 모델을 학습하고, (3) 학습된 모델을 이용하여, 새로운 데이터에 대해 예측한다. 모델을 [학습](http://devblogs.nvidia.com/parallelforall/deep-learning-nutshell-history-training#training)하는 과정은 새롭고, 익숙치 않은 자료를 하나씩 살펴보고 배움을 얻는 과정과도 같다. 각 단계마다, 모델은 예측을 하고, 얼마나 정확히 예측하였는지에 대해 피드백을 받는다. 이 피드백은 정답으로부터 얼만큼 차이가 나는지 등과 같은 방법을 통해 측정 가능한 오류(error)를 통해, 예측을 더 정확하게 하는데 사용된다.


학습과정은 종종 파라미터 공간 (parameter space)에서 후진-전진이 반복는 게임이다: 만약 당신이 좋은 예측 결과를 얻기 위해 모델의 파라미터를 수정한다면, 이전에 제대로 예측했던 것도 수정 이후, 틀리게 예측될 수도 있다. 우수한 예측 성능을 가진 모델을 학습한다는 것은 많은 반복 작업이 필요할 것이다. 이런 반복적인 예측-수정의 과정은 예측 결과가 더 이상 발전이 없을 때 까지 반복한다. 


#### Feature Engineering (특징 추출)
특징 추출은 [기계 학습](https://devblogs.nvidia.com/parallelforall/deep-learning-nutshell-core-concepts/#machine-learning) 모델로 하여금 데이터들로 부터 클래스들을 쉽게 구분 할 수 있도록 도와주는 유용한 패턴을 추출 하는 것이다. 예를 들어,사진으로 부터 땅과 물고기를 구분하는 것을 초록색과 푸른색 픽셀의 수를 이용한다고 하자. 이런 특징은 기계 학습 모델에 도움이 된다. 좋은 분류를 위해 클래스의 갯수가 제한되어 있기때문에 좋은 분류가 가능하다. 

특징 추출은 대부분의 예측 분야에서 좋은 성능을 얻기위해 요구되는 가장 중요한 기술이다. 하지만, 다른 데이터 셋과 다른 종류의 데이터들은 각자 다른 특징 추출 기법이 필요하기에,최고의 특징 추출 기술을 습득하고 마스터하기엔 어렵다. 특징 추출은 과학이라기 보다 예술의 경지에 가깝다. 특정 데이터 셋에서 추출된 특징은 종종 다른 데이터 셋에서는 적용되지 않는다. (위 예제에서 계속하여, 다음 사진이 오직 육지 동물만 포함하는 경우). 특징 추출이 어렵다는 점과 많은 노력이 요구되는 점이 **자동으로 특징을 학습할 수 있는 알고리즘**을 찾게 되는 가장 큰 이유이다.



While many tasks can be automated by Feature Learning (like object and speech recognition), feature engineering remains the single most effective technique to do well in difficult tasks (like most tasks in Kaggle machine learning competitions).

#### Feature Learning (특징 학습)

#### Deep Learning (딥 러닝)


### Fundamental Concepts (기본 개념)
----------

#### Logistic Regression ()

#### Artificial Neural Network (인공 신경망)

#### Unit

#### Artificial Neuron

#### Activation Function 

#### Layer


### Convolutional Deep Learning 
-------

#### Convolution

#### Pooling / Subsampling

#### Convolutional Neural Network (CNN)

#### Inception


### Conclusion to Part 1
-----



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [Original post]: https://devblogs.nvidia.com/parallelforall/deep-learning-nutshell-core-concepts
   [Parallel ForAll]: https://devblogs.nvidia.com/parallelforall
   [Part 1]: https://devblogs.nvidia.com/parallelforall/deep-learning-nutshell-core-concepts
   [Part 2]: https://devblogs.nvidia.com/parallelforall/deep-learning-nutshell-history-training
   [Part 3]: https://devblogs.nvidia.com/parallelforall/deep-learning-nutshell-sequence-learning
   
   