# Student Maths Marks Predictor

A fully implemented end-to-end machine learning project designed to analyze student performance data and predict mathematics marks using structured statistical and ML techniques. This project demonstrates the ability to handle real-world data workflows, build reliable predictive models, and present results in a clean, deployment-ready format — making it suitable for resumes, interviews, and portfolio showcases.

---

## 🔍 Project Summary

This project focuses on identifying key factors affecting students' academic performance and building a regression-based model to predict maths scores. It highlights practical experience with data preprocessing, feature engineering, model selection, evaluation, and integration into an interactive prediction interface.

---

## 💼 Key Responsibilities & Contributions

* Developed an **end-to-end ML pipeline** covering data ingestion, cleaning, EDA, model development, optimization, and deployment.
* Conducted **in-depth Exploratory Data Analysis** to uncover insights and correlations influencing student outcomes.
* Evaluated multiple regression algorithms and implemented the best-performing model with tuned hyperparameters.
* Engineered reusable and modular code under the `src/` directory, improving maintainability and scalability.
* Built an optional **flask-based prediction app** for real-time score prediction using trained models.

---

## 🛠 Tech Stack

**Languages:** Python 3.x
**Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
**Tools:** Jupyter Notebook, VS Code, Git
**Deployment:** Flask

---

# ☁️ **AWS Deployment**

This project is deployed on **AWS Elastic Beanstalk**, demonstrating:

* Ability to containerize and package ML applications for cloud environments
* Configuration of Elastic Beanstalk environments (Python platform)
* Handling environment variables, WSGI setup, and application configuration
* Deploying updates and managing versions
* Using AWS services for scalable, production-ready ML apps


## ⚙️ How to Run

### 1. Install dependencies and clone project

```
git clone https://github.com/abhinav7876/Student-Marks-Predictor-Data-Science.git
conda create -p venv python==3.10 -y
conda activate venv/
pip install -r requirements.txt
```

### 2. Launch the prediction app

```
python app.py
```
open up localhost:
http://127.0.0.1:8080/predictdata
---

## 📈 Results & Insights

Key insights derived from the dataset:

- Student's Performance is related with lunch, race, parental level education
- Females lead in pass percentage and also are top-scorers
- Student's Performance is not much related with test preparation course
- Finishing preparation course is benefitial.

---

![alt text](image-1.png)

![alt text](<Screenshot 2025-11-13 065332.png>)
