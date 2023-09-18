### DRUG_CLASSIFICATION
### GOAL

This project aims to classify drugs based on patient characteristics such as age, sex, blood pressure (BP), cholesterol level, and sodium-to-potassium ratio (Na_to_K). We employ various machine learning algorithms and techniques to achieve accurate drug classification.

### DATASET

The dataset used for this project is available in CSV format with 200 rows and 6 columns
The dataset used in this project contains the following columns:
- `Age`: Age of the patient.
- `Sex`: Gender of the patient.
- `BP`: Blood pressure level.
- `Cholesterol`: Cholesterol level.
- `Na_to_K`: Sodium-to-potassium ratio.
- `Drug`: The target variable representing the prescribed drug.

### INTEL DEVELOPERS CLOUD SERVICE ENV

Here , we used IDC service ; That is Intel® Max Series GPU (PVC) on 4th Gen Intel® Xeon® processors - 1100 series (4x) (Batch Processing/Scheduled access) to make our project to run in pytorch_xpu Environment.



### Intel oneAPI Data Analytics Library (oneDAL)

   Intel® oneAPI Data Analytics Library (oneDAL) is a library that helps speed up big data analysis by providing highly optimized algorithmic building blocks for all stages of data analytics (preprocessing, transformation, analysis, modeling, validation, and decision making) in batch, online, and distributed processing modes of computation.

### ML ALGORITHMS

We have implemented and evaluated the following machine learning algorithms for drug classification:

  (1)KNN
  (2)Random Forest
  (3)Logistic Regression
  (4)SVM
  (5)Naives Bayes
  (6)Adaboost
  (7)Voting Classifier
  (8)Multinomial Logistic Regression
    
### LIBRARIES USED

Pandas: for data analysis
Numpy: for data analysis
Matplotlib: for data visualization
Seaborn: for data visualization
Scikit-learn: for data analysis
Intel oneDAL: for enhanced performance and efficiency

### DISTRIBUTIONS

![Screenshot 2023-09-18 230718](https://github.com/harishraaghavdv/drugclassification/assets/94100274/bf7e833e-c054-461f-8ad5-fe853ce90794)
![Screenshot 2023-09-18 230740](https://github.com/harishraaghavdv/drugclassification/assets/94100274/b2434b87-2bc6-4b1d-9c5d-cc671ed70e47)
![Screenshot 2023-09-18 230753](https://github.com/harishraaghavdv/drugclassification/assets/94100274/bf6615a3-3f74-4a8e-a128-897c12156301)
![Screenshot 2023-09-18 230844](https://github.com/harishraaghavdv/drugclassification/assets/94100274/d78af41a-2892-41ab-aa26-b223d4db5ca3)
![Screenshot 2023-09-18 230858](https://github.com/harishraaghavdv/drugclassification/assets/94100274/8079b359-aed5-4db7-bb39-ea18248279ce)
![Screenshot 2023-09-18 230922](https://github.com/harishraaghavdv/drugclassification/assets/94100274/6ba79303-3747-46f4-b751-b80f26d40dbd)
![Screenshot 2023-09-18 230954](https://github.com/harishraaghavdv/drugclassification/assets/94100274/b7033fd5-988f-45dc-88ac-7c74e2013e38)
![Screenshot 2023-09-18 231024](https://github.com/harishraaghavdv/drugclassification/assets/94100274/d8844e4d-012c-40fd-bd9e-e3f3f9ebcdf9)


### GRID SEARCH

"Grid search" is a hyperparameter optimization technique used in machine learning to systematically search for the best combination of hyperparameter values for a given model have been used. Hyperparameters are parameters that are not learned from the data but are set prior to training a machine learning model. 

### ACCURACIES
![image](https://github.com/harishraaghavdv/drugclassification/assets/94100274/6002d5eb-459b-4cc7-b0b9-ac6b9b08d414)



### RESULTS

We have evaluated each algorithm's performance and included the results in the Jupyter Notebook files , which we run through IDC Environment and also by the Grid Search we got our best tuning parameters.
