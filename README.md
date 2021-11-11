# Breast-Cancer-Wisconsin-Diagnostic
## Installation 
Python 3.8 is used in this project 
The code should run with no issues using Python versions 3.* <br /> 
There should be nnecessary libraries to run the code here beyond the Anaconda distribution of Python <br /> 
## Motivation 
October is Breast Cancer Awareness Month, people all over the world show their support for everyone affected by breast cancer. I choose to Analyze the Breast Cancer Wisconsin (Diagnostic) Data Set for my Data Scientist Nano-degree project using CRISP-DM process.
## CRISP-DM process
- Busnisse understanding <br /> 
I used the Breast Cancer Wisconsin (Diagnostic) Data Set to answer 3 questions <br /> 
Question 1: How many patients are daignosied with Benign tumors or Malignant tumors? <br /> 
Question 2: which varibles have an influnce in the target varible "diagnosis" <br /> 
Question 3 : predicts whether the cancer is benign or malignant using LinearRegression <br /> 
- Data Understanding  <br /> 
The diagnosis coulmn <Targit varible> have two values M\B  <br /> 
  * What are B and M  <br /> 
Tumors can be Benign (noncancerous) or Malignant (cancerous). <br /> 
Benign tumors tend to grow slowly and do not spread. <br /> 
Malignant tumors can grow rapidly, invade and destroy nearby normal tissues, and spread throughout the body <br /> 
<img width="552" alt="Screen Shot 2021-11-06 at 1 41 13 AM" src="https://user-images.githubusercontent.com/84443038/140586246-92d4dfa3-36b4-415e-84d9-1ef92ab9b15b.png"> 
There is unfortunately 212 patients has been diagnosed with cancerous tumor 'Malignant' and 357 has been diagnosed with noncancerous tumor 'Benign'<br /> </ol>
<img width="694" alt="Screen Shot 2021-11-06 at 1 58 22 AM" src="https://user-images.githubusercontent.com/84443038/140587298-dbe38553-8726-4318-96d4-1d6c4c5a5bfc.png">
From the heatmap we can see the columns that have a positive influence on the diagnosis column
 <li> Prepare Data</li> 
 <ul>
 <li> There was no null nor duplicated values in the data set to deal with </li> 
 <li> The diagnosis coulmns is an object type I changed it into a numerical type becuse it is our target variable </li> 
 </ul>
 <li> Data Modeling</li> 
 <ul>
 </li> Logistic regression is a statistical model used predicts whether the cancer is benign or malignant </li>
 </ul>
  <li> Evaluate the Results</li> 
The Logistic Regression model is predicting with 96% accuracy on our test data
## File Descriptions
jupytor: There is one notebooks available here to showcase work related to the above questions, The notebook structured using CRISP-DM process. <br /> 
Csv: The Breast Cancer Wisconsin (Diagnostic) Data Set  <br /> 
##  Acknowledgments
### Data set
Breast Cancer Wisconsin (Diagnostic) Data Set
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data 
## Breast Cancer Diagnostics project blog post 
https://medium.com/@hannan.alsufyani/breast-cancer-diagnostics-project-3758c7b6d150 

