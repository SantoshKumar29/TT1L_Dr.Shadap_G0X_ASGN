# 📱 TikTok App Reviews Sentiment Analysis

> CDS6344 – Social Media Computing Assignment

## 📋 Project Information

| Item                 | Details                               |
| -------------------- | ------------------------------------- |
| **Course**           | CDS6344 – Social Media Computing      |
| **Project Title**    | TikTok App Reviews Sentiment Analysis |
| **Tutorial Section** | TC1L / TT1L                           |
| **Group Number**     | G0X                                   |

### 👥 Team Members

| Member                           | Student ID   | Responsibility                   |
| -------------------------------- | ------------ | ---------------------------------|
| Arvind A/L Gopalakrishna Thevar  | 1211104071   | Data Preprocessing               |
| Santoshkumar A/L K Munusamy      | 241UC240LW   | Modeling (ML, DL & Transformers) |
| Member 3                         | XXXXXXXX     | Evaluation & Visualization       |

---

# 📖 Project Overview

This project performs **Sentiment Analysis on TikTok App Reviews** using multiple Natural Language Processing (NLP) approaches, ranging from traditional Machine Learning models to modern Deep Learning and Transformer-based architectures.

The objective is to classify user reviews into sentiment categories and compare the effectiveness of different modeling techniques through comprehensive evaluation metrics and visualizations.

---

# 🚀 Project Pipeline

The complete workflow is implemented in **`Assignment_CDS6344.ipynb`** and consists of three major phases:

## 1️⃣ Data Preprocessing

* Dataset loading and inspection
* Data cleaning and normalization
* Text tokenization
* Stopword removal
* Exploratory Data Analysis (EDA)
* Word Cloud generation
* Sentiment distribution visualization

---

## 2️⃣ Model Development

### Traditional Machine Learning Models

* Logistic Regression
* Support Vector Machine (SVM)

### Deep Learning Models

* Long Short-Term Memory (LSTM)
* Convolutional Neural Network (CNN)

### Transformer-Based Model

* DistilBERT

Model training includes:

* Hyperparameter optimization
* GPU acceleration support
* Performance comparison across architectures

---

## 3️⃣ Evaluation & Visualization

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Additional analyses include:

* Model benchmarking
* Performance comparison charts
* Aspect-Based Sentiment Analysis (ABSA) visualizations
* Word Clouds and sentiment distribution graphs

---

# 📂 Repository Structure

```text
TikTok-App-Reviews-Sentiment-Analysis/
│
├── Assignment_CDS6344.ipynb                 # Main Jupyter Notebook
├── TikTok Reviews Sentiment Analysis.csv    # Raw dataset
├── images/                                  # Visualization screenshots
└── README.md                                # Project documentation

```

---

# 🛠️ Technologies Used

### Programming Language

* Python 3.x

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn
* TensorFlow / Keras
* Transformers (Hugging Face)
* WordCloud

### Models

* Logistic Regression
* Support Vector Machine (SVM)
* LSTM
* CNN
* DistilBERT

---

# ▶️ How to Run

## Option 1: Google Colab (Recommended)

### Step 1

Open the notebook:

```text
Assignment_CDS6344.ipynb
```

### Step 2

Select GPU runtime:

```text
Runtime → Change Runtime Type → T4 GPU
```

### Step 3

Run the entire notebook:

```text
Runtime → Run All
```

The notebook will automatically execute:

* Data preprocessing
* Model training
* Evaluation
* Visualization generation

---

## Option 2: Local Environment

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Assignment_CDS6344.ipynb
```

Run all cells sequentially.

---

# 📊 Sample Outputs

The repository contains generated visualizations including:

* Word Clouds
* Sentiment Distribution Charts
* Confusion Matrices
* Model Comparison Graphs
* Aspect-Based Sentiment Analysis (ABSA) Visualizations

All screenshots can be found in the **`images/`** directory.

---

# 📈 Results Summary

The project benchmarks multiple NLP approaches and compares their effectiveness for sentiment classification on TikTok app reviews.

Evaluation metrics include:

| Metric    |
| --------- |
| Accuracy  |
| Precision |
| Recall    |
| F1-Score  |

The results provide insights into the strengths and limitations of:

* Traditional Machine Learning
* Deep Learning
* Transformer-based architectures

---

# 🔮 Future Work

Several improvements can be explored in future research:

### Aspect-Based Sentiment Analysis (ABSA)

Move beyond document-level sentiment classification by implementing fine-tuned BERT-based ABSA models to identify specific application features that influence user sentiment.

### Real-Time Deployment

Deploy the best-performing model (LSTM/CNN) through a web application using:

* Streamlit
* Flask
* FastAPI

This would enable real-time sentiment monitoring for newly submitted TikTok reviews.

### Transformer Optimization

Improve Transformer performance by:

* Learning rate scheduling
* Hyperparameter tuning
* Extended training epochs
* Better class balancing

Future experiments may also evaluate larger Transformer architectures such as:

* RoBERTa
* DeBERTa
* BERT-large

for enhanced contextual understanding and higher classification accuracy.

---

# 📜 License

This repository was developed solely for academic purposes as part of the **CDS6344 Social Media Computing** course.

---

## ⭐ Acknowledgements

Special thanks to the course lecturer and teammates for their guidance, collaboration, and contributions throughout this project.
