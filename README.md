# Heart Disease Classification
Heart disease is a prevalent and potentially life-threatening condition that affects millions of people worldwide. Early detection and accurate classification of heart disease play a crucial role in providing timely medical intervention and improving patient outcomes. Machine learning techniques offer powerful tools for analyzing complex datasets and predicting heart disease based on various risk factors and clinical indicators.

This project aims to leverage Support Vector Machine (SVM) and K-Nearest Neighbor (K-NN) algorithms to develop accurate models for heart disease classification. By examining key features such as age, gender, and medical measurements, these models can assist healthcare professionals in identifying individuals at risk and making informed decisions for effective disease management.

Through data analysis, model evaluation, and visualization, this project provides valuable insights into the factors contributing to heart disease and facilitates improved diagnosis and treatment strategies. By harnessing the power of machine learning, this project contributes to advancing medical research and enhancing healthcare practices in the field of cardiology.

## Dataset
The dataset used in this project is in CSV format and contains the following columns:

![image](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/76724024-58e7-4b38-a741-ddc2d34d0398)

## Prerequisites

Before running the code, make sure you have the following libraries installed:
* Python 3
* Jupyter Notebook (optional, for running the provided code)
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
   * preprocessing
   * model_selection
   * svm
   * metrics
   * neighbors
   * decomposition
   * datasets
   * ensemble

You can install these libraries using the following command:

```shell
pip install numpy pandas matplotlib seaborn scikit-learn
```
## Usage
1. Clone the repository and navigate to the project directory.
```shell
git clone https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML
```
2. Run the provided code in a Jupyter Notebook or any Python environment.
3. Make sure the dataset file "heart.csv" is in the same directory as the code file.
4. Adjust the code or parameters as needed for customization.
5. Execute the code and observe the results.

## Steps
* Import the necessary libraries and modules.
* Load the dataset from the "heart.csv" file.
* Preprocess the dataset by splitting it into independent variables (X) and the target variable (y), and perform any required data transformations.
* Split the dataset into training and test sets.
* Apply feature scaling if necessary.
* Create the SVM model and train it on the training set.
* Make predictions on the test set using the trained SVM model.
* Evaluate the performance of the SVM model using accuracy and the confusion matrix.
* Repeat steps 6-8 for the K-NN algorithm.
* Visualize the results using appropriate plots and analytics.
* Interpret the results and draw conclusions.

## Results
The project aims to achieve accurate classification of heart disease based on the provided dataset. The results include the accuracy of the SVM and K-NN models, as well as the confusion matrix showing the true positive, true negative, false positive, and false negative predictions. These results can be used to evaluate the performance of the models and assess their effectiveness in heart disease classification.

## Analytics
Analytics and insights from the project can include:

* Creating the Model

![download](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/9ba5b405-8938-407c-bcf1-44b8a9804f12)

* Using K-Nearest Neighbor Classifier (K-NN)

![download (1)](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/f04fa11e-b833-4202-9f27-8535513ff233)

* Using SVM WITH PCA

![download (2)](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/8853ff9a-b474-47a2-a06f-6b691b8a1762)

* Using KNN with PCA

![download (3)](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/32ec96c2-8e64-4866-8e0a-7ab1c7365061)

* Bar Plot for count of People Diseased and Not Diseased

![download (4)](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/944e3aab-ab72-4081-a08f-49b28b3b7a59)

* Scatter Plot between Age and <max> Heart Rate

![download (5)](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/5d5b3e11-f786-4663-be8d-62417b076cfd)

* Count of Male and Female

![download (6)](https://github.com/viv3k19/heart_Disease_Classification-using-Python-ML/assets/82309435/b8d1a7ca-cf08-4a92-87d2-36f47117c7ab)

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.
