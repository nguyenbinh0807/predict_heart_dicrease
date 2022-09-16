# predict_heart_dicrease
<img src='https://mendedhearts.org/wp-content/uploads/2018/06/HeartAttackPrevention.png' />
Heart disease describes a range of conditions that affect your heart. Today, cardiovascular diseases are the leading cause of death worldwide with 17.9 million deaths annually, as per the World Health Organization reports [1]. Various unhealthy activities are the reason for the increase in the risk of heart disease like high cholesterol, obesity, increase in triglycerides levels, hypertension, etc. [1]. There are certain signs which the American Heart Association [2] lists like the persons having sleep issues, a certain increase and decrease in heart rate (irregular heartbeat), swollen legs, and in some cases weight gain occurring quite fast; it can be 1-2 kg daily [3]. All these symptoms resemble different diseases also like it occurs in the aging persons, so it becomes a difficult task to get a correct diagnosis, which results in fatality in near future.

But as time is passing, a lot of research data and patients records of hospitals are available. There are many open sources for accessing the patient’s records and researches can be conducted so that various computer technologies could be used for doing the correct diagnosis of the patients and detect this disease to stop it from becoming fatal. Nowadays it is well known that machine learning and artificial intelligence are playing a huge role in the medical industry. We can use different machine learning and deep learning models to diagnose the disease and classify or predict the results. A complete genomic data analysis can easily be done using machine learning models. Models can be trained for knowledge pandemic predictions and also medical records can be transformed and analyzed more deeply for better predictions [4–6].
tôi sử dụng ba bài toán phân lại cụ thể là:

models = {"KNN": KNeighborsClassifier(),
          "Logistic Regression": LogisticRegression(), 
          "Random Forest": RandomForestClassifier()}
  
![Architecture](https://github.com/nguyenbinh0807/predict_heart_dicrease/blob/main/newplot.png) 
<p size=26px>tôi viết bằng ngôn ngữ python và build trên colab</p>
<ul>
<li>1.Description of the Dataset
</li>
<li>2.Preprocessing of the Dataset
</li>

2.1 Checking the Distribution of the Data

2.2 Checking the Skewness of the Data

2.3  Checking Stats of the Normal Distribution of Data

2.4 Feature Selection

2.5 Checking Duplicate Values in the Data
<li>3. Machine Learning Classifiers Proposed
</li>
</ul>
<div>các bước được viết trong file này: <a href='https://github.com/nguyenbinh0807/predict_heart_dicrease/blob/main/heart.ipynb'>file heart</a> </div>
<div>dataset from kaggle: <a href='
