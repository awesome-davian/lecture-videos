# lecture-videos
Lecture video repository with some comments or time stamps

## Lectures Wiki (강의들에서 나온 주제별 모음)

* Convolutional Neural Networks for Text Classification:
    - https://youtu.be/bnmAsFBl4E4#t=1h08m08s (15m 30s)

* Fully-Connected Layer Perspective about Convolution:
    - https://youtu.be/bnmAsFBl4E4#t=1h31m14s (13m 30s)

* Four Different Perspectives of Matrix Multiplications (+ Brief Intro to Low-Rank Factorization):
    - https://youtu.be/00rwOWPEiY4#t=2h02m19s (36m 00s)
    - Prerequisite: Span, Inner Product

* Shallow overview of second-order optimization techniques (why second-order methods don't require the step size):
    - https://youtu.be/MGSw0wCwqmw#t=0h37m30s (14m 15s)
    - Prerequisite: Vanilla Gradient Ddescnet

* **[cs224n]** 4 explanation for Back propagation
	- https://www.youtube.com/watch?v=isPiE-DBagM&list=PLqdrfNEc5QnuV9RwUAhoJcoQvu4Q46Lja&index=5&t=0s

#### Deep Learning Details (need to confirm)
* Importance of Zero-centered Activation Function: (need to confirm)
    - https://youtu.be/vUimliXeBUY?t=3682
    - https://youtu.be/Wew7bCVx2gI?t=1411
* Dead ReLU: (need to confirm)
    - https://youtu.be/kZlrHIu1cQ8?t=3007 (9m)
* Fancier first-order optimization techniques beyond SGD (need to confirm)
    - Momentum : https://youtu.be/rAKk2t5USEc?t=2785 (20m 30s)
    - Adagrad/RMSProp/Adam : https://youtu.be/rAKk2t5USEc?t=4672 (28m)
* Model Ensembles - train multiple indepent models (need to confirm)
    - General description : https://youtu.be/rAKk2t5USEc?t=6369 (15m)
    - Dropout (The idea is to train an ensemble of DNNs) : https://youtu.be/rAKk2t5USEc?t=7293 (22m)
    - Generalization effect of SGD : https://youtu.be/rAKk2t5USEc?t=7561 (3m 10s)

#### CNN (need to confirm)
* Case Studies of CNN Architectures
    - VGGNet - (1) much deeper, (2) only 3x3 CONV: https://youtu.be/eTHlqBpRQDc?t=761
        + why does the stack of three 3X3 conv layers have same effective receptive field as one 7X7 conv?
        + the stack of three 3x3 conv layers has fewer parameters than 7x7 conv layer
    - GoogLeNet : https://youtu.be/eTHlqBpRQDc?t=1765
        + "inception module" : multiple receptive filed sizes, "1x1 convolution", "Auxiliary classification outputs to inject additional gradient at lower layers"
    - ResNet : https://youtu.be/eTHlqBpRQDc?t=3673
        + Residual connections enabling very deep networks (like 152-layer model)    

#### RNN (need to confirm)
* RNN/LSTM/GRU
    - RNN - Gradient Vanishing & Exploding
       + Causes to occur (Repetition of same linear transformation) : https://youtu.be/_LCkwu6tH0M?t=3841 (6m 30s)
       + Long-term Dependancy Problem : https://youtu.be/_LCkwu6tH0M?t=4237
    - LSTM : https://youtu.be/_LCkwu6tH0M?t=4543
       + Key success factor of LSTM and ResNet : https://youtu.be/f5reJVwTK0U?t=3750
    - GRU : https://youtu.be/_LCkwu6tH0M?t=6298, https://youtu.be/z3sBNVTuuss?t=133
* Attention model
    - Core Explanation : https://youtu.be/7ivUO7ER0iE?t=776 (41m)
    - Hard/Soft Attention : https://youtu.be/7ivUO7ER0iE?t=3259 (5m 30s)
       + Stochastic Hard Attention : https://youtu.be/7ivUO7ER0iE?t=4099 (2m)
    - Visual Question Answering (RNNs with Attention)
       + https://youtu.be/ut24qA_Gxu0?t=2936
       + https://youtu.be/7ivUO7ER0iE?t=4386
* Sequence to Sequence model
    - Chatbot/Machine Translation : https://youtu.be/7ivUO7ER0iE?t=4787
    - Seq2seq with Attention : https://youtu.be/7ivUO7ER0iE?t=5131
    - Attention example in Machine Translation (learning word-order) : https://youtu.be/7ivUO7ER0iE?t=5633

#### ML Basics (need to confirm)
* Epoch vs Iteration
    - https://youtu.be/_LCkwu6tH0M?t=2411
* Distance : KL Divergence(=distance, similar but different w/ metric), Edit distance, etc.
    - General description with regard to distance : https://youtu.be/f5reJVwTK0U?t=379
    - KL Divergence (Asymmetry, Greater than or equal to zero) : https://youtu.be/f5reJVwTK0U?t=1529
    - Cross Entropy Loss (cannot be equal to zero) : https://youtu.be/f5reJVwTK0U?t=2694
* Gradient of Vector/Quadratic form (Ref. Matrix Calculus - https://goo.gl/XkCibf)
    - Gradient Vector (multiple input and scalar output) : https://youtu.be/eAiQy5iQi5E?t=604
    - Gradient of Quadratic form : https://youtu.be/eAiQy5iQi5E?t=880
    - PCA : 1) centering 2) maximize the variance  https://youtu.be/eAiQy5iQi5E?t=1870
        + optimal C is found as an eigenvector - more about...
    - Gaussian Kernel, How to define similarity measure : https://youtu.be/eAiQy5iQi5E?t=2768
    
## Lectures (강의별 다루는 내용 모음)
--- 
### 2017_2 Big Data and Info Retrieval Lectures
* 빅데이터와 정보검색 강의.
* topic modeling, word emvedding, attention models, seq2seq models, question answering, memory networks 등을 다룬다.
* 강의링크 : https://www.youtube.com/playlist?list=PLep-kTP3NkcNqn2MtzkscRlTDYTiqKjzD


#### Lecture index
* course overview (Lecture 1)
    - 앞으로 배울 내용들을 간략하게 정리한다.
    - https://www.youtube.com/watch?v=Z-ptwY3fkVQ&list=PLep-kTP3NkcNqn2MtzkscRlTDYTiqKjzD&index=1
* topic modeling , word embedding (Lecture 2~4)
    - topic modeling, gradient descent, word embedding, negative sampling 등을 다룬다
    - 키워드와 다큐먼트의 용어 언급에서 간혹 바꿔 말하는 실수가 있으니 주의
    - https://www.youtube.com/watch?v=CCZ6LeanKIc&list=PLep-kTP3NkcNqn2MtzkscRlTDYTiqKjzD&index=2

---

### 두 번째 강의 추가는 이쪽으로..!
* 강의내용 ...
