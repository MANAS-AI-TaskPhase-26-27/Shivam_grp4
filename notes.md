 machiene learning is propcess of training a piece of software ( model ) to make useful predictions or generate content from givan data


        types of ml learning


1.0  supervised training
 
 the models make predictions after seeing lots of data with correct asnwers and then discovering the relation between elements in data that produce answers
 ex: A student learning new material by studying old exams that contain both Q and A . Once the student has trained on enough old exams , it can crack the new one .


* Regression

A regression model predicts a numeric value by analysing the given data
ex: A weather app that predicts amount of rain in inches or millimeters


* Classification

Classification models predict the likelihood that something belongs to a category. Classification models output a value that states whether or not something belongs to a particular category.
ex: if an email is spam or not

Classification Models

Binary Classification: outputs a value from a class that contains only 2 values.
ex: A model that outputs rain or no rain

Multiclass Classification: outputs a value from a class that contains more than 2 values.
ex: rain, hail, snow, sleet



2.0 unsupervised trainiung

The model aims to identify meaningful patterns in a dataset. Many unsupervised learning models rely on a technique called clustering to organize similar data into groups.
(Clustering differs from classification because categories aren't defined by you)

ex: An unsupervised model might cluster a weather dataset used in temp recording segmentation that defines the seasons. You might then attempt to name those clusters based on your understanding of the dataset.

An unsupervised algorithm doesn't know to label data.


3.0 II Reinforcement Learning

These models make predictions by getting rewards or penalties based on actions performed within an environment.
A reinforcement learning system generates a policy that defines the best strategy for getting most rewards.

Reinforcement Learning is used to train robots to perform tasks, like walking around a room.


4.0 generative AI

It creates content from user input.
ex: create unique imgs, music, jokes and can summarize articles, edit pic etc

Generative models learn patterns in data with the goal to produce new but similar data like.

ex: Artists who learn to paint in a particular style by studying lots of paintings in that style

    
     
     
     ai ml foundation



Deep Learning is a subset of machine learning that uses layered neural networks.
Analogy: teaching a kid about a cat, rather than saying "4 legs + whiskers etc", just show the kid many cat images and teach him.

#Training, Validation and Test Sets

*Training Set: The model learns from this, it sees input and adjusts itself to fit pattern. (Margin Note: 60-70%)

*Validation Set: Used during development to tune settings and check progress. (Margin Note: 15-20%)

*Test Set: Used only once, at the very end, to check how well the model performs on data it has never seen. (Margin Note: 15-20%)

*A model is a mathematical function that takes inputs and produces outputs with internal adjustable numbers called parameters.

q   Why Data Needs to be cleaned and preprocessed?
ans Real-world data is messy, missing values, inconsistent formats, duplicate rows etc.
     Feeding this directly into a model leads to poor or misleading results.


A model is only as good as the data it learns from.Handling Missing Data#TechniqueStrategyWhen to Use1DeletionRemove rows with many missing valuesWhen missing data is minimal $< 5\%$ and random2Mean/Median ImputationFill gaps with relevant mean or medianSimple, fast and reliable. Is better if data has outliers3Mode ImputationFill gaps with most frequent categoryCommon for categorical features4Forward / Backward FillUse the previous / next valueTime series Data5Predictive ImputationUse another model to predict missing modelWhen missingness has a pattern6Flagging as MissingCreate a new category for missingWhen absence itself is useful


