**SmartLender - Loan Approval Prediction System**

**Overview**

SmartLender is a Machine Learning-based web application that predicts whether a loan application is likely to be approved or rejected based on applicant information. The system helps simplify and accelerate the loan evaluation process by providing instant predictions through an easy-to-use web interface.

**Features**

- User-friendly web interface
- Secure Admin Login
- Loan approval prediction using Machine Learning
- Real-time prediction results
- Responsive design
- Data preprocessing using encoding and scaling
- Flask-based backend integration

**Technologies Used**

**Frontend**

- HTML5
- CSS3
- JavaScript

**Backend**

- Python
- Flask

**Machine Learning**

- Scikit-learn
- Pandas
- NumPy
- Joblib / Pickle

**Project Structure**

SmartLender/
│── app.py
│── requirements.txt
│── README.md
│── models/
│   ├── loan_model.pkl
│   ├── scaler.pkl
│   └── encoder.pkl
│── templates/
│   ├── index.html
│   ├── login.html
│   ├── dashboard.html
│   ├── predict.html
│   └── result.html
│── static/
│   ├── css/
│   ├── js/
│   └── images/
│── dataset/
│── notebooks/

**Workflow**

1. User opens the SmartLender application.
2. Admin can log in securely through the Admin Login page.
3. User enters loan applicant details.
4. The Flask backend receives the input data.
5. Data is preprocessed using the saved scaler and encoder.
6. The trained Machine Learning model predicts the loan status.
7. The application displays whether the loan is Approved or Rejected.

**Input Features**

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

**Installation**

1. Clone the repository:

git clone https://github.com/jyothiradhitya-tech/smart-leader_wed

2. Navigate to the project folder:

cd SmartLender

3. Install the required packages:

pip install -r requirements.txt

4. Run the Flask application:

python app.py

5. Open your browser and visit:

http://127.0.0.1:5000/

**Future Enhancements**

- User authentication
- Loan history management
- Database integration
- Explainable AI for prediction insights
- Cloud deployment
- Email and SMS notifications

**Authors**

Nali Jothiradhitya &

Akula Padmanayani

B.Tech (CSE - Artificial Intelligence)

**License**

This project is developed for educational and learning purposes.
