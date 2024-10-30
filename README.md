# **Titanic Survival Classification**

This project aims to predict the survival of passengers aboard the Titanic using various machine learning models. The classification techniques used include Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Gaussian Naive Bayes. The project leverages popular libraries such as Pandas, NumPy, and Matplotlib for data manipulation, numerical operations, and data visualization.

## **Table of Contents**

- [Introduction](#introduction)
- [Data Overview](#data-overview)
- [Models and Accuracy](#models-and-accuracy)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
  
## **Introduction**

The Titanic was a British passenger liner that sank in the North Atlantic Ocean in 1912 after hitting an iceberg. This tragic event resulted in the loss of over 1,500 lives. This project seeks to analyze the data from the Titanic disaster to create predictive models that classify whether a passenger survived based on various features.

## **Data Overview**

The dataset used in this project is the Titanic dataset, which includes the following features:

- **PassengerId**
- **Pclass** (Passenger Class)
- **Name**
- **Sex**
- **Age**
- **SibSp** (Siblings/Spouses Aboard)
- **Parch** (Parents/Children Aboard)
- **Ticket**
- **Fare**
- **Cabin**
- **Embarked** (Port of Embarkation)

## **Models and Accuracy**

The following models were implemented for classification, along with their respective accuracies:

- **Logistic Regression:** 77%
- **Support Vector Machine (SVM):** 76%
- **K-Nearest Neighbors (KNN):** 69%
- **Gaussian Naive Bayes:** 76%

## **Installation**

To run this project, you'll need to have Python installed on your machine. You can install the required libraries using pip:


pip install pandas numpy matplotlib scikit-learn


## **Usage**
Clone the repository:


git clone https://github.com/yourusername/titanic-classification.git
Navigate to the project directory:


cd titanic-classification
Run the main script:


python titanic_classification.py
Visualize results and analysis through the generated plots.

## **Contributing**
Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.
