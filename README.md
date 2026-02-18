# Employee Attrition Risk Agent 

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Gradio](https://img.shields.io/badge/Gradio-3.0%2B-orange)](https://gradio.app/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-green)](https://scikit-learn.org/)
[![SHAP](https://img.shields.io/badge/SHAP-0.40%2B-red)](https://shap.readthedocs.io/)


<img width="671" height="390" alt="image" src="https://github.com/user-attachments/assets/38e0426c-9668-49d5-a5a9-17631928591d" />

An intelligent HR analytics tool that predicts employee attrition risk using machine learning, provides explainable insights through SHAP values, and delivers actionable retention recommendations.

## Overview

This AI-powered agent helps HR professionals proactively identify employees at risk of leaving the organization, understand the key factors contributing to the risk, and receive tailored recommendations for employee retention.

### Key Features
- **Predictive Analytics**: Decision Tree Classifier trained on IBM HR dataset
- **Explainable AI**: SHAP waterfall plots for transparent decision-making
- **Smart Recommendations**: Rule-based system for HR-friendly retention strategies
- **Real-time Dashboard**: Interactive Gradio interface
- **Slack Integration**: Automated alerts for high-risk employees


<img width="457" height="247" alt="image" src="https://github.com/user-attachments/assets/5347241f-70c2-4f5b-8422-b8e6c56c4f74" />

## Use Case

Human Resource teams can leverage this tool to:
- Identify flight-risk employees before they resign
- Understand specific factors driving attrition for each employee
- Implement targeted retention strategies
- Make data-driven HR decisions

## Architecture

<img width="335" height="438" alt="image" src="https://github.com/user-attachments/assets/3c4bc339-504b-4416-99a0-208a22b9df3a" />


## Model & Dataset

- **Model Type**: Decision Tree Classifier
- **Dataset**: Kaggle HR Employee Attrition dataset
- **Features**: Job satisfaction, years at company, overtime, salary, etc.
- **Explainability**: SHAP (SHapley Additive exPlanations) waterfall plots

## Workflow

1. **User Input**: Enter Employee Index
2. **Risk Prediction**: Model predicts attrition probability
3. **Explanation**: SHAP waterfall plot shows key factors
4. **Recommendation**: Rule-based system generates HR-friendly suggestions
5. **Visualization**: Results displayed on Gradio dashboard

## Slack Integration

The system includes automated Slack notifications for proactive HR intervention:

- **Trigger**: Attrition probability > 60%
- **Action**: Automated alert via Slack Webhook
- **Content**: Employee details, risk factors, and recommendations
- **Benefit**: Immediate awareness for HR teams

