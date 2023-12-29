# Graph2Text: Get Textual data from Bar charts

# Requirements
- PIL==10.0.1
- matplotlib==3.7.2
- pandas==2.1.1
- pytesseract==0.3.10
- sklearn==1.3.2
- torch==2.1.0
- torchvision==0.16.0
- tqdm==4.66.1

In addition to these python libraries, please make sure to download Tesseract OCR in your machine as pytesseract is just a wrapper that calls Tesseract OCR.
Download Tesseract from https://tesseract-ocr.github.io/tessdoc/Downloads.html.

# Code

The code folder contains two jupyter notebooks:-
- Graph2Text = This is the main system notebook which all training and predicting code
- Graph2Text_Predict_one_Image = This is a notebook which only has prediction code. It takes the path of a single image and predicts output for that image.

## To use Graph2Text 

To use the Graph2Text notebook, please follow the following steps:-
- Set images_path to path of images folder 
- Set annotations_path to path of json annotation folder
- Set model_path_loss to where you would like to store and extract the model from
- Set pytesseract.pytesseract.tesseract_cmd to the absolute path of tesseract executable 
- Run the notebook

## To use Graph2Text_Predict_one_Image 

To use the Graph2Text notebook, please follow the following steps:-
- Set image_path to path of image
- Set model_path_loss to where you would like to store and extract the model from
- Set pytesseract.pytesseract.tesseract_cmd to the absolute path of tesseract executable 
- Run the notebook
