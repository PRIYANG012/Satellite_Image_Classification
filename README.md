
# Satellite Image Classification using CNN.

The use of multimedia in applications for artificial intelligence, 
such as video summarization, picture retrieval, and image 
categorisation, is a fascinating and futuristic topic. 
In this project, we are creating a system to classify satellite 
images of 3 different datasets using 3 different CNN models and 
comparing their results with high-level observations. The CNN models we used are ResNet18, VGG19 and DenseNet121. The datasets in which we implemented these models are Satellite Data, EuroSAT and Amazon Planet Dataset. 
    
## Datasets

Following are the details and download links of our datasets.
It should be downloaded in local machine in order to run our models.

| Dataset           | Author        | Download Links |
| ----------------- | --------------|----------------|
| Sat Data (RSI-CB256) |  [mahmoudreda55](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification)|[Kaggle](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification), [GDrive](https://drive.google.com/drive/folders/1Gmy_Lr625n8LjnIKaAI1DRcK8UMscZTi?usp=sharing) |
| EuroSAT | [nilesh789](https://www.kaggle.com/nilesh789) | [Kaggle](https://www.kaggle.com/code/nilesh789/land-cover-classification-with-eurosat-dataset/data), [GDrive](https://drive.google.com/drive/folders/1Gmy_Lr625n8LjnIKaAI1DRcK8UMscZTi?usp=sharing) |
| Amazon Planet | [Planet](https://www.planet.com/) | [Kaggle](https://www.kaggle.com/competitions/planet-understanding-the-amazon-from-space/data), [GDrive](https://drive.google.com/drive/folders/1Gmy_Lr625n8LjnIKaAI1DRcK8UMscZTi?usp=sharing)  |


## Models
The downloadable .pth models are uploaded on this link :

https://drive.google.com/drive/folders/1VD1s7dcR0OhPpPZwPPsA7rD4ND_sGq1o?usp=sharing

## Requirements

The following bullet points are the links of the libraries/frameworks we used in our project. In order to run our models, 
these libraries must be installed in the local machine. 

* [Python3](https://www.python.org/downloads/)
* [Pytorch](https://pytorch.org/)
* [Numpy](https://numpy.org/install/)
* [OpenCV](https://opencv.org/releases/)
* [Matplotlib](https://matplotlib.org/stable/users/installing/index.html)
* [SciPy](https://scipy.org/install/)
* [Sklearn](https://scikit-learn.org/stable/install.html)
* [Optuna](https://optuna.org/#installation)
* [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
* [Seaborn](https://seaborn.pydata.org/installing.html) 


## How to test model:
1. To test the model load the testing.ipynb file from notebooks folder.
2. Give the input path of the model in torch.load()
3. We have defined a dictionary named sat_map for EuroSAT dataset, which will convet our predicted output to labels. Similarly we can do it for other 2 datasets.
4. To pass the image for which the classification has to be done, we just need to pass the path of that image in image.open() method.
5. Run the shell to get the prediction.

## How to train model:
1. To train the model load the respective .ipynb file from the notebooks folder.
2. Give the input path of the model in torch.load()
3. To pass the image for which the classification has to be done, we just need to pass the path of that image in image.open() method.
5. Run the shell to get the prediction.
