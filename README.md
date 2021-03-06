# Big-data-analytics - CSCI 7000 - 003 , University of Colorado, Boulder

### Project Title:

Reliability of social media platform

### Team Members:

Vandana Sridhar, Xiaotong Diao, Yu-Lin Chou 
Section - 001

### Project Description:

We are building a model to estimate the percentage of fake followers in Twitter users' accounts. We intend to use these statistics as a reference to aid companies in finding the correct customer base in social media marketing.

### Dataset:

1) twitter_data: A sample dataset queried from Twitter consisting of both public and private user profiles

2) clean: cleaned data from MIB dataset

3) data.zip: Queried 5 youtubers followers profile and tweets information


### Code: 

1) twitter_query - consists of node.js code to query Twitter followers' data

2) Model - consists of code to clean the MIB Benchmark dataset, training the model (model_train.py) and predicting output labels(predict.py)

clean MIB dataset by executing the following command. Need to change the path to MIB dataset folder
```
python cleanMIB.py
```

train and analyze model by executing the following command. Need to change the path to the folder contains cleaned data
```
python model_train.py
```

predict results by executing the following command. Need to change the path to the folder contains cleaned data and queried data
```
python predict.py
```

3) Analyzation - consists of jupyter notebooks for analysing the benchmark dataset and analysing youtubers data.

Add the sample dataset and obtain the MIB dataset from this link - http://mib.projects.iit.cnr.it/dataset.html and add them to same folder as these codes. These notebooks can be run in jupyter notebook through the Anaconda Console.
```
Analyzing training data- MIB dataset.ipynb 
```

```
analyzing youtubers' data.ipynb
```




### Key Results:

Key results consists of screenshots of model evaluation, execution trace, and result analytics.

### Project Report included.



