# About
This analysis identifies three clusters of 2021 Kaggle survey participants by **k-means clustering** method. By digging further of each cluster, we name them as **explorers**, **climbers** and **experts**, depending on how they respond questions in regards of demographics, professions, their skill and knowledge in data science, the tools they are frequently using and tools they plan to get more familiar in the next two years.

# Motivation
This analysis tries to answer -

1. How many types of professionists in the data science field?
2. How does each segment of data science professionsts differ in demographics, professions, their skill and knowledge in data science, the tools they are frequently using and tools they plan to get more familiar in the next two years?

# Requiments
Python libraries are required to run this notebook

os/numpy/pandas/matplotlib/sklearn/pyarrow/plotly

# Description of each file
1. udacity_ds_nano_degree_capstone.ipynb
The notebook where analysis code is stored

2. data.parquet
The dataset from the data science online community kaggle [link](https://www.kaggle.com/competitions/kaggle-survey-2021).

3. README.md
Introduction of the project

# Summary of analysis
By adopting k-means clustering, we have identified three segments of participants of the Kaggle 2021 data science survey. They are -
1. explorers

They have interest in the data science field, probably because their work and study are relevant with the data science. Knowledge and skillset of this field such as programming and machine learning are new to them. They don't have much opportunity to use data science tools as any other cluster participants.

2. climbers
They are the most ambicious participants regarding their learning plan in the next two years. They are young and most likely live in the developing world. They have some degree of relevant knowledge and skillset, however, compared with experts, their scope of knowledge and skillset is a bit narrower. The majority of them are students or unemployed. 

3. experts
They are the building stones of the data science industry. They have the highest education degree among the three clusters in general. The majority of data scientists are allocated in this cluster. They are most likely working in giant tech companies in the developed world. On the other hand, their motivation to learn in the next two years is less than the climbers, at least telling from the survey answers.


# Acknowledgement
Massive and heartful thanks to Kaggle community [link](https://www.kaggle.com/competitions/kaggle-survey-2021) and all the survey participants for the hard work and the spirit of sharing.

