# Tensorflow_DANN

TensorFlow Version Used: 2.0

This is an implementation of the paper Domain-Adversarial Training of Neural Networks(https://arxiv.org/abs/1505.07818). I have tested my implementation on 3 datasets ( MNIST, SVHN, SynNumbers).
Paper focuses upon Unsupervised Domain Adaptation via Backpropagation.

#### Source-only training results
|                              |  MNIST       | SVHN         | SynNumbers |
| :--------------------------: | :----------: | :----------: |:----------:|
| Source Training Accuracy     | 99.9%        | 99.7%        | 99.8%      |
| Source Test Accuracy         | 99.9%        | 91.5%        | 96.4%      |
| Target Accuracy(MNIST)       | -            | 71.3%        | 89.2%      |
| Target Accuracy(SVHN)        | 20.2%        | -            | 84.8%      |
| Target Accuracy(SynNumbers)  | 24.5%        | 91.1%        | -          |


I have used this implementation my research work for CT lung Images for Interstitial lung diseases (ILD).

This Repo will be updated soon with full description.
