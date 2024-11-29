# 📊 Student Exam Performance Predictor

## 🌟 Project Overview

Unlock the power of predictive analytics with our Student Exam Performance Predictor! This intelligent web application leverages advanced machine learning techniques to forecast a student's math score based on various demographic and academic factors.

## ✨ Key Features

### 🤖 Advanced Prediction Engine
- **Multiple Machine Learning Models**: Utilizing Random Forest, XGBoost, CatBoost, and more
- **Intelligent Model Selection**: Automatically chooses the best-performing model
- **Precise Predictions**: Accurate math score forecasting

### 🖥️ User-Friendly Interface
- **Simple Web Form**: Easy input of student details
- **Instant Predictions**: Immediate math score estimation
- **Intuitive Design**: Seamless user experience

## 🛠 Technology Stack

| Technology | Purpose | Description |
|-----------|---------|-------------|
| Flask | Web Framework | Powering the backend application |
| Scikit-learn | Machine Learning | Model training and evaluation |
| XGBoost | Prediction | Advanced gradient boosting |
| CatBoost | Machine Learning | Efficient categorical feature handling |
| Pandas & NumPy | Data Processing | Advanced data manipulation |

## 🔧 Installation & Setup

### Prerequisites
Ensure you have the following installed:
- [Python 3.6+](https://www.python.org/)
- [Pip](https://pip.pypa.io/en/stable/installation/)

### Installation Steps

#### 1. Clone the Repository
```bash
git clone https://github.com/dinesh-gaire/Student-Exam-Performance-Prediction.git
cd Student-Exam-Performance-Prediction
```

#### 2. Create Virtual Environment
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# For Unix/macOS:
source venv/bin/activate
# For Windows:
venv\Scripts\activate
```

#### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

#### 4. Train the Model
```bash
python src/model_trainer.py
```

#### 5. Launch the Application
```bash
python app.py
```

🌐 Access the app at: `http://127.0.0.1:5000/`

## 🔍 How It Works

### 1. Data Input
Collect key student information:
- Gender
- Race/Ethnicity
- Parental Education
- Lunch Type
- Test Preparation
- Reading Score
- Writing Score

### 2. Machine Learning Magic
- **Model Processing**: Advanced preprocessing
- **Intelligent Prediction**: Accurate math score estimation
- **Instant Feedback**: Immediate result display

## 🤖 Machine Learning Models

Our prediction arsenal includes:
- Random Forest Regressor
- Decision Tree Regressor
- Gradient Boosting Regressor
- Linear Regression
- XGBoost Regressor
- CatBoost Regressor
- AdaBoost Regressor

### Model Evaluation
- **Metric**: R-squared score
- **Goal**: Maximum predictive accuracy

## 🤝 Contributing

We love community contributions!

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/awesome-improvement
   ```
3. **Commit** your changes
   ```bash
   git commit -m "Describe your innovative addition"
   ```
4. **Push** to your branch
   ```bash
   git push origin feature/awesome-improvement
   ```
5. **Open** a Pull Request

## 📄 License

Proudly licensed under the MIT License. 
See the `LICENSE` file for complete details.

## 🎉 Let's Predict Academic Success!

Star ⭐ the repo if you're excited about data-driven education!

**Empowering students through intelligent predictions!** 📈🎓
