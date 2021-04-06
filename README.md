# Airbnb price prediction using multi-input(text and image) and output (price, type of listing)
- preprocessing data
- parameter search
- pipelining
- **models used**: CNN with attention layer implemented
- **dataset**: uses Airbnb image and text data available on Kaggle
- **goal**: This problem involves predicting a price range for new listers on Airbnb. Several factors constitute an ‘acceptable’ price such as various amenities, location, size, and even pictures. For this problem we want to create a model that uses this information to predict a price, which is categorized into beginner, plus and premium as 0,1,2 respectively. In this problem we have both text and image data being used as input for our independent variables. However, for our dependent or target variable, we actually have two instead of one making it a multi-target classification problem. The output of this problem, however, only predicts for one of those target variables which is price, the other target variable is type which refers to the type of the listing (house, apartment…). There are some advantages of doing this; usually single output models take longer to train and are more computationally expensive than multioutput ones. Data mining functions requires include natural language processing techniques such as tokenizing and other preprocessing methods. Image mining techniques will also be used such as padding, feature extraction, etc. It also requires techniques used to build a model, which in this case starts with a neural net, libraries such as pandas, keras, etc. can be used to formulate these models.
- full_dumentation file provides more detail on EDA and modeling findings

**Paste code link here if .ipynb files won't open (or take too long to open): https://nbviewer.jupyter.org/**
