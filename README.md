
## Cesar Olivares
This is my portfolio of Data Science/Machine Learning projects.<br>
[Portfolio](https://colivarese.github.io/Portfolio/)

- Potato Leaves Disease Classification on Google Cloud 🥔🥬🍂
 -On this project a Convolutional Neural Network model is trained using images from potato leaves,
 with three clases, healthy and two with diseases. The model achieves an accuracy around 0.95.
 The model is used in a React local webpage having a drag and drop function, which returns the
 predicted class with its accuracy.
 <!--
 <p align="center">
 <img width="360" alt="Captura de Pantalla 2022-01-03 a la(s) 19 39 26" src="https://user-images.githubusercontent.com/80273045/148007912-17dc44c5-2dc6-44fa-9126-0e345ffda445.png"> <img width="360" alt="Captura de Pantalla 2022-01-03 a la(s) 19 40 20" src="https://user-images.githubusercontent.com/80273045/148008320-02b47121-1c63-4eca-84c2-4f2a8664b7bf.png">
 </p> -->

The trained model is then loaded into Google Cloud Platform, connected with the FastAPI to get
predictions with a cloud server and tested with Postman.

# Sentiment Analysis on Movies Reviews 😃🤬🍿
On this project a pre-trained BERT Model was taken from Hugging Face, specifically a Multilingual uncased sentiment to assign a value to a sentence given on the sentiment of the text. Data was retrieved from the popular website RottenTomatoes using the Request Dependency, processed with the BeautifulSoup library and RegEx, finally formatted on a Pandas DataFrame. [Source code](https://github.com/colivarese/Sentiment-Analysis-with-BERT-and-Web-Scrapping/blob/main/Sentiment_Analysis_using_BERT.ipynb)
<!--
<p align='center'>
 <img width="360" alt="Captura de Pantalla 2022-01-03 a la(s) 19 39 26" src="https://user-images.githubusercontent.com/80273045/148017280-018bf722-a535-4a79-91b0-5d006fc17d3a.jpeg">
</p> -->

# Bank Churners Prediction using Tree's Algorithms 🏦💳🌳
On this project we capture data from Kaggle, perform Exploratory Data Analysis, cleaning, feature engineering, categorical encoding and use the data to train different Tree Models, use cross validation to find the one with the best performance and fine tune the parameters. ![Source code] (https://www.kaggle.com/csarolivares/credit-card-customers-eda-modeling/notebook)
<!--
<p align='center'>
 <img width="480" alt="Captura de Pantalla 2022-01-03 a la(s) 19 39 26" src="https://user-images.githubusercontent.com/80273045/148121268-afedee1d-2573-49d0-a7f3-cfb338a47e67.png">
</p> -->

# MNIST Digit Generator with GANs 🔢🤖
On this project we take the popular MNIST dataset which consists of tens of thousands images of hand written digits, design a Generative Adversarial Network, train it on the dataset to generate more realistic digits on every epoch.
