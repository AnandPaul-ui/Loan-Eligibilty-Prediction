# Loan Eligibility Prediction

## Overview
The Loan Eligibility Prediction system is a machine learning-based application designed to assess whether an applicant qualifies for a loan based on various financial and demographic attributes. It utilizes historical data to train a predictive model, providing a quick and efficient decision-making process for financial institutions.

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and normalizes numerical features.
- **Model Training**: Uses machine learning algorithms like Logistic Regression, Decision Trees, Random Forest, and XGBoost.
- **Prediction**: Determines loan eligibility based on user-provided input.
- **Web Interface**: A simple UI built with Flask to allow users to input details and receive predictions.

## Tech Stack
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Flask
- **Modeling**: Logistic Regression, Decision Trees, Random Forest, XGBoost
- **Deployment**: Flask for web-based interaction

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-eligibility-prediction.git
   cd loan-eligibility-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```
4. Open your browser and visit:
   ```
   http://127.0.0.1:5000
   ```

## Dataset
The dataset contains features such as:
- **Applicant Income**
- **Coapplicant Income**
- **Loan Amount**
- **Loan Amount Term**
- **Credit History**
- **Property Area** (Urban, Rural, Semi-urban)
- **Marital Status**
- **Education**

## Model Performance
The trained model achieved:
- **Accuracy**: 85% (varies depending on the model used)
- **Precision & Recall**: Evaluated using cross-validation
- **Confusion Matrix**: Used for performance assessment

## Usage
1. **Input Data**: Provide loan-related information via the web form.
2. **Predict**: Click on the submit button to get the eligibility result.
3. **Interpret Result**: The model will return "Eligible" or "Not Eligible."

## Contributing
Feel free to fork the repository and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.
