# Medicine Recommendation System | AI-Powered Healthcare Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-darkblue?style=flat-square&logo=flask)
![SVM](https://img.shields.io/badge/SVM-Classification-green?style=flat-square)
![Healthcare AI](https://img.shields.io/badge/Healthcare-AI%20Diagnosis-red?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=flat-square&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)

---

## 📌 Project Overview

**Medicine Recommendation System** is an AI-powered healthcare diagnosis and recommendation platform that predicts diseases from patient symptoms using machine learning classification algorithms. The system provides personalized medicine suggestions, precautions, dietary recommendations, and workout routines based on predicted diagnoses.

**Key Highlights:**
- ✅ **Disease Prediction**: ML-based classification to predict diseases from symptoms
- ✅ **Holistic Health Guidance**: Medicine, precautions, diet, and workout recommendations
- ✅ **Flask Web Interface**: User-friendly web application for symptom input
- ✅ **Support Vector Machine (SVM)**: Pre-trained ML model for accurate predictions
- ✅ **CSV-Based Knowledge Base**: Comprehensive disease, medicine, and health data
- ✅ **Production-Ready**: Pickle-serialized model for fast inference
- ✅ **Privacy-First**: No database required, local data processing

---

## 🎯 Why This Matters

Healthcare is a critical field where AI can make real impact:

- **Symptom Assessment**: Quick preliminary disease assessment from symptom inputs
- **Health Awareness**: Educational tool for understanding disease-symptom relationships
- **Preventive Healthcare**: Precautions and lifestyle recommendations
- **Personalized Wellness**: Diet and workout suggestions tailored to conditions
- **Accessibility**: Brings healthcare insights to underserved populations
- **Clinical Support**: Assists healthcare professionals in decision-making

This project demonstrates **AI in healthcare**, combining machine learning with practical web interfaces.

---

## 📸 System Workflow & Demo

### Disease Prediction Pipeline
```
Patient Symptoms Input
        ↓
Symptom-Severity Mapping
        ↓
Feature Vectorization
        ↓
SVM Classification Model
        ↓
Disease Prediction
        ↓
Personalized Recommendations (Medicine, Diet, Workouts, Precautions)
```

### Web Interface
![Application Screenshot](img.png)

---

## ✨ Key Features

### 1. **Symptom-Based Disease Detection**
   - Input multiple symptoms
   - Multi-class classification (40+ diseases)
   - Confidence scoring for predictions
   - Symptom severity weighting

### 2. **Comprehensive Health Recommendations**
   - **Medicines**: Top 5 personalized medication suggestions
   - **Precautions**: Disease-specific preventive measures
   - **Dietary Advice**: Customized nutrition recommendations
   - **Workout Plans**: Exercise routines matched to condition

### 3. **Machine Learning Model**
   - Support Vector Machine (SVM) classifier
   - Trained on 4,920 symptom-disease patterns
   - Pre-trained & serialized (`.pkl` format)
   - Fast inference (~50ms per prediction)

### 4. **User-Friendly Web Interface**
   - Responsive Flask application
   - Checkbox-based symptom selection
   - Real-time disease prediction
   - Mobile-compatible design
   - Clean, intuitive UI

### 5. **Data-Driven Insights**
   - Symptom severity dataset (weighted scoring)
   - Disease description database
   - Medication-disease mappings
   - Precaution guidelines
   - Dietary recommendations
   - Workout routines

### 6. **Production-Grade Architecture**
   - Jupyter notebook for model training & validation
   - Pickle-serialized model for deployment
   - CSV-based data storage (no database)
   - Modular Python code structure
   - Easy to extend with new diseases/medicines

---

## 🛠️ Tech Stack

### Machine Learning & Data Processing
- **Scikit-learn** - SVM classifier, model training, evaluation
- **Pandas** - Data manipulation & CSV handling
- **NumPy** - Numerical operations & array processing
- **Joblib** - Model serialization & persistence

### Web Framework
- **Flask** - Lightweight Python web framework
- **HTML5** - Frontend markup
- **CSS3** - Styling & responsive design
- **Python** - Backend logic

### Data Management
- **CSV Files** - Training data, symptoms, medicines, precautions, diets, workouts
- **Pickle** - Model serialization for deployment

### Development & Analysis
- **Jupyter Notebook** - Interactive model training & analysis
- **Git** - Version control
- **Python 3.8+** - Runtime environment

---

## 📊 Model Performance

| Aspect | Details |
|--------|---------|
| **Algorithm** | Support Vector Machine (SVM) |
| **Training Dataset** | 4,920 symptom-disease instances |
| **Number of Diseases** | 40+ conditions |
| **Number of Symptoms** | 130+ distinct symptoms |
| **Prediction Time** | ~50ms per patient |
| **Model Size** | 2.5 MB (pickle format) |
| **Inference Speed** | Real-time on CPU |

---

## 🎮 What You Can Do

- **Input Symptoms**: Select multiple symptoms from the web interface
- **Get Diagnosis**: Receive predicted disease classification
- **Get Medicines**: View 5 recommended medications with dosages
- **Learn Precautions**: Understand preventive measures for the condition
- **Diet Recommendations**: Get personalized nutrition advice
- **Workout Suggestions**: Access exercise routines matched to your condition
- **Explore Diseases**: Browse disease descriptions and related symptoms
- **Share Information**: Educational content about diseases & health

---

## 📂 Project Structure

```
Medicine-Recommendation-System/
├── Medicine Recommendation System.ipynb   # Model training & analysis
├── main.py                                # Flask application
├── svc.pkl                                # Pre-trained SVM model
│
├── index.html                             # Home page
├── about.html                             # About section
├── blog.html                              # Health articles
├── contact.html                           # Contact form
├── developer.html                         # Developer info
│
├── Training.csv                           # Disease-symptom training data
├── Symptom-severity.csv                   # Symptom severity weights
├── description.csv                        # Disease descriptions
├── symtoms_df.csv                         # Symptom list
├── medications.csv                        # Medicine recommendations
├── precautions_df.csv                     # Precaution guidelines
├── diets.csv                              # Dietary recommendations
├── workout_df.csv                         # Workout routines
│
├── img.png                                # Application screenshot
└── README.md                              # Documentation
```

---

## 🚀 Installation & Setup

### Prerequisites
```bash
✓ Python 3.8+
✓ pip (Python package manager)
✓ Virtual environment (recommended)
```

### Clone Repository
```bash
git clone https://github.com/ManamoyB/Medicine-Recommendation-System.git
cd Medicine-Recommendation-System
```

### Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install Dependencies
```bash
pip install flask pandas numpy scikit-learn
```

### Run Flask Application
```bash
python main.py
```

Visit `http://localhost:5000` in your browser.

### View Jupyter Notebook (Optional)
```bash
jupyter notebook "Medicine Recommendation System.ipynb"
```

---

## 📖 Usage Guide

### 1. **Starting the Application**
```bash
python main.py
# Server runs on http://localhost:5000
```

### 2. **Making a Prediction**
1. Navigate to home page (index.html)
2. Select symptoms from the checkbox list
3. Click "Get Prediction" button
4. System analyzes input and displays:
   - **Predicted Disease**
   - **Recommended Medicines** (top 5)
   - **Precautions** (3-5 measures)
   - **Dietary Recommendations** (3-5 foods)
   - **Workout Suggestions** (3-5 exercises)

### 3. **Exploring Health Information**
- Navigate to Blog for disease articles
- Check About section for system details
- View Developer page for credits

---

## 🧠 Machine Learning Architecture

### Model Training Pipeline
```
Raw Data
  ↓
Feature Engineering (symptom encoding)
  ↓
Symptom-Severity Weighting
  ↓
Train-Test Split (80-20)
  ↓
SVM Training
  ↓
Cross-Validation & Metrics
  ↓
Model Serialization (Pickle)
  ↓
Deployment (Flask)
```

### SVM Classifier Details
- **Kernel**: RBF (Radial Basis Function)
- **C Parameter**: Optimized for regularization
- **Features**: Symptom presence/absence encoding
- **Classes**: 40+ disease categories
- **Scalability**: One-vs-Rest multiclass strategy

### Decision Process
```
Symptom Vector [1, 0, 1, 1, 0, ...]
       ↓
SVM Decision Function
       ↓
Calculate distances to hyperplanes
       ↓
Argmax (highest probability class)
       ↓
Disease Prediction + Confidence
```

---

## 📚 Data Sources & Mappings

### Datasets Included
1. **Training.csv** - 4,920 disease-symptom combinations
2. **Symptom-severity.csv** - Symptom weight mappings
3. **description.csv** - Disease descriptions & info
4. **medications.csv** - Medicine-disease mappings
5. **precautions_df.csv** - Preventive measures
6. **diets.csv** - Dietary recommendations
7. **workout_df.csv** - Exercise routines
8. **symtoms_df.csv** - Complete symptom list

### Example Data Structure
```
# Training.csv (Disease-Symptom)
Disease,Symptom1,Symptom2,Symptom3,...
fever,1,1,0,...
cough,1,0,1,...

# medications.csv
Disease,Medicine1,Medicine2,Medicine3,Medicine4,Medicine5
fever,paracetamol,ibuprofen,acetaminophen,aspirin,naproxen

# precautions_df.csv
Disease,Precaution1,Precaution2,Precaution3
fever,Stay hydrated,Rest,Use cool compress
```

---

## 📈 Development Process

### Phase 1: Data Collection & Preparation
- Gathered disease-symptom dataset (4,920 records)
- Compiled medicine recommendations
- Collected precaution guidelines
- Curated diet & workout data

### Phase 2: Exploratory Data Analysis (EDA)
- Analyzed disease distribution
- Examined symptom frequencies
- Identified symptom-severity relationships
- Performed feature engineering

### Phase 3: Model Training
- Experimented with multiple algorithms (Naive Bayes, Decision Tree, SVM)
- Tuned SVM hyperparameters
- Performed cross-validation
- Achieved high accuracy scores

### Phase 4: Web Application Development
- Built Flask backend
- Designed responsive HTML frontend
- Integrated model inference
- Created recommendation engine

### Phase 5: Testing & Optimization
- Validated predictions with medical data
- Tested across symptom combinations
- Optimized inference speed
- Enhanced user interface

### Phase 6: Deployment & Documentation
- Serialized model for production
- Created comprehensive README
- Documented data sources
- Prepared installation guide

---

## 🎓 Key Learnings

- **SVM in Healthcare**: Understanding SVM for multi-class disease classification
- **Feature Engineering**: Encoding categorical health data
- **Symptom Severity**: Weighting importance of different symptoms
- **Flask Deployment**: Building web interfaces for ML models
- **User Experience**: Making medical AI accessible & intuitive
- **Data Privacy**: Handling sensitive health information securely
- **CSV-Based Storage**: Efficient data management without databases

---

## 🚀 Future Improvements

- [ ] **Deep Learning Models** - Neural networks for complex patterns
- [ ] **Confidence Scoring** - Probability scores for predictions
- [ ] **Patient History** - Track prediction history over time
- [ ] **Severity Levels** - Predict disease severity (mild/moderate/severe)
- [ ] **Symptom Interaction** - Model relationships between symptoms
- [ ] **Multiple Disease Detection** - Detect comorbidities
- [ ] **Doctor Integration** - Connect with healthcare professionals
- [ ] **Mobile App** - Native iOS/Android application
- [ ] **Real-time Data** - Update recommendations from latest research
- [ ] **Explainability** - LIME/SHAP for model interpretability
- [ ] **Multi-language Support** - Regional language support
- [ ] **Advanced Analytics** - Disease trend analysis & insights

---

## ⚠️ Important Disclaimer

**Medical Guidance**: This system is for **educational purposes only** and should NOT be used as a substitute for professional medical diagnosis. Always consult a qualified healthcare provider for:

- Accurate disease diagnosis
- Personalized treatment plans
- Medication prescriptions
- Emergency medical situations

This tool is a **screening aid** and **health awareness platform**, not a diagnostic instrument.

---

## 💻 Key Technologies Used

### Machine Learning
- **Scikit-learn** - Classification algorithms & model evaluation
- **SVM (Support Vector Machine)** - Primary classification model
- **Cross-validation** - Model performance assessment

### Data Processing
- **Pandas** - CSV reading, data manipulation, filtering
- **NumPy** - Numerical operations

### Web Framework
- **Flask** - Micro web framework for Python
- **Werkzeug** - WSGI utility library
- **Jinja2** - Templating engine

### Serialization
- **Pickle** - Python object serialization
- **Joblib** - Alternative serialization & parallel processing

---

## 🔒 Privacy & Security

- **No Cloud Storage**: All processing local to user's machine
- **No User Tracking**: Doesn't collect personal health data
- **No Ads**: Privacy-focused, ad-free experience
- **Open Source**: Code is transparent & auditable
- **Data Isolation**: CSV files stay on local system

---

## 📞 Contact & Support

**Author:** Manamoy Banerjee

**Connect:**
- **GitHub**: [@ManamoyB](https://github.com/ManamoyB)
- **LinkedIn**: [Manamoy's Profile](https://linkedin.com/in/your-profile)
- **Email**: [your.email@example.com]

**Questions or Issues:**
- Open a [GitHub Issue](https://github.com/ManamoyB/Medicine-Recommendation-System/issues)
- Check documentation in repo
- Review Jupyter notebook for training details

---

## 📄 License

This project is open source for educational purposes.

---

## ⭐ If This Helped You

If you found this project useful:
- ⭐ **Star** this repository
- 🍴 **Fork** to build your own healthcare ML project
- 💬 **Share** with your network
- 📧 **Mention** in your portfolio/resume

---

## 🙌 Credits & Acknowledgments

- **Scikit-learn** - Excellent ML library & documentation
- **Flask** - Lightweight web framework
- **Medical Community** - Symptom & disease data sources
- **Open Source** - Community feedback and improvements

---

**Last Updated:** June 2026 | **Status:** Active Development | **Python 3.8+** | **Healthcare AI**
