# TRASH DETECTION - BANGKIT FINAL PROJECT - BDG 2B

Trash Detection is an Android App. The Goal of this project to makes better waste management system in Indonesia.

## Android App

You can Download App in this Link [App Final Version](https://github.com/MohammadFebriyanto/TrashDetection/raw/master/Banfkit_Final_Project_New.apk)

You can Install this App in your Android 

## Modeling Method

We use two model to make a Comparation in this project, The first Model We use CNN model that we make from scratch, but the result of this model has a low Confidence in TFlite.

On the second model we use Mobilenetv2 architecture as pretrained model and add 4 layer in the last model. We got around 80% and high confidence on this model so we decide to use this model.

Click below to run Colab notebook:

[![Modeling without Pretrained model] (https://colab.research.google.com/github/MohammadFebriyanto/TrashDetection/blob/master/Machine%20Learning/Modeling%20without%20Pretrained%20model.ipynb)]

[![Modeling with Pretrained model](https://colab.research.google.com/github/MohammadFebriyanto/TrashDetection/blob/master/Machine%20Learning/transfer_learning_mobilenetv2.ipynb)]
