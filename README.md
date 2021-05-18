### Hi there 👋

- 🔭 I’m currently working on helping people to find a job (Analysis of Pole Emploi Dataset -> French job board)
- 🌱 I’m currently learning about Data Science / AI / Deep Learning / Machine learning (Never ending process)
- 👯 I’m looking to collaborate on everything that has a meaningful purpose when I have time !
- 📫 How to reach me: https://www.linkedin.com/in/smougel/
- 😄 Pronouns: He/His

I've a background of 20 years as Software Engineer (Fullstack dev) and now I add a new card to my set as Data Scientist / AI Engineer.
I love to learn new things about Deep learning / CNN / Sequence Models (Many thanks Andrew NG & Coursera)

- 💻 Programming languages : Python, Javascript, Php
- 🗂️ Databases : Maria DB / MySQL / Redis
- 💍 Front : React / Redux / Css / HTML 5
- 🔧 Web frameworks : Symfony / Laravel / Code Igniter
- 🔩 DB frameworks : Active Records, Doctrine ORM
- ⚙️ Backend : Writing of Workers & Daemons
- ⌚ Load & Queue management : Beanstalkd
- 📊 DataViz : Matplotlib , plotly, seaborn
- 🧪 Data science : Pandas, numpy, scikit learn, tensorflow, pytorch, keras

# Projects

I will open source them as soon as possible.


## Exploratory Data Analysis (Data for good): 🌳 🌲 🌱 🏢 Paris Trees 🌳 🌲 🌱

Goal : Helping Paris city to become a smart city.

Optimization of tree maintenance

Data source : opendata.paris.fr

My work : https://github.com/smougel/eda_paris_tree (Notebook & Presentation)

## Exploratory Data Analysis (Open food facts) 🍕 🍇 🍓 🧀 🍔 🍫

Goal : Analyse and find healthy products / Inform people about nutritional metrics

My work : https://github.com/smougel/eda_open_food_facts (Notebook & Presentation)

## Credit scoring ✒️ 💯 

Build a model to detect people able to repay their loan... or not... 

💡 Process :
- exploratory data analysis
- data cleaning
- feature engineering
- sampling / train & test split
- model training : SVM, Neural Networks, Logistic Regression, Random forest
- variable importance evaluation with lime

📏 Metrics : Precision / Recall / F1-Score

🪛 Hyperparameter tuning with grid-search and cross-validation

Tech used : Python, Scikit-learn, Matplotlib, Seaborn

## Customer segmentation for e-commerce 👨 👧 🧓 👽 🙆

Unsupervised learning task

Dataset : Olist.com

Gain insights about user behavior and discover buyer characteristics

💡 Process :
- exploratory data analysis
- data wrangling
- feature engineering
- dimensionality reduction : Principal Component Analysis
- clustering : k-means, db-scan
- elbow method
- High-dimensionality vizualisation : T-SNE, U-Map
- Analysis of cluster stability

📏 Metrics : ARI Score

## AI for Restaurants 🍽️ 🍝

😡 Customer dissatisfaction discovery
🪄 Automatic photo classification : Menu card, Food picture 🍝, Outdoor picture

Dataset : https://www.yelp.com/dataset

💡 Process :
- exploratory data analysis
- data wrangling for NLP (🤬 stop words , lemmatization, stemming, tokenization)
- data wrangling for photos (contrast normalization, resizing, noise filtering)
- Topic discovery : LDA
- Convolutional neural networks
- Regularization (Dropout)
- Exploration of filters learned by the CNN (Thanks to francois Chollet)
- Use of Yelp API

Tech used : Tensorflow, NLP, Sequence model, LSTM, CNN, Keras, Open CV

## Bad Buzz Detection in comments 🗣️ 👍 / 👎 

Dataset : https://www.kaggle.com/kazanova/sentiment140 (1.6M Tweets)
Goal : Sentiment analysis from tweets. Benchmark with Microsoft Azure Sentiment Analysis.

💡 Process :
- exploratory data analysis
- data wrangling (lemming / stemming / tokenization)
- modelization (Basic to advanced : logistic regression, TF-IDF, LSTM)
- benchmark with Azure Machine Learning Services

🪛 Hyper parameter tuning
📏 Metrics : F-Beta Score

Tech used : Word embeddings (Word2Vec & FastText), Tensorflow & Keras

## Image segmentation for autonomous driving 🤖 ❤️ 🚗

Dataset : Cityscape

💡 Process :
- exploratory data analysis
- data wrangling (Picture to binary mask)
- data augmentation (Random cropping, flipping, mirroring)
- modelization (Basic to advanced : Fully connected layers to U-Net architecture)
- ☁️ training in the cloud (w/ Microsoft Azure)
- Model serving via Flask API hosted on Microsoft Azure

🪛 Hyper parameter tuning
📏 Metrics : Jaccard index

Tech used : Tensorflow, Keras, CNN, U-Net
