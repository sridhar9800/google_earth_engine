# google_earth_engine
This repository contains code for performing inference on the Landsat ETM+ images to generate a binary mask showing the glaciated pixels of the image
The code can be run on Google Colab for which a Google account is required and you will need to authenticate your account access
User can look in to this presentation from 2018 Google Earth Engine user summit to get idea about Colab and deep learning 
(https://docs.google.com/presentation/d/1fEf-oScgbC9zjbzI3K3jUlHf4JdmoSLFiG_H491FUmk/edit)
In this code I am using Pytorch instead of TensorFlow
The advantage of using Colab and EarthEngine is that you don't need to download the Landsat Images on your hard disk to test the Neural Network model
At the moment there are issues with the limited RAM with the free colab usage. So I am unable to process the whole ETM+ image
UNet_Glaciers is the trained Neural network model
GlacierDelineationDeepLearning.ipynb is the code which you can upload in to your Colab app
