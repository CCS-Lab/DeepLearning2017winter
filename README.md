<img width="25%" src="https://ccs-lab.github.io/images/ccs-lab-logo.png" align="right">

# README

This repository is to study Deep Learning with people in [CCS-Lab][ccs-lab], in 2018 Winter (January - February 2018). All the materials in the repository can be used in addition to [the Sung Kim's lectures][humkim-dl] and [its codes][dl-zero-to-all].

[ccs-lab]: https://ccs-lab.github.io
[humkim-dl]: https://hunkim.github.io/ml/
[dl-zero-to-all]: https://github.com/hunkim/DeepLearningZeroToAll

## Week 1 (2018-01-15)

- **Lectures**
    - 머신러닝의 개념과 용어
    - Linear Regression의 개념
    - Linear Regression Cost 함수 최소화
    - 여러 개의 입력의 Linear Regression
- **Materials**
    - [Main material](./week-1/) by [Jaeyeong Yang][jaeyeongyang]
    - [Supplement for TensorBoard](./week-1/tensorboard.html) by [Jaeyeong Yang][jaeyeongyang]

## Week 2 (2018-01-22)

- **Lectures**
    - Logistic (Regression) Classification
        - Hypothesis 함수 소개
        - Cost 함수 소개
        - TensorFlow에서의 구현
    - Softmax Regression (Multinomial Logistic Regression)
        - Multinomial 개념 소개
        - Cost 함수 소개
        - Lab 1: TensorFlow에서의 구현
        - Lab 2: TensorFlow에서의 Fancy한 구현
- **Materials**
    - [Main material](./week-2/) by [Jimin Sun][jiminsun]
    - [Plotting with PCA](./week-2/PCA_plotting.html) by [Jaeyeong Yang][jaeyeongyang]

## Week 3 (2018-01-29)

- **Lectures**
    - ML의 실용과 몇가지 팁
        - 학습 rate, Overfitting, 그리고 일반화 (Regularization)
        - Training/Testing 데이타 셋
        - Lab 1: TensorFlow에서의 구현 (학습 rate, training/test 셋으로 성능평가)
        - Lab 2: Meet MNIST dataset
    - 딥러닝의 기본 개념과, 문제, 그리고 해결
        - 딥러닝의 기본 개념: 시작과 XOR 문제
        - 딥러닝의 기본 개념2: Back-propagation과 2006/2007 '딥'의 출현
        - Lab: Tensor Manipulation
- **Materials**
    - [Main material](./week-3/) by [Hyeonjin Kim][hyeonjinkim]

## Week 4 (2018-02-13)

- **Lectures**
    - Neural Network 1: XOR 문제와 학습방법, Backpropagation (1986 breakthrough)
        - XOR 문제 딥러닝으로 풀기
        - 특별편: 10분 안에 미분 정리하기
        - Deep Network 학습시키기 (backpropagation)
        - Lab 1: XOR을 위한 TensorFlow Deep Network
        - Lab 2: TensorBoard로 Deep Network 들여다보기
    - Neural Network 2: ReLU and 초기값 정하기 (2006/2007 breakthrough)
        - XSigmoid보다 ReLU가 더 좋아
        - Weight 초기화 잘해보자
        - Dropout과 앙상블
        - 레고처럼 넷트웍 모듈을 마음껏 쌓아 보자
        - Lab: 딥러닝으로 MNIST 98% 이상 해보기

## Week 5 (2018-02-19)

- **Lectures**
    - Convolutional Neural Networks
        - ConvNet의 Conv 레이어 만들기
        - ConvNet Max pooling 과 Full Network
        - ConvNet의 활용 예
        - Lab 1: TensorFlow CNN의 기본
        - Lab 2: TensorFlow로 구현하자 (MNIST 99%)
        - Lab 3: Class, tf.layers, Ensemble (MNIST 99.5%)

## Week 6 (2018-02-26)

- **Lectures**
    - Recurrent Neural Networks
        - NN의 꽃 RNN 이야기
        - Lab 1: RNN의 기본
        - Lab 2: Hi Hello RNN Traning
        - Lab 3: Long Sequence RNN
        - Lab 4: Stacked RNN + Softmax Layer
        - Lab 5: Dynamic RNN
        - Lab 6: Time Series RNN

## Useful Resources

- [A Primer on Using LaTeX in Jupyter Notebooks | Democratizing Data](http://data-blog.udacity.com/posts/2016/10/latex-primer/)
- [28 Jupyter Notebook tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)

[jaeyeongyang]: https://github.com/PluVian
[jiminsun]: https://github.com/jiminsun
[hyeonjinkim]: https://github.com/ChulBal
