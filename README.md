# PyTorch-Implementations


**IMDB Sentiment Classification**
Downloaded the dataset from torchtext.datasets.IMDB and preprocessed it into a DataLoader format where an example is ((32, 256), (32, 1)). Each sentence was tokenized and then numerized using the vocabulary from the training dataset, followed by padding to a length of 256. Then created a model that utilizes two layers of bi-directional LSTM layers and trained it with the dataset. It achieved an accuracy of 87% on the validation set.
> [notebook](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/NLP/IMDB%20Sentiment%20Classification.ipynb)

**DenseNet**
Following the DenseNet paper, implemented DenseNet-BC with settings of {L=121, k=32}.
> [notebook](https://github.com/seungjun-green/PyTorch-Implementations/blob/main/CNN/DenseNet_BC_Implementation.ipynb)
