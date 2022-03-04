# Rainfall-Prediction
In this project, I will be implementing a predictive model on Rain Dataset to predict whether or not it will rain tomorrow in Australia.The Dataset contains about 10 years of daily weather observations of different locations in Australia. By the end of this project, you will be able to build a predictive model.

# Objectives: 
Design a predictive model with the use of machine learning algorithms to forecast whether or not it will rain tomorrow in Australia.

# Data Source:
The dataset is taken from Kaggle and contains about 10 years of daily weather observations from many locations across Australia.

# Dataset Description:

<ul> 
  <li> Number of columns: 23 </li>
  <li> Number of rows: 145460 </li>
 <li> Number of Independent Columns: 22 </li>
<li>  Number of Dependent Column: 1</li>

  </ul>

# Problem Statement: 
Build an efficient Classification Model that should predict whether it Rains Tomorrow or not, using the dataset Rain in Australia.
  
  
# Exploratory Data Analysis

In this EDA part I have to do the following steps. 

# Feature Engineering 
<ul>
  <li>Data Preprocessing</li>


<p>Missing Data We can use seaborn to create a simple heatmap</p>
  
![image](https://user-images.githubusercontent.com/95357575/156415986-1c7bc542-bd61-435b-8d25-8499854fbe47.png)
  
  <p>Bar Graph</p>   
  
  ![image](https://user-images.githubusercontent.com/95357575/156416386-36f85080-a700-4720-bd36-371d17b0b96e.png)


  <li>Data Cleaning </li>
  <li>Correlation</li>
  
  <p>To check the Correlation using Heatmap</p>  
  
  ![image](https://user-images.githubusercontent.com/95357575/156416618-d02350a9-8fc4-4679-9be6-0089af377b1b.png)

  
  <li>Finding categorical and Numerical features in Dataset</li>
  <li>Replace the Missing Values & Replace the Null values  </li> 
  
  <li>To Detect and Handle the Outliers </li>
  
  # To find the Outliers in the dataset Using Box plot 
  
  ![image](https://user-images.githubusercontent.com/95357575/156416884-141e150b-aab6-4c52-9894-a00f461ef8ad.png)

  <p> To Remove the Outliers & verifying in the dataset Using Box plot</p>
  
  ![image](https://user-images.githubusercontent.com/95357575/156417046-dd083eec-cd03-4703-8ddd-a81e48768599.png)
  
  
  <li>One Hot Encoding Method </li> 
  <p> Encoding Categorical Features using replace function</p>
 </ul>  
 
 # Classification models  
 <p>To apply the Machine Learning Algorithm</p>
 
 # Feature Selection 
 
 <p>Finding the Correlation</p>
 
 ![image](https://user-images.githubusercontent.com/95357575/156417692-beaf88ed-1f62-4a66-b57a-847e6f8574d6.png)

 
# Model Building 

<ul>
   <li>Model Training</li>
   <li>Model Testing</li>
   <li>Evaluating Model Performance using Accuracy, Confusion Matrix, Classification Report, RUC-AUC curve</li>
  </ul>
  
# Confusion Martix (Decision Tree Classifier) 
  
![image](https://user-images.githubusercontent.com/95357575/156783296-7eab11e6-4029-44db-9a45-5b7f87e613f4.png)


# Visualize the Performance of the Decision Tree Classifier Model  

![image](https://user-images.githubusercontent.com/95357575/156783483-15fb5ffc-a384-4ba1-9ad3-8cc36d1021da.png)


# Confusion Martix (Decision Tree Classifier (Entropy))

![image](https://user-images.githubusercontent.com/95357575/156784183-e8821642-caf5-401f-8fd3-b7511ac87c39.png)


# Visualize the Performance of the (Decision Tree Classifier (Entropy)) Model

![image](https://user-images.githubusercontent.com/95357575/156784137-b40f2d5a-3bec-4781-9064-c981780375b3.png)


# Confusion Martix (Decision Tree Classifier (Gini))
  
![image](https://user-images.githubusercontent.com/95357575/156784352-62042867-673a-470a-81ec-3b430e289653.png)


# Visualize the Performance of the (Decision Tree Classifier (Gini)) Model

![image](https://user-images.githubusercontent.com/95357575/156784432-6f6e014d-a10e-45fc-8043-6ef202942da8.png)



# Confusion Martix (Random Forest Classifier)
  
![image](https://user-images.githubusercontent.com/95357575/156784676-e08fbb59-f467-4564-84ae-2cfad1ae89f7.png)

# Visualize the Performance of the (Random Forest Classifier) Model

![image](https://user-images.githubusercontent.com/95357575/156784703-00f7861e-3674-4ba8-bffd-28c84adc075f.png)


# Confusion Martix (Logistic Regression)
  
![image](https://user-images.githubusercontent.com/95357575/156784859-56659559-1278-4c3c-b45a-f4c9616fe6fa.png)

# Visualize the Performance of the (Logistic Regression) Model

![image](https://user-images.githubusercontent.com/95357575/156784948-349191ba-c458-43b3-b574-d6a2079f6416.png)

# Confusion Martix (XGBoost Classifier)

![image](https://user-images.githubusercontent.com/95357575/156785059-f36adbdb-c5fc-4307-8d69-f058569abf28.png)

# Visualize the Performance of the (XGBoost Classifier) Model

![image](https://user-images.githubusercontent.com/95357575/156785132-bf6350da-e211-4d51-8207-8621e878e03e.png)

# Confusion Martix (Naive Byes)

![image](https://user-images.githubusercontent.com/95357575/156785219-36d926fe-d79d-4978-ace0-72ae2134e3af.png)

# Visualize the Performance of the (Naive Byes) Model

![image](https://user-images.githubusercontent.com/95357575/156785332-bc21e51f-9591-4d01-a9fe-9f079c1eae38.png)




# Comparative Analysis & Model Evaluation
  
 
![image](https://user-images.githubusercontent.com/95357575/156782985-acc6b17b-3b8c-4821-b2ad-a4b0f07c6fd8.png)



<h3> Here, We applied Five Machine learning algorithms, We can conclude that Random Forest classifier performs the best with 85.40% accuracy</h3> 

# Libraries used
<ul>
  <li> Data Cleaning: Numpy, Pandas </li>
<li> Visualisation: Seaborn, Matplotlib </li>
<li> Feature scaling: StandardScaler </li>
<li> Splitting to train and test: train_test_split </li>
<li> Accuracy calculation & confusion matixs: metrics,confusion_matrix,accuracy_score,precision_score,recall_score,f1_score </li>
<li> Algorithms: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, GaussianNB, XGBClassifier </li>

</ul>



  
