# Employee Salary Prediction Web App 💼💸

An interactive **Streamlit web application** that predicts whether an employee's annual income exceeds $50,000 based on demographic and professional data using a machine learning classification model.

---

## 🚀 Project Overview

This project demonstrates a complete machine learning pipeline — from data preprocessing to model deployment — applied to salary classification. Users can enter employee details through a friendly UI or upload batch CSV files to get salary bracket predictions instantly.

The app leverages an optimized model combining feature encoding and classification, wrapped in an intuitive Streamlit interface with a modern dark theme for an enhanced user experience.

---

## 🔍 Features

- Predict employee salary class (<=50K or >50K) using individual inputs.
- Batch prediction using CSV file uploads.
- Real-time results with clear visual feedback.
- Modern dark-themed UI styled via custom CSS.
- Utilizes a trained pipeline combining preprocessing and model.
- Easy-to-run locally with minimal setup.

---

## 📂 Repository Structure

| File/Folder            | Description                                      |
|-----------------------|--------------------------------------------------|
| `app.py`              | Main Streamlit app code handling UI and prediction logic. |
| `best_model_pipeline.pkl` | Serialized trained machine learning pipeline.        |
| `label_encoders.pkl`  | Saved label encoders for categorical features.   |
| `income_encoder.pkl`  | Encoder for salary class labels.                   |
| `custom_styles.css`   | Custom CSS to style the Streamlit app with dark theme. |

---

## 🎯 How to Run Locally

### Prerequisites

- Python 3.8 or higher
- Streamlit
- Packages: pandas, numpy, scikit-learn, joblib

### Installation & Setup

1. Clone this repository.
2. (Recommended) Create and activate a virtual environment:
3. Install dependencies:
4. Ensure these files are in the project directory:
- `best_model_pipeline.pkl`
- `label_encoders.pkl`
- `income_encoder.pkl`
- `custom_styles.css`
5. Run the Streamlit app:

---

## 🧩 Usage

- **Predictor Tab:** Fill in employee details (age, workclass, education, etc.) and click "Predict Salary Class" to see the estimated income bracket.
- **Batch Prediction:** *(if implemented)* Upload a CSV file with employee data to predict salary class for multiple entries at once.
- View predictions in real-time with color-coded results on the interface.

---

## 📊 Dataset & Preprocessing

- The model was trained on a variation of the **UCI Adult Income Dataset (`adult 3.csv`)**.
- Data cleaning steps include replacing missing values, removing irrelevant rows, and filtering outliers.
- Categorical columns were encoded with label encoders to make data machine-readable.
- Features used: age, workclass, fnlwgt, education-num, marital-status, occupation, relationship, race, gender, capital-gain, capital-loss, hours-per-week, native-country.

---

## 🔧 Model Details

- Multiple classifiers were evaluated: Logistic Regression, Random Forest, KNN, SVM, Gradient Boosting.
- Best performing model saved as a pipeline with preprocessing and scaling.
- Model predicts binary salary class (`<=50K` or `>50K`).
- Model files are loaded at app startup for instant prediction.

---

## 🎨 UI & Styling

- Custom CSS (`custom_styles.css`) applies a sleek dark theme with smooth typography and widget adjustments.
- Background image (`background.jpg`) with a dark overlay creates an elegant look.
- Responsive layout with sidebar navigation between Predictor and About sections.

---

## 📈 Results & Impact

- Provides HR teams and analysts with an automated tool for salary bracket estimation.
- Facilitates transparency and data-driven decisions in compensation management.
- Extensible framework for integrating more advanced models or real-time data sources.

---

## 🔮 Future Enhancements

- Integration of real-time HR datasets for continuous learning.
- Expand feature set with additional attributes like job location, performance scores.
- Cloud deployment with API access for scalable usage.
- Cross-platform support including mobile and multilingual UI.

---

## 🙏 Acknowledgments

Thanks to:

- The UCI Machine Learning Repository for the Adult Income dataset.
- Streamlit for enabling rapid web app development.
- Libraries: Scikit-learn, pandas, numpy, joblib for the machine learning pipeline.

---

## 📄 License

This project is licensed under the MIT License.

---

> **Contact:** Namneet Dash | Department of Computer Science and Engineering | Trident Academy of Technology  
> GitHub: [https://github.com/code2104-sys/Employee_Salary_Predictor](https://github.com/code2104-sys/Employee_Salary_Predictor)

