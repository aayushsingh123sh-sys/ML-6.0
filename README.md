🚢 Titanic Survival Prediction App
A streamlined web application built with Streamlit that uses Logistic Regression to predict passenger survival based on the famous Titanic dataset.

🚀 Features
CSV Upload: Upload any Titanic-formatted dataset.

Automated Preprocessing: Handles missing values for Age and Fare, drops rows with missing Embarked data, and performs One-Hot Encoding for categorical variables.

Feature Scaling: Uses StandardScaler to normalize numerical data for better model performance.

Real-time Evaluation: Trains a Logistic Regression model on the fly and displays the accuracy score.

🛠️ Installation & Setup
Clone the repository (or navigate to your project folder):

Bash
git clone <your-repo-url>
cd titanic-survival-app
Install dependencies:
Make sure you have Python installed, then run:

Bash
pip install -r requirements.txt
Run the application:

Bash
streamlit run app.py
📊 Dataset Requirements
The application expects a .csv file with the following standard Titanic columns:

Survived (Target variable)

Pclass, Age, SibSp, Parch, Fare, Sex, and Embarked

🧠 Model Architecture
The app utilizes a Logistic Regression classifier. This is a linear model used for binary classification (Survived vs. Not Survived).
