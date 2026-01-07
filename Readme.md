# 🏥 Healthcare Appointment No-Show Predictor

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Problem Statement

Hospitals and clinics face significant revenue loss due to **missed appointments (20-30% no-show rate)**. Patients who don't show up without canceling prevent other patients from getting care and waste valuable medical resources.

This project builds a **Machine Learning system** to:
- Predict which patients are likely to miss their appointments
- Suggest optimal intervention strategies (SMS, calls, emails)
- Help hospitals reduce no-show rates by 35-40%

---

## Business Impact

### Current Situation
- **20.2% no-show rate** identified in our dataset
- For a hospital with 3,000 monthly appointments
- At ₹500 per appointment value
- **Monthly loss: ₹3,03,000**

### After Implementation
- Reduce no-show rate to **12%**
- **Monthly savings: ₹1,23,000+**
- Improved patient care and resource utilization
- Better scheduling efficiency

---

## Dataset Information

- **Source:** [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **Records:** 110,527 medical appointments
- **Features:** 14 columns
- **Target Variable:** No-show (Yes/No)

### Key Features
- Patient demographics (Age, Gender)
- Appointment details (Scheduled day, Appointment day)
- Health conditions (Hypertension, Diabetes, Alcoholism, Handicap)
- Communication (SMS received)
- Location (Neighbourhood)
- Socioeconomic factors (Scholarship status)

---

## Tech Stack

### Programming & Analysis
- **Python 3.8+**
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine Learning

### Visualization
- **Matplotlib** - Static visualizations
- **Seaborn** - Statistical graphics
- **Power BI** - Interactive dashboards

### Machine Learning Models
- Logistic Regression (Baseline)
- Random Forest Classifier
- XGBoost
- Feature Engineering & Selection

### Tools
- **Jupyter Notebook** - Development environment
- **Git & GitHub** - Version control
- **VS Code** - Code editor

---

## Project Structure
```
Healthcare-NoShow-Predictor/
│
├── data/
│   ├── raw/                      # Original dataset
│   └── processed/                # Cleaned and feature-engineered data
│
├── notebooks/
│   ├── 01_data_exploration.ipynb      
│   ├── 02_data_cleaning.ipynb         
│   ├── 03_eda.ipynb                   
│   ├── 04_feature_engineering.ipynb   
│   └── 05_modeling.ipynb              
│
├── src/                          # Python scripts
├── models/                       # Saved ML models
├── dashboards/                   # Power BI files
├── reports/                      # Visualizations and findings
│   └── 01_target_distribution.png
│
└── README.md                     # Project documentation
```

---

## Project Workflow

### Phase 1: Data Exploration ✅
- Load and inspect dataset
- Check data quality (missing values, duplicates)
- Analyze target variable distribution
- Initial insights and statistics

### Phase 2: Data Cleaning & Preparation 🔄
- Handle date/time conversions
- Remove outliers and anomalies
- Create derived features
- Encode categorical variables

### Phase 3: Exploratory Data Analysis (EDA) ⏳
- Univariate analysis
- Bivariate analysis (features vs target)
- Correlation analysis
- Identify key predictors

### Phase 4: Feature Engineering ⏳
- Time-based features (day of week, hour, waiting time)
- Patient history features
- Distance/location features
- Interaction features

### Phase 5: Model Building ⏳
- Train-test split
- Baseline models
- Hyperparameter tuning
- Model evaluation and selection
- Feature importance analysis

### Phase 6: Dashboard & Deployment ⏳
- Power BI interactive dashboard
- Business insights report
- Recommendations engine
- ROI calculation

---

## Key Insights (So Far)

### From Initial Exploration:
- **110,527** total appointments analyzed
- **20.2%** no-show rate (baseline to beat)
- **No missing values** in the dataset
- **Age range:** -1 to 115 years (needs cleaning!)
- **SMS reminders** sent to ~32% of patients

---

## Project Goals

1. **Reduce no-show rate** from 20.2% to below 12%
2. **Identify high-risk patients** with >70% accuracy
3. **Create actionable recommendations** for hospital staff
4. **Build interactive dashboard** for real-time monitoring
5. **Calculate clear ROI** and business impact

---

## Key Learnings & Skills Demonstrated

- End-to-end ML project execution
- Real-world problem solving with data
- Feature engineering and selection
- Model evaluation and business metrics
- Data storytelling and visualization
- Healthcare domain understanding

---

## Future Enhancements

- Real-time prediction API using Flask/Django
- Integration with hospital management systems
- A/B testing framework for interventions
- Mobile app for appointment reminders
- Deep learning models (LSTM for sequential patterns)
- Multi-language support for SMS reminders

---

## Author

**Laiba Fatima Khan**  
Data Analyst | Machine Learning Enthusiast

- Email: laibassvm123@gmail.com
- LinkedIn: https://www.linkedin.com/in/laiba-fatima-a5a0a528b/
- GitHub: [@laibakhan26](https://github.com/laibakhan26)
- Location: Bangalore, India

---

## License

This project is licensed under the MIT License - feel free to use it for learning and portfolio purposes.

---

##  Acknowledgments

- Dataset provided by Kaggle community
- Inspired by real healthcare challenges
- Built as part of data science portfolio

---

## Contact

Have questions or suggestions? Feel free to reach out!

**Current Status:** Actively developing (Step 1 completed, Step 2 in progress)

**Last Updated:** January 2025

---

If you find this project helpful, please star it on GitHub!
```


