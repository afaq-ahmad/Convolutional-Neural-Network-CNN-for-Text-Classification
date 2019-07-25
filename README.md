# Convolutional-Neural-Network-CNN-for-Text-Classification
Convolutional Neural Network (CNN) for Text Classification in different categories

## Dataset:
  
  |Categories|No. of Examples|
  |----------|---------------|
  |politics|3626|
  |sports|1963|
  |Technology|2134|
  |Food & drink|2543|
  |entertainment|541|
  |Promotion|876|
  |Family|297|
  |travel|297|
  |education|133|
  |style & beauty|74|
       
  Dataset is made by combining different opensource datasets.
  
  ## Requirements:
  pip install --user --requirement requirements.txt
  
      OpenCV==3.4.1
      openpyxl==2.6.2
      xlrd==1.2.0
      XlsxWriter==1.1.8
      xlutils==2.0.0
      xlwings==0.15.8
      xlwt==1.3.0


## Steps:

      -Dataset preparation
          >Loading the dataset
          >Dataset Features Counting
      -Feature Engineering
          >Tokenizing
          >Word Embeddings as features
      -Train Test Spliting
      -Text Tokenizing
      -Word Embedding
      -Categorical Veriable Handling
      -CNN Model Building
      -Training the model
      -Testing the model
      -Testing on New Data File

### Note:
-Download wordtovector model:
    
    Download the the 'wikinews300d1mvec.zip' and place the wiki-news-300d-1M.vec in the Model directory.
-Download the pretrained our weights and place them in Model directort if you want to test directly. 

   [Download Link](https://www.dropbox.com/sh/bc289jpbz80rzpk/AABiNzv2TqDD4K_npZIeKG8aa?dl=0)

