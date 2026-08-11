
# 🏦 Loan Approval Prediction Using Java

## 📌 Overview

Loan Approval Prediction is a machine learning-based project that predicts whether a loan application is likely to be approved or rejected based on applicant financial and personal information.

The project is implemented in Java and demonstrates the use of classification techniques for financial decision-support.

## 🎯 Objectives

* Predict loan approval status.
* Analyze applicant income and loan amount.
* Consider credit history during prediction.
* Demonstrate classification using Java.
* Provide a simple and easy-to-use prediction system.

## ✨ Features

* Applicant income analysis
* Co-applicant income analysis
* Loan amount analysis
* Credit history evaluation
* Education information
* Property area information
* Loan approval/rejection prediction
* Console-based simulation

## 🛠️ Technologies Used

* Java
* Object-Oriented Programming
* Classification
* Machine Learning Concepts
* Git
* GitHub
* VS Code / IntelliJ IDEA / Eclipse

## 📂 Project Structure

```text
Loan-Approval-Prediction/
│
├── src/
│   └── LoanApprovalPrediction.java
│
├── data/
│   └── loan_data.csv
│
├── output/
│   └── sample_output.txt
│
└── README.md
```

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Loan-Approval-Prediction.git
```

### 2. Open the project

Open the project in VS Code, IntelliJ IDEA, or Eclipse.

### 3. Compile

```bash
javac src/LoanApprovalPrediction.java
```

### 4. Run

```bash
java -cp src LoanApprovalPrediction
```

## 🧪 Sample Simulation

### Input

```text
Applicant Income: 6000
Co-Applicant Income: 2000
Loan Amount: 200
Credit History: 1
Education: 1
Property Area: 2
```

### Output

```text
Training dataset loaded.
Training records: 10

Final Decision: LOAN APPROVED

Reason: Applicant has suitable income and credit history.
```

## 📊 Example Rejected Application

```text
Applicant Income: 2500
Co-Applicant Income: 500
Loan Amount: 200
Credit History: 0
Education: 0
Property Area: 0
```

Output:

```text
Final Decision: LOAN REJECTED

Reason: Income/loan ratio or credit history is insufficient.
```

## 💡 Applications

* Banking systems
* Financial institutions
* Loan screening
* Credit risk analysis
* Financial decision-support systems
* Educational machine learning projects

## 🚀 Future Improvements

* Use a real-world loan dataset.
* Implement an actual Decision Tree or Random Forest model.
* Add accuracy, precision, recall, and F1-score.
* Create a JavaFX/Swing graphical interface.
* Add MySQL database integration.
* Develop a Spring Boot web application.
* Add explainable AI for prediction decisions.
* Deploy the application as a web service.

## ⚠️ Disclaimer

This project is intended for educational and demonstration purposes. A real banking system should use validated financial models, appropriate regulatory controls, secure data handling, fairness testing, and human review.

## 👩‍💻 Author

**Aswitha Konda**

B.Tech – Artificial Intelligence and Data Science

---

⭐ If you found this project useful, consider giving the repository a star!
