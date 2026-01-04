Rock vs Mine Prediction using SONAR Data
📌 About the Project

SONAR (Sound Navigation and Ranging) technology plays a crucial role in detecting underwater objects such as rocks and mines, which are otherwise difficult to identify. This project leverages Machine Learning techniques to classify underwater objects as either Rock or Mine based on SONAR signal data.

The project demonstrates how predictive analytics can be applied using a Logistic Regression model to solve a real-world binary classification problem. The implementation is carried out using Python in Google Colab.

📊 Dataset

Source: UCI Machine Learning Repository

Total Samples: 209

Total Features: 61

60 numerical features representing SONAR signal energy at different frequencies

1 target label indicating:

R → Rock

M → Mine

The dataset is included in this repository and is used for both training and testing the model.

⚙️ Model Used
Logistic Regression

Logistic Regression is a statistical model used for binary classification problems. It uses a sigmoid (logit) function that maps input values to a range between 0 and 1, making it ideal for probability-based predictions.

Why Logistic Regression?

Suitable for binary outcomes (Rock or Mine)

Simple and interpretable

Efficient for small-to-medium-sized datasets

Reduces the impact of outliers using the sigmoid function

🧪 Project Workflow

Load SONAR dataset from CSV file

Perform data preprocessing:

Label encoding

Feature scaling

Split dataset into training and testing sets

Train the Logistic Regression model using training data

Predict object type using test data

Evaluate model performance using accuracy and predictions

🛠️ Technologies & Tools

Python

NumPy

Pandas

Scikit-learn

Google Colab

📈 Results

The trained Logistic Regression model is capable of accurately predicting whether an underwater object is a Rock or a Mine based on SONAR signal data.

📚 Lessons Learned

Understanding of Logistic Regression and its use in binary classification

Hands-on experience with data preprocessing

Practical usage of Python libraries such as:

NumPy

Pandas

Scikit-learn

Model training, testing, and evaluation

Gained foundational knowledge of Machine Learning workflows

🚀 Future Improvements

Experiment with advanced models like SVM or Random Forest

Perform hyperparameter tuning

Improve evaluation using precision, recall, and confusion matrix

Deploy the model using a simple web interface

📎 How to Run

Open the notebook in Google Colab

Upload the dataset (if not already present)

Run all cells sequentially

Modify input values to test new predictions

⭐ This project marks my first step into Machine Learning and helped me build a strong foundation in classification models and data-driven decision making.
