Description

In this challenge, we predict the wine quality. To do so, we have to use the machine learning tools : `Pytorch` or `Tensorflow`.   
In our case, we use `Tensoflow - Keras` tool for ours depp learning model.   



Installation   

To install `Tensorflow` use the following command line :   

    # Requires the latest pip
    pip install --upgrade pip

    # Current stable release for CPU and GPU
    pip install tensorflow

    # Or try the preview build (unstable)
    pip install tf-nightly
for more informations, please follow this [link]('https://www.tensorflow.org/install?hl=fr')  


Usage  

In this project, we use `Tensorflow` to make predictions about the wine quality. for that, we do it in several steps:  

1 - Load data:   
the dataset is loaded after a first preprocessing.  
caracteristics:   

    rows = 6497  
    columns =  12 
    labels = 7  

2 - Baseline   

Build the baseline, the basic machine learning model model with which we train the dataset to get first results to improve.  

Parameters:  
    - layers = 4  
    - Epochs = 80  
    - activation = 'relu' and sigmoid
    - 
(Visuals)
(Contributors)
(Timeline)
(Personal situation)