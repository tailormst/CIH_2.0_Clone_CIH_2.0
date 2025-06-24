# CIH_2.0_Clone_CIH_2.0
This is NewFDAAS which is uploaded in google drive so kindly open the link in the google drive
https://drive.google.com/file/d/1tC1Fo7Hnmy6rPPadqFlsWU89VCddSViF/view?usp=sharing


# 🛡️ Django Fraud Detection System

A comprehensive, AI-powered fraud detection web application built with Django and advanced machine learning algorithms. This system provides real-time fraud analysis for financial transactions with both web interface and RESTful API access.

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Django](https://img.shields.io/badge/django-v4.2.7-green.svg)
![XGBoost](https://img.shields.io/badge/xgboost-v1.7.6-orange.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🌟 Features

### 🔐 Authentication & Security
- **User Registration & Login**: Secure authentication using Django's built-in system
- **API Key Management**: Auto-generated API keys for programmatic access
- **Session Management**: Secure session handling and CSRF protection

### 🤖 Machine Learning Capabilities
- **XGBoost Model**: Advanced gradient boosting algorithm for fraud detection
- **Real-time Prediction**: Instant fraud analysis with confidence scores
- **Feature Engineering**: Automated preprocessing including:
  - Distance calculation between cities
  - Age computation and outlier handling
  - Time-based feature extraction
  - One-hot encoding for categorical variables

### 🌐 Web Interface
- **Manual Fraud Check**: User-friendly form for individual transaction analysis
- **Transaction History**: Complete audit trail of all fraud checks
- **Interactive Dashboard**: Visual representation of fraud analysis results
- **Responsive Design**: Mobile-friendly interface using Bootstrap

### 🔌 API Integration
- **RESTful API**: JSON-based API for system integration
- **API Key Authentication**: Secure access control
- **Comprehensive Documentation**: Built-in API documentation
- **Rate Limiting**: Protection against API abuse

### 📊 Analytics & Reporting
- **Risk Scoring**: Detailed fraud probability calculations
- **Confidence Metrics**: Model confidence indicators
- **Processing Time Tracking**: Performance monitoring
- **Status Recommendations**: Automated decision support

## 🚀 Quick Start

### Prerequisites

- **Python 3.8+** (Recommended: Python 3.9 or 3.10)
- **pip** (Python package manager)
- **Git** (Version control)
- **Virtual Environment** (venv or conda)

### Installation

1. **Clone the Repository**
   \`\`\`bash
   git clone https://github.com/your-username/django-fraud-detection.git
   cd django-fraud-detection
   \`\`\`

2. **Create Virtual Environment**
   \`\`\`bash
   #### Using venv
   python -m venv fraud_env
   
   ### Activate environment
   #### Windows:
   fraud_env\Scripts\activate
   #### macOS/Linux:
   source fraud_env/bin/activate
   \`\`\`

3. **Install Dependencies**
   \`\`\`bash
   pip install --upgrade pip
   pip install -r requirements.txt
   \`\`\`

4. **Setup Machine Learning Model**
   \`\`\`bash
   #### Create ML models directory
   mkdir ml_models
   
   #### Place your fraud_model2.pkl file in ml_models/
   #### Download from: [Your Model Source]
   cp path/to/your/fraud_model2.pkl ml_models/
   \`\`\`

5. **Configure Environment Variables**
   \`\`\`bash
   #### Create .env file
   echo "SECRET_KEY=your-super-secret-django-key-here
   DEBUG=True
   DATABASE_URL=sqlite:///db.sqlite3" > .env
   \`\`\`

6. **Initialize Database**
   \`\`\`bash
   python manage.py makemigrations
   python manage.py migrate
   python manage.py createsuperuser
   \`\`\`

7. **Run Development Server**
   \`\`\`bash
   python manage.py runserver
   \`\`\`

8. **Access the Application**
   - **Web Interface**: http://127.0.0.1:8000/
   - **Admin Panel**: http://127.0.0.1:8000/admin/
   - **API Documentation**: http://127.0.0.1:8000/api/docs/

## 📋 Detailed Setup Guide

### System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Python | 3.8 | 3.9+ |
| RAM | 4GB | 8GB+ |
| Storage | 2GB | 5GB+ |
| CPU | 2 cores | 4+ cores |

### Package Versions

\`\`\`txt
Django==4.2.7
djangorestframework==3.14.0
numpy==1.24.3
pandas==2.0.3
scikit-learn==1.3.0
xgboost==1.7.6
joblib==1.3.2
python-decouple==3.8
\`\`\`


## Team Info:
### Member 1 - Mohammed Tailor
### Member 2 - Jayandrajeet Chauhan
### Member 2 - Jagdish Jadhav
### Member 2 - Amit Bangde
