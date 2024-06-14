# PyTorch-Implementations

## CNN

**[DenseNet-BC](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/CNN/DenseNet_BC_Implementation.ipynb)**

Following the DenseNet paper, implemented DenseNet-BC with settings of {L=121, k=32}.

## NLP

**[IMDB Sentiment Classification](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/NLP/IMDB%20Sentiment%20Classification.ipynb)**

Downloaded the dataset from torchtext.datasets.IMDB and preprocessed it into a DataLoader format where an example is ((32, 256), (32, 1)). Each sentence was tokenized and then numerized using the vocabulary from the training dataset, followed by padding to a length of 256. Then created a model that utilizes two layers of bi-directional LSTM layers and trained it with the dataset. It achieved an accuracy of 87% on the validation set.


## VAE
[VAE](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/VAE/VAE.ipynb)

## GANs

[DCGAN_MNIST](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/GAN/DCGAN_MNIST.ipynb)

[Conditional_GAN](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/GAN/Conditional_GAN.ipynb)

[GAN_MNIST](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/GAN/GAN_MNIST.ipynb)

[WGAN](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/GAN/WGAN.ipynb)

[Pix2Pix](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/GAN/Pix2Pix.ipynb)


## TransFormers
[ViT-Base](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/TransFormers/VIT_Base_Implementation.ipynb)

## Kaggle Competitions

[Digit Recognizer](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/Kaggle%20Competitions/Digit%20Recognizer.ipynb)
[Facial Keypoints Detection]()
[Natural Language Processing with Disaster Tweets]()
