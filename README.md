# ❤️ Heart Disease Prediction Project

This project aims to predict the presence of heart disease in patients using machine learning models. The system is trained on a publicly available dataset, and the final model is deployed through an interactive Streamlit web app.

## 📁 Project Structure

Heart_Disease_Project/
│
├── data/ # Contains raw and cleaned datasets
├── notebooks/ # Jupyter notebooks for analysis and modeling
│ ├── 1_preprocessing.ipynb
│ ├── 2_feature_selection.ipynb
│ ├── 3_supervised_learning.ipynb
│ ├── 4_unsupervised_learning.ipynb
│ └── 5_hyperparameter_tuning.ipynb
├── models/ # Saved models (e.g., final_model.pkl)
├── streamlit_app/ # Streamlit app files
│ └── app.py
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## 📊 Dataset

- **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Target:** Multi-class classification (`0` = no disease to `4` = severe)

### Selected Features:
- `age`
- `sex`
- `cp` (chest pain type)
- `trestbps` (resting blood pressure)
- `chol` (cholesterol)
- `thalach` (max heart rate)
- `oldpeak` (ST depression)
- `fbs` (fasting blood sugar)
- `exang` (exercise-induced angina)

## ⚙️ Models Used

- Logistic Regression  
- Decision Tree  
- Random Forest (**Final Model**)  
- KMeans (Unsupervised for EDA)

### Evaluation Metrics:
- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- Cross-validation

## 🧪 Feature Selection

Feature importance and correlation heatmaps were used to select top predictive features.

## 🚀 Streamlit App

The final model is deployed in a user-friendly web interface using Streamlit.

### How to Run:

1. Clone the repository:
git clone https://github.com/Esraa-eng422/Heart_Disease_Project.git
cd Heart_Disease_Project/streamlit_app

2.Install dependencies:


pip install -r ../requirements.txt

3.Run the app:

streamlit run app.py
✅ Requirements
Python 3.8+

pandas

numpy

scikit-learn

streamlit

matplotlib

seaborn

Install all dependencies using:




pip install -r requirements.txt
👤 Author
Esraa Ali Mahmoud Elsayed Abu Elkhir

GitHub: Esraa-eng422

Email: esraaabuelkhir@gmail.com

LinkedIn: Esraa's Profile

📌 License
This project is open-source and available under the MIT License.

🌟 Acknowledgments
UCI Machine Learning Repository

Scikit-learn and Streamlit teams
