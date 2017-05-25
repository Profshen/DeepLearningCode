# CharCnn_Keras

Text classification from character-level using convolutional networks. It can be used to reproduce the results in the following article:

Xiang Zhang, Junbo Zhao, Yann LeCun. [Character-level Convolutional Networks for Text Classification](http://arxiv.org/abs/1509.01626). Advances in Neural Information Processing Systems 28 (NIPS 2015)

![Alt text](./charcnn/model.png "The model")

## How to use
First, specify the training and testing data sources in the config.py file.

Then, run the training.py file as below:
```sh
$ python char_cnn.py
```

