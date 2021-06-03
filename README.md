# Sparkify
Capstone project of udacity data scientist nanodegree
 
![alt text](https://i.pinimg.com/736x/5e/64/d8/5e64d895f7c72537ff5f4c97ba66e750.jpg "Sparkify")

# About
This project look to get insights of sparkify data to predict the churn of users in this plataform. You can read more of this project on my [Medium Blog](https://ssantos-igor.medium.com/sparkify-understand-the-costumers-e081168d077c]

# Requirements
* seaborn==0.8.1
* scipy==1.2.1
* scikit-learn==0.24.1
* pandas==1.1.5
* numpy==1.19.5
* matplotlib==2.1.0
* httpagentparser==1.9.1
* spark==2.4.3

# Project structure
This project have two notebooks. The notebook called `Sparkify Data Analysis.ipynb` there is some data analysis and `Modeling - Sparkify.ipynb` there is the modeling part.
`mini_sparkify_event_data.json` is a sample with the data from Sparkify. 
`workspace_utils.py` is a code to help the kernel at Udacity Workspace to keep it active.

# Results
The Logistic Regression Model and GBTs overfitting the model with F1-Score very high, 0.99 and 0.97 respectively, so Random Forest got the best performance without overfitting 0.86.

# Acknowledgment
To the Udacity instructors that help me to understand a lot of concepts of the way and to offer an amazing project idea to work.
# References

[Features Transformation and pipelines for pyspark](https://www.analyticsvidhya.com/blog/2019/11/build-machine-learning-pipelines-pyspark/)

[Fit models in pyspark](https://www.kaggle.com/tylerx/machine-learning-with-spark)

[Cv on pyspark](https://github.com/susanli2016/PySpark-and-MLlib/blob/master/Machine%20Learning%20PySpark%20and%20MLlib.ipynb)

[Undersampling Data on Scala](https://github.com/phatak-dev/spark-ml-kaggle/blob/master/src/main/scala/com/madhukaraphatak/spark/ml/UnderSampling.scala)
