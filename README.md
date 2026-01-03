# Customer Churn Prediction App

Predict whether a bank customer is likely to churn using a trained Artificial Neural Network (ANN) model. This project demonstrates how machine learning can help banks identify at-risk customers and take action to retain them.
<img width="1724" height="893" alt="image" src="https://github.com/user-attachments/assets/e80c8978-2ec0-47cf-bdc1-533808d931aa" />

**Try it live online:** https://huggingface.co/spaces/kinteh/ANN-CLassification1

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Demo](#demo)
- [Author](#author)

---

## Project Overview

Customer churn is when customers stop using a company's service. In banking, high churn rates can significantly affect revenue. This project uses an **Artificial Neural Network (ANN)** to predict the likelihood of a customer leaving a bank.  

The model is trained on historical customer data, including features such as:
- Demographics (age, gender, geography)
- Account information (balance, credit score, tenure)
- Product usage (number of products, credit card ownership, active membership)
- Estimated salary

The **Streamlit app** allows users to input customer details and immediately see a churn probability along with a clear prediction.

---
## Features

- Interactive input for customer details
- Real-time churn probability prediction
- Clear output: “Likely to churn” or “Not likely to churn”
- User-friendly interface for non-technical users

## Installation

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/mlkinteh2/ANN-classification.git
cd ANN-classification

python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows
pip install -r requirements.txt
streamlit run src/app.py
---
## Author
Modou Lamin Kinteh
LinkedIn: https://www.linkedin.com/in/mlkinteh/
