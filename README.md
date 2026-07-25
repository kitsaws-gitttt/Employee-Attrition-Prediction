# Employee Attrition Prediction using Decision Tree and Random Forest


Name : Swastik Sharma

Registration Number : 23BCY10012

Application Number : IN26011866

Batch Code : 1A

Registered Email ID : swastiksharma9000@gmail.com

College Email ID : swastik.23bcy10012@vitbhopal.ac.in

---

## Objective

The objective of this project is to predict whether an employee is likely to leave the organization based on demographic, professional, and work-related attributes. Two machine learning models, Decision Tree and Random Forest, were developed and compared to identify which model provides better prediction performance.

--- 

## Dataset

This project uses the IBM HR Analytics Employee Attrition dataset available on Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

> Note: The dataset is not included in this repository. Please download it from the Kaggle link above.

---

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Explored the dataset by examining its structure, data types, and summary statistics.
3. Checked for missing values and removed unnecessary columns.
4. Encoded categorical variables using Label Encoding.
5. Split the data into training and testing sets using an 80:20 ratio.
6. Built a Decision Tree Classifier.
7. Built a Random Forest Classifier with 100 estimators.
8. Evaluated both models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
9. Visualized feature importance using the Random Forest model.
10. Compared the performance of both models based on the evaluation metrics.

---

## Results

Both models successfully predicted employee attrition. The Random Forest model achieved better overall performance and produced more reliable predictions on the test data compared to the Decision Tree model.

---

## Model Comparison

| **Decision Tree**                                 |                             **Random Forest**                                    | 
| :-----------------------------------------------: | :------------------------------------------------------------------------------: | 
| It is easy to understand and interpret. It trains quickly but is more to overfitting, which may reduce its performance on unseen data. | Provides higher accuracy and better generalization. By combining multiple decision trees, it produces more stable and reliable predictions while reducing the risk of overfitting.|


---

## Conclusion

The Random Forest classifier outperformed the Decision Tree classifier across the evaluation metrics. By combining the predictions of multiple trees, it reduced overfitting and improved overall prediction accuracy. Although Decision Trees are simple to interpret, they are more sensitive to variations in the training data. Random Forest requires more computation but provides more dependable results, making it the preferred model for this employee attrition prediction task.
