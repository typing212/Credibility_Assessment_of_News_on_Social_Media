# Credibility_Assessment_of_News_on_Social_Media
In this project, we will leverage upon text analytics techniques, machine learning tools and self-learning strategy to establish an automated credibility assessment model for social media news. In addition, as we all know that texts on a social media platform tends to share similarity. In order to eliminate the platform-induced bias, we introduce three datasets from different sources and use self-learning. 


## Techniques
PySpark, NLP, Self-traning

## Content
In this project, firstly, by extracting information from news headlines and body content from the first two labeled datasets, a text news classification model is built as the preliminary model to detect the textual similarity in different categories. 

Then, we conduct self-learning based on the preliminary model to predict on an unlabeled dataset with interactive information and compare the predicting results with spam scores. 

Finally, we take the interactive information features into account, such as the number of replies, the number of participants, etc., to find the relationship between them and the credibility of news. 



## Dataset
We combine four fake and real news datasets in order to have enough data for the text news classification model and eliminate platform-induced bias. Two of them are labeled (Dataset I and II), which will be used to build the preliminary model. The third dataset (Dataset III) is unlabeled but has interactive information features, which will be used to conduct self-training and interactive information exploratory.

## Insights
This methodology is useful when there is only limited amount of data without label. In practice, if the equipment conditions can support, pre-training the preliminary model on a larger dataset with records from various sources will be recommended. Also, when the model applied to a dataset on a specific platform without abundant labeled data, we could manually label several records and then use these records to conduct self-train. Therefore, the self-training process will fine-tune the model to better predict this dataset.


## Collaborators

Nanhai Zhong

Yishun Liu

Yuankai Ma

Jiankun Wang

Liuyang Chen
