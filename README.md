# 🎓 Student Performance Prediction in Azure Deployment

This repository contains a **Machine Learning project** focused on predicting **student performance** using **Azure Cloud Deployment**. The project involves building a custom **ML library**, deploying it in **Azure**, and automating the prediction workflow. It covers the entire pipeline, from **data collection and cleaning** to **model selection and deployment**.

---

## 🚀 Project Overview
This project leverages **machine learning** to analyze student data and predict academic performance. The pipeline follows structured steps including **data preprocessing, feature engineering, model selection, and cloud deployment**. A custom **Python library** is developed for modular and reusable ML processing, which is then deployed on **Azure** for scalable inference.

---

## 🏗️ Project Workflow

![Workflow Diagram](https://github.com/user-attachments/assets/sample_workflow.png)

1. **Data Collection** 📊  
   - Gathered student performance data from public datasets and school records.  
   - Data stored in **Azure Blob Storage** for easy access and scalability.

2. **Data Preparation & Cleaning** 🔧  
   - Handled missing values and outliers using **Pandas & NumPy**.  
   - Applied **label encoding** for categorical features.  
   - Performed **feature scaling & normalization** for better model accuracy.

3. **Exploratory Data Analysis (EDA)** 📈  
   - Visualized trends and correlations using **Matplotlib & Seaborn**.  
   - Identified key factors influencing student performance.

4. **Feature Engineering** 🛠️  
   - Extracted meaningful insights using **domain knowledge**.  
   - Created new features such as study hours, attendance rates, and parental involvement scores.

5. **Model Selection & Training** 🤖  
   - Experimented with **Linear Regression, Random Forest, and XGBoost**.  
   - Tuned hyperparameters using **GridSearchCV** for optimal performance.  
   - Selected the best model based on **RMSE and accuracy metrics**.

6. **Custom ML Library Development** 📦  
   - Created a **Python library** (`student_perf_ml`) for modular ML processing.  
   - Includes data preprocessing, model training, evaluation, and prediction functions.  
   - Packaged using `setuptools` and deployed as a **pip-installable library**.

7. **Azure Deployment** ☁️  
   - **Containerized** the ML model using **Docker**.  
   - Deployed using **Azure Machine Learning Service (Azure ML)** for scalable inference.  
   - Exposed an **API endpoint** using **Azure Functions** for real-time predictions.

8. **Model Monitoring & Optimization** 🧐  
   - Integrated **Azure Monitor** for tracking model performance.  
   - Set up **automated retraining** based on data drift and new student records.  

---

## 📌 Technologies Used
- **Programming:** Python, SQL  
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, FastAPI  
- **ML Models:** Linear Regression, Random Forest, XGBoost  
- **Cloud Services:** Azure Machine Learning, Azure Blob Storage, Azure Functions  
- **Deployment Tools:** Docker, Kubernetes, GitHub Actions  

---

## 🎯 Results & Key Insights
- Successfully built and deployed an **ML model on Azure** to predict student performance.  
- Developed a **custom Python ML library** for modular and reusable ML processing.  
- Achieved **high prediction accuracy**, helping educators **identify at-risk students early**.  
- Integrated **monitoring and retraining strategies** to improve model performance over time.  

---

## 🚀 How to Use This Project

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/student-performance-azure.git
   cd student-performance-azure
