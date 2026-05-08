# Student Marks Prediction Flask App

This project is a simple Machine Learning web application built using Flask.  
The application predicts student marks based on study hours using a trained Linear Regression model.

---

# 📌 Project Overview

The user enters study hours through a web form, and the application predicts the expected marks using a pre-trained machine learning model stored in a `.pkl` file.

The project demonstrates:
- Flask integration with Machine Learning
- Model deployment
- Form handling
- Prediction using trained model
- Saving prediction data into CSV

---

# 🛠 Technologies Used

- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- HTML
- joblib

---

project structure

Flask_App/
│
├── app.py
├── Desktop.pkl
├── smp_data_from_app.csv
│
├── templates/
│ └── index.html
│
└── README.md


---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone <your-github-repository-link>
2. Move into Project Folder
cd Flask_App
3. Install Required Libraries
pip install flask numpy pandas scikit-learn joblib
▶️ Run the Application
python app.py

After running, open browser:



http://127.0.0.1:5000/



