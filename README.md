# Deep Convolutional Generative Adversarial Network to Generate Dog Images

1. To train this network, download the DCGAN_GenDogs.ipynb notebook
2. Open the downloaded notebook in either Google Colab by clicking Upload and select the notebook 
3. Alternately you can click the link for the kernel in the linke to open in Kaggle and fork it there
4. If you went with Google Colab, you need to use Kaggle API by running the following code:
 
# Colab library to upload files to notebook
`from google.colab import files`

# Install Kaggle library
`!pip install -q kaggle`

# Upload kaggle API key file
`uploaded = files.upload()`

`!cp kaggle.json ~/.kaggle/kaggle.json`

`!kaggle competitions download -c generative-dog-images`

`!unzip all-dogs.zip`
`!unzip Annotation.zip`

Then you can the notebook to train the model.

The Kaggle is more preferable as both resources give you a GPU. 

The dataset wasn't able to upload to GitHub due to size restriction. 


