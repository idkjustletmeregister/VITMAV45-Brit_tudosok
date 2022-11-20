# Identification of Defective Manufacturing Products with a Convolutional Autoencoder - Group Project
## Description

Defective items are inevitable in a mass production process and companies are investing a lot into the detection and handling of such products. With the help of artificial intelligence, these processes can be made cheaper and much more efficient.  

The aim of our project is to identify faulty products from the MVTecAD Anomaly Detection Database with Unsupervised Learning techniques.  
For this task we are training a Convolutional Autoencoder on images that contain non-defective products. Since the autoencoder only encounters correct products during  training, it will reconstruct images of normal products correctly, but not the images of defective ones - as a result these will have a higher reconstruction error, thus making the identification of these products possible.


## Our team: Brit Tudósok


- Benjamin János Garzó [LP69C0]
- Gergő Marcell Miklós [WE507Q]
- Péter Herbai [RUS9IV]


## User guide

The updated source code of the project can be found in the uploaded `deep_learning_hw_milestone_2.ipynb` notebook.  

Or the notebook can be directly accessed in Google Colab by clicking this button:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Alwwnt0Ho4HYuWPxc6lluQ4NXnqPSC2s?usp=sharing)

All the training and testing related methods can be found and executed inside the notebook.
