# CIFAR-10 classification with HOG features + MLP

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iafrincu/MLP-HOG-CIFAR10-classifier/blob/master/Tema_SSPI_Ioana_Frincu_Eduard_Marin.ipynb)

Classifies the 10 classes of [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) (32×32 colour images) without a convolutional network: each image is described with **Histogram of Oriented Gradients (HOG)** features, which capture local edge orientations, and a **multilayer perceptron** from scikit-learn is trained on those descriptors. The target was at least 58% test accuracy.

## Running it

Open the notebook in Google Colab with the badge above and run all cells. All dependencies are preinstalled there; to run locally:

```bash
pip install -r requirements.txt
jupyter notebook Tema_SSPI_Ioana_Frincu_Eduard_Marin.ipynb
```

Keras is used only to download the dataset.

## Background

Originally a homework assignment for the SSPI course (Politehnica University of Bucharest) by Ioana Frincu and Eduard Marin.
