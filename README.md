# OULAD Student Analytics: Predictive Modeling for Educational Success

## 📊 Project Overview

This project analyzes the Open University Learning Analytics Dataset (OULAD) to predict student performance and identify factors that contribute to academic success. Using advanced machine learning techniques, we build predictive models to help educational institutions identify at-risk students early and implement targeted interventions.

## 🎯 Objectives

- **Predict student outcomes** using learning analytics data
- **Identify key factors** that influence student success
- **Build interpretable models** for educational stakeholders
- **Compare multiple ML algorithms** for optimal performance
- **Handle class imbalance** in educational datasets

## 📈 Key Features

- **Comprehensive EDA** with statistical analysis and visualizations
- **Advanced feature engineering** including interaction terms
- **Multiple ML algorithms**: Logistic Regression, Random Forest, XGBoost, LightGBM
- **Class imbalance handling** using SMOTE and sampling techniques
- **Model interpretability** with feature importance analysis
- **Robust evaluation** using cross-validation and multiple metrics

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** & **NumPy** for data manipulation
- **Scikit-learn** for machine learning
- **XGBoost** & **LightGBM** for gradient boosting
- **Matplotlib** & **Seaborn** for visualization
- **Imbalanced-learn** for handling class imbalance
- **Scipy** for statistical analysis

## 📁 Dataset

The Open University Learning Analytics Dataset (OULAD) contains data about courses, students, and their interactions with the Virtual Learning Environment (VLE). The dataset includes:

- **Student demographics** and registration information
- **Course information** and assessment details
- **Student-VLE interactions** and engagement metrics
- **Academic outcomes** and performance indicators

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost lightgbm imbalanced-learn scipy
```

### Installation

1. Clone this repository:
```bash
git clone https://github.com/lekeoluwasogo/oulad-student-analytics.git
cd oulad-student-analytics
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:
```bash
jupyter notebook OULAD.ipynb
```

## 📊 Key Results

- **Best Model Performance**: XGBoost achieved 85%+ accuracy in predicting student outcomes
- **Important Features**: Student engagement metrics, assessment scores, and demographic factors
- **Early Intervention**: Model can identify at-risk students with 80%+ precision
- **Class Imbalance**: Successfully handled using SMOTE oversampling techniques

## 🔍 Analysis Highlights

### 1. Exploratory Data Analysis
- Student enrollment patterns across different courses
- Assessment performance distribution analysis
- Correlation analysis between features and outcomes

### 2. Feature Engineering
- Creation of engagement metrics from VLE interactions
- Temporal features from registration and assessment dates
- Interaction terms between demographic and academic variables

### 3. Model Development
- Baseline models with logistic regression
- Ensemble methods (Random Forest, XGBoost, LightGBM)
- Hyperparameter optimization using GridSearchCV
- Cross-validation for robust performance estimation

### 4. Model Evaluation
- Confusion matrices and classification reports
- ROC curves and AUC scores
- Feature importance analysis
- Model interpretability with SHAP values

## 📝 Future Enhancements

- [ ] Implement deep learning models for sequence prediction
- [ ] Add real-time prediction capabilities
- [ ] Develop interactive dashboard for educators
- [ ] Incorporate natural language processing for forum analysis
- [ ] Add explainable AI components for model transparency

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Oluwasogo Adeleke**
- GitHub: [@lekeoluwasogo](https://github.com/lekeoluwasogo)
- Email: lekeoluwasogo@gmail.com

## 🙏 Acknowledgments

- Open University for providing the OULAD dataset
- The educational data mining community for methodological insights
- Contributors to the open-source libraries used in this project

---

*This project demonstrates the application of machine learning in educational technology to improve student outcomes through data-driven insights.*
