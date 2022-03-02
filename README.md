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
  
  <p>To find the Outliers in the dataset Using Box plot</p>
  
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

 
 # Comparative Analysis of the Algorithms 
 
 ![image](https://user-images.githubusercontent.com/95357575/156417921-0cac1a81-51b7-405d-ba8e-05d3bf620699.png)


 
 # Model Building 

<ul>
   <li>Model Training</li>
   <li>Model Testing</li>
   <li>Evaluating Model Performance using Accuracy, Confusion Matrix, Classification Report, RUC-AUC curve</li>
  </ul>
  
<p>Confusion Matrix (XG Boost) </p>  

![image](https://user-images.githubusercontent.com/95357575/156418180-0fa1b3cc-0272-4563-91fb-55d3ebfd8c41.png)


<p>Confusion Martix (Random Forest Algm) </p>  

![image](https://user-images.githubusercontent.com/95357575/156418329-46e25293-2b81-484c-b7b9-3e68cd08cabe.png)

<p>RUC-AUC curve</p> 

![image](https://user-images.githubusercontent.com/95357575/156418417-16fe2ec2-1a33-480b-9e6a-b3aae67bd6c1.png)


# Model Evaluation
  
 
![image](https://user-images.githubusercontent.com/95357575/156418500-bc6f1ab9-30d5-47e1-b965-63fd57137d43.png)


<h3> Here, We applied Six machine learning algorithms, We can conclude that Random Forest classifier performs the best with 85.34% accuracy </h3> 






  
