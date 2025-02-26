# Anomaly Detection & Classification in Blood Donation Data
Hey there! Welcome to my project on spotting quirks and predicting health conditions in blood donation data. I dove into a dataset of blood donor medical records to detect anomalies (think oddball outliers) and classify folks into categories like donation status, hepatitis, cirrhosis, and more. Armed with machine learning, I built a system that’s part detective, part fortune-teller—perfect for recruiters looking for data science chops with real-world impact!

## Project Overview  
This is my take on using machine learning to make sense of blood donation data. The goal? Flag unusual cases and predict medical conditions that matter. I mixed anomaly detection with classification magic, leaning on tools like Isolation Forest, Decision Trees, XGBoost, and a custom Combined Model. Plus, I threw in SHAP to explain what’s driving the predictions—because transparency is key. It’s a blend of tech and purpose, and I’m stoked to show you how it works!

## Tasks & Steps  
Here’s how I pulled it off:  
- **Anomaly Detection**: Fired up Isolation Forest to sniff out weird data points—like donors who don’t fit the mold.  
- **Classification**: Trained a trio of models—Decision Tree, XGBoost, and a Combined Model—to predict health statuses. Tuned XGBoost with GridSearchCV for that extra oomph.  
- **Evaluation**: Checked my work with a Confusion Matrix, Classification Report (Precision, Recall, F1), ROC Curve, AUC Score, and good ol’ accuracy metrics.  
- **Explainability**: Used SHAP to shine a light on what features (like blood markers) matter most and why the models think what they do.  

## Key Insights  
- Isolation Forest nailed the outliers—think rare cases that could signal deeper issues.  
- XGBoost, post-tuning, stole the show with top-tier accuracy. It’s my go-to for a reason!  
- Features like donor history and lab results were huge predictors—SHAP visuals made that crystal clear.  
- The Combined Model brought teamwork to the table, boosting predictions beyond any solo act.  

## Requirements  
To run this, you’ll need:  
- Python 3.x  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `shap`, `matplotlib`, `seaborn`  
All neatly listed in `requirements.txt` for you!

## Installation  
Ready to dig in? Here’s how to set it up:  
1. Clone the repo and hop in:  
   ```bash  
   git clone https://github.com/VishalGawale/ml-blood-donor-classifier.git  
   cd ml-blood-donor-classifier 
