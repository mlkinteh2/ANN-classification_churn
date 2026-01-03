# Customer Churn Prediction App

Predict whether a bank customer is likely to churn using a trained **Artificial Neural Network (ANN)** model. This project demonstrates how machine learning can help banks identify at-risk customers and take action to retain them.

<img width="1724" height="893" alt="image" src="https://github.com/user-attachments/assets/e80c8978-2ec0-47cf-bdc1-533808d931aa" />

**Try it live online:** [Hugging Face Space](https://huggingface.co/spaces/kinteh/ANN-CLassification1)

---

## Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Project Structure](#project-structure)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [Author](#author)

---

## Project Overview

Customer churn occurs when clients stop using a company's services. In banking, high churn rates can significantly affect revenue. This project uses an **ANN** to predict the likelihood of a customer leaving a bank.

The model is trained on historical customer data, including features such as:

* Demographics: age, gender, geography
* Account information: balance, credit score, tenure
* Product usage: number of products, credit card ownership, active membership
* Estimated salary

The **Streamlit app** allows users to input customer details and see the churn probability in real time, along with a clear prediction.

---

## Features

* Interactive input for customer details
* Real-time churn probability prediction
* Clear output: “Likely to churn” or “Not likely to churn”
* User-friendly interface for non-technical users

---

## Project Structure

```
ANN-classification/
│
├── src/
│   ├── app.py
│   ├── model.h5
│   ├── scaler.pkl
│   ├── label_encoder_gender.pkl
│   ├── onehot_encoder_geo.pkl
│
├── requirements.txt
├── README.md
```

---

## Installation

To run this project locally:

1. Clone the repository:

```bash
git clone https://github.com/mlkinteh2/ANN-classification.git
cd ANN-classification
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Streamlit app:

```bash
streamlit run src/app.py
```

---

## Usage

* Open the app in your browser
* Enter customer details in the form
* View the churn probability and prediction

---

## Technologies

* Python
* TensorFlow / Keras
* Pandas, NumPy, Scikit-learn
* Streamlit for the web interface

---

## Author

**Modou Lamin Kinteh**
LinkedIn: [https://www.linkedin.com/in/mlkinteh/](https://www.linkedin.com/in/mlkinteh/)

---


