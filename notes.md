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



1.0 Deep Learning
is a subset of machine learning that uses layered neural networks.
Analogy: teaching a kid about a cat, rather than saying "4 legs + whiskers etc", just show the kid many cat images and teach him.

#Training, Validation and Test Sets

*Training Set: The model learns from this, it sees input and adjusts itself to fit pattern. (Margin Note: 60-70%)

*Validation Set: Used during development to tune settings and check progress. (Margin Note: 15-20%)

*Test Set: Used only once, at the very end, to check how well the model performs on data it has never seen. (Margin Note: 15-20%)

*A model is a mathematical function that takes inputs and produces outputs with internal adjustable numbers called parameters.

q   Why Data Needs to be cleaned and preprocessed?
ans Real-world data is messy, missing values, inconsistent formats, duplicate rows etc.
     Feeding this directly into a model leads to poor or misleading results.




2.0 Handling Outliers
Outliers are data points that are unusually far from the rest. Might be genuine rare events or errors.

How to handle?
Remove — if it was error
Keep it — if genuine
Use Robust models — Some algorithms are naturally less sensitive to outliers



3.0 Feature Scaling
Feature scaling is a data processing technique used to bring different numeric features onto a similar numerical scale.
Without scaling, the algorithm assumes larger numbers are more important.

Person A: age = 25, Salary = 67000
Person B: age = 35, Salary = 69000

Acc to ML algorithm:
Diff in age = 10, Diff in Salary = 2000

Because 2000 is much larger than 10, the model will act as if age barely exists even though a 10 year age gap might be far more significant than a 2000 salary difference.



4.0 overfitting VS Underfitting

Overlifting: The model learns the training data too well. It performs great on training data but poorly on new data.
Low training error, high test error

Fix: Get more training data, simplify the model, and Early Stopping (stop training before it starts memorizing).

Underlifting: The model is performing poorly on both training and test data.
High training error, high test error

Fix: Train longer, add more relevant features

We detect these by comparing Validation/Test accuracy and Training accuracy.

Evaluation Metrics
How we grade a machine learning model's performance. Because accuracy can lie, we rely on a tool called confusion matrix to see what the model is getting right and wrong.

True Positive: There is fire, and alarm rings
True Negative: There is no fire, alarm stays mute
False Positive: No fire, but alarm rings anyways
False Negative: There is fire, but alarm didn't ring




