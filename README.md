# IMDb-Review-Sentiment-Analysis
Group project for my Applied Machine Learning class. Project aims to build an accurate model that predicts movie review sentiment. 

\# COMS 4995 Applied Machine Learning: IMDB Sentiment Analysis Project  
\#\# Authors: Alan Wong (ajw2252), Anna Micros (am6529), Emma Corbett (ec3745), Nuneke Kwetey (nfk2108), Xiqian Yuan (xy2655)  
The main dataset for this project is IMDB Dataset.csv. It is too large to include in this repository, so can be downloaded here: [https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) 

In this zip file, there should be the final report, the README file that you are reading, and a folder “Code” containing all the code written for this project. In that folder are three subfolders that should all contain code:

- 1\) Data Preprocessing and EDA    
  - AML\_Project\_Deliverable2.ipynb: A Python notebook containing data cleaning process and tokenization as well as exploratory data analysis of our dataset.    
  - wordcloud\_and\_barcharts.ipynb: A Python notebook containing additional exploratory data analysis done on the dataset.  
- 2\) Creating Embeddings  
  - README\_createEmbeddings.md: A README file containing instructions on how to create the embeddings from the processed data using create\_embeddings.py.    
  - create\_embeddings.py: The Python file containing the code to create the four embeddings that we will test with each of our models.  
- 3\) Models:  
  - BERT\_Model.ipynb: Code for running the Pre-trained BERT Transformer model using the data generated from create\_embeddings.py.    
  - DNN\_Model.ipynb: Code for finding the optimal Deep Neural Network model for each embedding type using the data generated from create\_embeddings.py.    
  - KNN\_Model.ipynb: Code for finding the optimal KNN model for each embedding type using the data generated from create\_embeddings.py.   
  - Logistic\_Regression\_Model.py: Code for finding the optimal Logistic Regression model for each embedding type using the data generated from create\_embeddings.py.    
  - Random\_Forest\_Model.ipynb: Code for finding the optimal Random Forest model for each embedding type using the data generated from create\_embeddings.py. Code for exploratory data analysis  from AML\_Project\_Deliverable2.ipynb is also present.  

Please do not hesitate to reach out if there are any questions.
