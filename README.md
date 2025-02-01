# Wine Quality Check - End to End Project with Deployment

<img width="397" alt="Input_01" src="https://github.com/user-attachments/assets/2a9b0e66-2908-40c6-9821-1fb8e972d07b" />
<img width="476" alt="Predict_01" src="https://github.com/user-attachments/assets/4574c2c1-3430-4995-93d6-20bd32c6a243" />

## 🚀 Overview
This project implements an end-to-end machine learning pipeline to predict wine quality based on various physicochemical properties. The project follows a robust CI/CD pipeline for automated testing, building, and deployment.

## 📌 Features
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Model training using multiple algorithms
- Model evaluation and selection
- Deployment using Flask/Django
- CI/CD pipeline for automation
- API endpoint for real-time predictions

## 📁 Dataset
The dataset used for this project is the **Wine Quality Dataset**, available on [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).

## 📊 Tech Stack
- **Programming Language:** Python
- **Machine Learning:** Scikit-learn, XGBoost, Random Forest
- **Web Framework:** Flask/Django
- **Deployment:** Docker
- **CI/CD:** GitHub Actions, Docker

## 🔧 Setup Instructions
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/Soum12ya/datascienceproject.git
 cd datascienceproject
```
### 2️⃣ Create and Activate a Virtual Environment
```sh
 python -m venv venv
 source venv/bin/activate   # On Windows: venv\Scripts\activate
```
### 3️⃣ Install Dependencies
```sh
 pip install -r requirements.txt
```
### 4️⃣ Run the Application
```sh
 python app.py
```

## 📦 CI/CD Pipeline
### ✅ Steps in the Pipeline
1. **Version Control**: GitHub repository management
2. **Automated Testing**: Pytest for unit tests
3. **Dockerization**: Containerizing the application

## 🎯 API Endpoints
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/predict` | POST | Predicts wine quality based on input features |

## 📝 License
This project is licensed under the GNU License.

## 🤝 Contributing
Feel free to contribute! Open issues, submit PRs, and improve the project.

## 📞 Contact
For any queries, reach out via [LinkedIn](https://www.linkedin.com/in/soumyajit-bhandary-20b348254/) or [Email](mailto:soumyajitbhandary9@gmail.com).
