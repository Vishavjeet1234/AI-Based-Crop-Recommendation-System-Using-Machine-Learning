# AI-Based Crop Recommendation System Using Machine Learning

## Overview

The AI-Based Crop Recommendation System is a Machine Learning-based solution that helps farmers identify the most suitable crop to cultivate based on soil and environmental conditions. The system analyzes important agricultural parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, soil pH, and rainfall to provide accurate crop recommendations.

By utilizing machine learning algorithms, the system supports data-driven decision-making, improves agricultural productivity, reduces resource wastage, and promotes sustainable farming practices.

---

## Key Features

### Input Data Collection

The system accepts agricultural and environmental parameters including:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* Soil pH
* Rainfall

### Data Preprocessing

The collected data is processed to improve model performance through:

* Handling missing values
* Data cleaning
* Feature normalization
* Data transformation

### Machine Learning Models

The system uses machine learning algorithms such as:

* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* Gradient Boosting

### Model Training and Evaluation

The models are trained using historical agricultural datasets and evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

### Crop Recommendation

Based on the input parameters, the system predicts and recommends the most suitable crop for cultivation.

### Performance Analysis

The system compares model performance and selects the best-performing algorithm for accurate recommendations.

### Easy-to-Use Interface

Users can easily enter agricultural parameters and obtain crop recommendations with minimal effort.

---

## Technologies Used

### Python

Primary programming language used for model development and implementation.

### Scikit-learn

Machine learning library used for:

* Model training
* Prediction
* Performance evaluation

### Pandas

Used for:

* Data loading
* Data cleaning
* Data analysis

### NumPy

Used for:

* Numerical computations
* Array manipulation
* Mathematical operations

### Matplotlib

Used for:

* Data visualization
* Accuracy comparison charts
* Graph generation

### Jupyter Notebook

Used for:

* Model development
* Experimentation
* Analysis

---

## Machine Learning Workflow

```text
Dataset Collection
        ↓
Data Preprocessing
        ↓
Feature Selection
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Crop Prediction
        ↓
Crop Recommendation
```

---

## Input Parameters

| Parameter   | Description             |
| ----------- | ----------------------- |
| N           | Nitrogen Content        |
| P           | Phosphorus Content      |
| K           | Potassium Content       |
| Temperature | Atmospheric Temperature |
| Humidity    | Relative Humidity       |
| pH          | Soil pH Value           |
| Rainfall    | Rainfall in mm          |

---

## Output

The system recommends the most suitable crop such as:

* Rice
* Wheat
* Maize
* Cotton
* Jute
* Coffee
* Coconut
* Chickpea
* Kidney Beans
* Lentils

and many other crops depending on the input conditions.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Vishavjeet1234/AI-Crop-Recommendation-System.git
```

### Navigate to Project Folder

```bash
cd AI-Crop-Recommendation-System
```

### Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib
```

---

## Usage

### Train the Model

```bash
python train_model.py
```

### Predict Crop

```bash
python predict_crop.py
```

### Example Input

```text
Nitrogen = 90
Phosphorus = 42
Potassium = 43
Temperature = 21
Humidity = 82
pH = 6.5
Rainfall = 202
```

### Example Output

```text
Recommended Crop: Rice
```

---

## Future Enhancements

* Integration with IoT Sensors
* Real-Time Weather Analysis
* Fertilizer Recommendation System
* Soil Health Monitoring
* Mobile Application Development
* AI-Based Disease Detection

---
AI Crop recommendation system
## Conclusion

The AI-Based Crop Recommendation System demonstrates the application of Machine Learning in modern agriculture. By analyzing soil and environmental conditions, the system provides accurate crop recommendations that help farmers improve productivity, optimize resource utilization, and support sustainable farming practices.

