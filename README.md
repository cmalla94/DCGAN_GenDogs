# Deep Convolutional Generative Adversarial Network to Generate Dog Images

## Instructions

1. To train this network, download the [DCGAN_GenDogs.ipynb](DCGAN_GenDogs.ipynb) notebook.
2. You can either: 
    * Open the downloaded notebook in [Google Colab](https://colab.research.google.com/) by clicking `Upload` and selecting the notebook.
    * Alternately, click the link for the [kernel](https://www.kaggle.com/jesucristo/gan-introduction) in the link to open in [Kaggle](https://kaggle.com) and fork it there. (Recommended)

_Note:_ Both Resources do provide access to a GPU

## Google Colab Setup

If you chose to use Google Colab, you need to setup the Kaggle API. The following commands need to be executed within the notebook to before use:

### Import Google Colab Library to upload files to the Notebook: 
`from google.colab import files`

### Install Kaggle library
`!pip install -q kaggle`

### Upload Kaggle API key file

`uploaded = files.upload()`

### Setup the environment

```
!cp kaggle.json ~/.kaggle/kaggle.json

!kaggle competitions download -c generative-dog-images

!unzip all-dogs.zip

!unzip Annotation.zip
```

## Additional Information

After installing the necessary libraries and setting up the environment, you can run the notebook to train the model.

_Note:_ The dataset is not uploaded to GitHub because of the size restriction. 