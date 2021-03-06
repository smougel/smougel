### Hi there ๐

- ๐ญ Iโm currently working on helping people to find a job (Analysis of Pole Emploi Dataset -> French job board)
- ๐ฑ Iโm currently learning about Data Science / AI / Deep Learning / Machine learning (Never ending process)
- ๐ฏ Iโm looking to collaborate on everything that has a meaningful purpose when I have time !
- ๐ซ How to reach me: https://www.linkedin.com/in/smougel/
- ๐ Pronouns: He/His

I've a background of 20 years as Software Engineer (Fullstack dev) and now I add a new card to my set as Data Scientist / AI Engineer.
I love to learn new things about Deep learning / CNN / Sequence Models (Many thanks Andrew NG & Coursera)

- ๐ป Programming languages : Python, Javascript, Php
- ๐๏ธ Databases : Maria DB / MySQL / Redis
- ๐ Front : React / Redux / Css / HTML 5
- ๐ง Web frameworks : Symfony / Laravel / Code Igniter
- ๐ฉ DB frameworks : Active Records, Doctrine ORM
- โ๏ธ Backend : Writing of Workers & Daemons
- โ Load & Queue management : Beanstalkd
- ๐ DataViz : Matplotlib , plotly, seaborn
- ๐งช Data science : Pandas, numpy, scikit learn, Tensorflow, Pytorch, keras

# Projects

I will open source them as soon as possible.


## Exploratory Data Analysis (Data for good): ๐ณ ๐ฒ ๐ฑ ๐ข Paris Trees ๐ณ ๐ฒ ๐ฑ

Goal : Helping Paris city to become a smart city.

Optimization of tree maintenance

Data source : opendata.paris.fr

My work : https://github.com/smougel/eda_paris_tree (Notebook & Presentation)

## Exploratory Data Analysis (Open food facts) ๐ ๐ ๐ ๐ง ๐ ๐ซ

Goal : Analyse and find healthy products / Inform people about nutritional metrics

My work : https://github.com/smougel/eda_open_food_facts (Notebook & Presentation)

## Credit scoring โ๏ธ ๐ฏ 

Build a model to detect people able to repay their loan... or not... 

๐ก Process :
- exploratory data analysis
- data cleaning
- feature engineering
- sampling / train & test split
- model training : SVM, Neural Networks, Logistic Regression, Random forest
- variable importance evaluation with lime

๐ Metrics : Precision / Recall / F1-Score

๐ช Hyperparameter tuning with grid-search and cross-validation

Tech used : Python, Scikit-learn, Matplotlib, Seaborn
Project : https://github.com/smougel/credit_scoring/tree/master (Notebook)

## Customer segmentation for e-commerce ๐จ ๐ง ๐ง ๐ฝ ๐

Unsupervised learning task

Dataset : Olist.com

Gain insights about user behavior and discover buyer characteristics

๐ก Process :
- exploratory data analysis
- data wrangling
- feature engineering
- dimensionality reduction : Principal Component Analysis
- clustering : k-means, db-scan
- elbow method
- High-dimensionality vizualisation : T-SNE, U-Map
- Analysis of cluster stability

๐ Metrics : ARI Score

## AI for Restaurants ๐ฝ๏ธ ๐

๐ก Customer dissatisfaction discovery
๐ช Automatic photo classification : Menu card, Food picture ๐, Outdoor picture

Dataset : https://www.yelp.com/dataset

๐ก Process :
- exploratory data analysis
- data wrangling for NLP (๐คฌ stop words , lemmatization, stemming, tokenization)
- data wrangling for photos (contrast normalization, resizing, noise filtering)
- Topic discovery : LDA
- Convolutional neural networks
- Regularization (Dropout)
- Exploration of filters learned by the CNN (Thanks to francois Chollet)
- Use of Yelp API

Tech used : Tensorflow, NLP, Sequence model, LSTM, CNN, Keras, Open CV

## Bad Buzz Detection in comments ๐ฃ๏ธ ๐ / ๐ 

Dataset : https://www.kaggle.com/kazanova/sentiment140 (1.6M Tweets)
Goal : Sentiment analysis from tweets. Benchmark with Microsoft Azure Sentiment Analysis.

๐ก Process :
- exploratory data analysis
- data wrangling (lemming / stemming / tokenization)
- modelization (Basic to advanced : logistic regression, TF-IDF, LSTM)
- benchmark with Azure Machine Learning Services

๐ช Hyper parameter tuning
๐ Metrics : F-Beta Score

Tech used : Word embeddings (Word2Vec & FastText), Tensorflow & Keras

## Image segmentation for autonomous driving ๐ค โค๏ธ ๐

Dataset : Cityscape

๐ก Process :
- exploratory data analysis
- data wrangling (Picture to binary mask)
- data augmentation (Random cropping, flipping, mirroring)
- modelization (Basic to advanced : Fully connected layers to U-Net architecture)
- โ๏ธ training in the cloud (w/ Microsoft Azure : compute instance provisionning)
- Model serving via Flask API hosted on Microsoft Azure

๐ช Hyper parameter tuning
๐ Metrics : Jaccard index

Tech used : Tensorflow, Keras, CNN, U-Net, Flask, Azure Services

## Content recommendation for news reading ๐ง ๐ช ๐

Dataset : News Portal User Interactions by Globo.com
https://www.kaggle.com/gspmoreira/news-portal-user-interactions-by-globocom#clicks_sample.csv

๐ก Process :
- exploratory data analysis (w/ t-SNE visualization of news embeddings)
- data wrangling 
- modelization : content filtering and collaborative filtering
- โ๏ธ training in the cloud (w/ Microsoft Azure : compute instance provisionning)
- Use of serverless Azure Function for model serving / Azure Storage
- Integration with a node js mobile app

๐ Metrics : Similarity measure (dot product, cosine)

Tech used : Tensorflow, Sparse Tensor, Matrix factorization, Azure Services

## Chatbot for vacation booking ๐ค ๐ช ๐ด โ๏ธ

Dataset : Microsoft frames dataset (Dialogs between two humans via a chat interface)
https://www.microsoft.com/en-us/research/project/frames-dataset/

๐ก Process :
- exploratory data analysis (w/ t-SNE visualization of news embeddings)
- data wrangling
- LUIS Training
- Integration w/ Microsoft bot framework

๐ Metrics : Similarity measure (dot product, cosine)

Tech used : Microsoft LUIS, Microsoft Bot Framework, Azure application insight, Unit Testing
