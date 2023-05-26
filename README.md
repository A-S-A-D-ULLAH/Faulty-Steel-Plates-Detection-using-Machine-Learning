# Faulty-Steel-Plates-Detection-using-Machine-Learning
## Introduction
The objective of this report is to provide an overview and analysis of the project "Faulty Steel Plates Detection using Machine Learning." The project focuses on utilizing machine learning algorithms to analyze the impact of various factors on defects in stainless-steel plates. The factors considered include luminosity, sigmoid of areas, pastry, stains, dirtiness, and bumps. The report will outline the applied algorithms, namely Random Forest, Decision Tree, Support Vector Machine (SVC), and k-Nearest Neighbors (KNN), and discuss their effectiveness in achieving the project's objectives.

## Methodology
### Data Collection and Preprocessing
The project began by collecting a dataset of stainless-steel plates with corresponding labels indicating the presence or absence of defects. The dataset was preprocessed to handle missing values, outliers, and any other data inconsistencies. Feature engineering techniques were employed to extract relevant features from the data, including luminosity, sigmoid of areas, pastry, stains, dirtiness, and bumps.
<p align="center">
  <img src="/Fiqures/111.jpg" align="center" width="900" height="450">
</p>


### Algorithm Selection and Implementation
The project employed four machine learning algorithms for defect detection: Random Forest, Decision Tree, SVC, and KNN. Each algorithm was implemented using appropriate libraries and frameworks such as scikit-learn in Python. The algorithms were trained on the preprocessed dataset to learn the relationships between the input features and the presence of defects.

<p align="center">
  <img src="/Fiqures/2.png" align="center" >
</p>

## Results and Discussion
### Random Forest
The Random Forest algorithm demonstrated high accuracy in detecting faulty steel plates. It leveraged the ensemble learning technique by combining multiple decision trees, which allowed for robust feature importance rankings. The algorithm successfully captured the complex relationships between the input features and defects, resulting in accurate predictions. The model achieved Training accuracy of 93% and testing is 80%.
<p align="center">
  <img src="/Fiqures/3.png" align="center" >
</p>

### Decision Tree
Decision Tree algorithm, although simpler compared to Random Forest, exhibited satisfactory performance in detecting defects. Its ability to create a tree-like model of decisions and consequences enabled interpretable insights into the impact of various factors on steel plate defects. The model achieved Training accuracy of 93% and testing is 79%.
<p align="center">
  <img src="/Fiqures/4.png" align="center" >
</p>

### SVM
Support Vector Machines (SVM) showed promising results in detecting faulty steel plates. By finding an optimal hyperplane to separate different classes, it effectively distinguished between defective and non-defective plates. However, SVM's computational complexity may pose limitations for larger datasets.The model achieved Training accuracy of 100% and testing is 76%.
<p align="center">
  <img src="/Fiqures/5.png" align="center" >
</p>

### KNN
k-Nearest Neighbors (KNN) algorithm provided reasonable accuracy in detecting faulty steel plates. By classifying new data points based on their proximity to labeled data points, it proved to be a straightforward and easy-to-implement approach.The model achieved Training accuracy of 79% and testing is 73%.
<p align="center">
  <img src="/Fiqures/6.png" align="center" >
</p>
