# divyavankudothu-AI-Based-Employee-Wellness-Management-platform
# AI-Based Employee Wellness Management Platform

> **An AI-powered platform for analyzing employee feedback through Natural Language Processing, Sentiment Analysis, and Transformer-based Emotion Classification to generate meaningful wellness insights.**

---

## 📌 Project Overview

The **AI-Based Employee Wellness Management Platform** is an Artificial Intelligence and Natural Language Processing project developed as part of an **Infosys Internship Milestone Project**.

The primary objective of the project is to analyze textual employee feedback and identify sentiment and emotional patterns using Machine Learning and advanced Transformer-based NLP models.

The system combines **Sentiment Analysis** and **Emotion Classification** to transform unstructured employee feedback into structured insights that can support data-driven employee wellness initiatives.

The project is designed with a strong focus on **responsible AI, privacy, and non-clinical wellness analysis**.

---

## 🎯 Project Objectives

The major objectives of this project are:

* Analyze employee feedback using Natural Language Processing.
* Identify sentiment expressed in textual feedback.
* Detect specific emotions associated with employee feedback.
* Apply Transformer-based models for advanced text classification.
* Compare NLP model performance using standard evaluation metrics.
* Generate confidence scores for model predictions.
* Convert unstructured textual feedback into meaningful analytical insights.
* Establish a foundation for an intelligent employee wellness platform.
* Follow privacy-aware and responsible AI principles.

---

# 🏗️ System Workflow

```text
                    Employee Feedback
                           │
                           ▼
                  Text Preprocessing
                           │
                           ▼
                  NLP Text Processing
                           │
             ┌─────────────┴─────────────┐
             │                           │
             ▼                           ▼
      Sentiment Analysis          Emotion Classification
             │                           │
             ▼                           ▼
      Sentiment Result           BERT / DistilBERT
             │                           │
             └─────────────┬─────────────┘
                           ▼
                    Model Prediction
                           │
                           ▼
                  Confidence Scores
                           │
                           ▼
                  Wellness Insights
                           │
                           ▼
                 Future Platform Layer
```

---

# 🚀 Project Milestones

## Milestone 1 — Sentiment Analysis

### Objective

The first milestone focuses on analyzing employee feedback and identifying the sentiment expressed in the text.

### Key Components

* Text preprocessing
* Natural Language Processing
* Sentiment classification
* Model prediction
* Performance evaluation
* Sentiment-based analysis

### Workflow

```text
Raw Employee Feedback
        ↓
Text Preprocessing
        ↓
NLP Processing
        ↓
Sentiment Model
        ↓
Sentiment Prediction
        ↓
Evaluation & Analysis
```

### Status

**Completed ✅**

---

# Milestone 2 — Emotion Classification

### Objective

The second milestone extends the NLP pipeline by identifying the specific emotion expressed in employee feedback.

Transformer-based architectures were explored for emotion classification, including:

* **BERT**
* **DistilBERT**

### Emotion Classes

The project considers the following six emotion categories:

| Emotion     | Description                                                   |
| ----------- | ------------------------------------------------------------- |
| 😊 Joy      | Happiness, satisfaction, or positive emotional expression     |
| 😢 Sadness  | Disappointment, unhappiness, or negative emotional expression |
| 😡 Anger    | Frustration, irritation, or anger                             |
| 😨 Fear     | Worry, uncertainty, or fear                                   |
| 😲 Surprise | Unexpected events or reactions                                |
| 🤢 Disgust  | Strong dislike, dissatisfaction, or aversion                  |

### Model Evaluation

The emotion classification models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Macro F1-Score

**Macro F1** is used as an important comparison metric because it evaluates performance across individual emotion classes and gives equal importance to each class.

### Prediction Output

The model produces:

```text
Input Employee Feedback
        ↓
Predicted Emotion
        ↓
Confidence Score
```

### Status

**Completed ✅**

---

# 🧠 Technology Stack

## Programming

* **Python**

## Machine Learning

* **Scikit-learn**
* **PyTorch**

## Natural Language Processing

* NLP
* Text Classification
* Sentiment Analysis
* Emotion Classification
* Tokenization
* Transformer-based NLP

## Transformer Models

* **BERT**
* **DistilBERT**

## Development Environment

* **Google Colab**
* **Jupyter Notebook**

## Version Control

* **Git**
* **GitHub**

---

# 📊 Model Evaluation

The project uses standard classification metrics to evaluate model performance.

### Accuracy

Measures the proportion of correctly classified samples.

```text
Accuracy = Correct Predictions / Total Predictions
```

### Precision

Measures how many of the samples predicted as a particular class actually belong to that class.

### Recall

Measures how many of the actual samples belonging to a class were correctly identified.

### F1-Score

The F1-score provides a balance between precision and recall.

```text
F1 = 2 × (Precision × Recall)
     ──────────────────────────
       Precision + Recall
```

### Macro F1-Score

Macro F1 calculates the F1-score independently for each class and then averages the results.

This is particularly useful for multi-class emotion classification.

---

# 📁 Repository Structure

```text
AI-Employee-Wellness-Management-Platform/
│
├── Milestone-1/
│   ├── notebooks/
│   ├── models/
│   ├── results/
│   └── README.md
│
├── Milestone-2/
│   ├── notebooks/
│   ├── models/
│   ├── results/
│   └── README.md
│
├── docs/
│   ├── Project-Report.pdf
│   └── Milestone-Documentation.pdf
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

> The folder structure should be updated to match the actual files in the repository.

---

# ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Employee-Wellness-Management-Platform.git
```

### 2. Navigate to the Project

```bash
cd AI-Employee-Wellness-Management-Platform
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

The project notebooks can be executed using **Google Colab**, **Jupyter Notebook**, or **JupyterLab**.

For Jupyter Notebook:

```bash
jupyter notebook
```

Then open the relevant notebook under the corresponding milestone directory.

For Google Colab, upload/open the notebook and execute the cells sequentially.

---

# 🔬 Project Methodology

The project follows a structured NLP workflow:

### Step 1 — Data Preparation

Employee feedback data is prepared for analysis.

### Step 2 — Text Preprocessing

Text is prepared for NLP processing using appropriate preprocessing and tokenization techniques.

### Step 3 — Sentiment Analysis

The sentiment of employee feedback is analyzed as part of Milestone 1.

### Step 4 — Emotion Classification

Milestone 2 uses Transformer-based models to classify feedback into six emotion categories.

### Step 5 — Model Evaluation

The models are evaluated using multiple classification metrics.

### Step 6 — Confidence Analysis

Prediction confidence is considered alongside the predicted class.

### Step 7 — Wellness Insights

The analyzed results provide a foundation for generating employee wellness-related insights.

---

# 🔐 Privacy & Responsible AI

Employee wellness data may contain sensitive information. Therefore, privacy and responsible AI are important considerations in this project.

The project follows principles such as:

* Avoiding unnecessary Personally Identifiable Information (PII).
* Using anonymized or appropriately protected data for experimentation.
* Avoiding unnecessary exposure of individual employee information.
* Using aggregated insights where appropriate.
* Treating model predictions as probabilistic outputs.
* Communicating the limitations of AI-generated predictions.
* Avoiding medical or psychological diagnosis.

### Important Disclaimer

> This project is intended for educational, research, and workplace wellness-support purposes. Sentiment and emotion predictions are AI-generated probabilistic outputs and should not be interpreted as medical, psychological, or clinical diagnoses.

---

# 📈 Current Progress

| Project Component                    | Status |
| ------------------------------------ | :----: |
| Project Planning                     |    ✅   |
| Data Preparation                     |    ✅   |
| Milestone 1 – Sentiment Analysis     |    ✅   |
| Milestone 2 – Emotion Classification |    ✅   |
| BERT Model Experimentation           |    ✅   |
| DistilBERT Model Experimentation     |    ✅   |
| Model Evaluation                     |    ✅   |
| GitHub Repository                    |   🔄   |
| Platform Integration                 |   🔄   |
| Wellness Recommendation System       |   🔄   |
| Deployment                           |   🔄   |

---

# 🔮 Future Scope

The project can be further extended into a complete employee wellness platform with features such as:

* Interactive wellness dashboards
* Personalized wellness recommendations
* Employee wellness trend analysis
* Burnout-risk trend monitoring
* Multilingual feedback analysis
* Large Language Model (LLM) integration
* Retrieval-Augmented Generation (RAG)
* Explainable AI
* Secure database integration
* Role-based access control
* Anonymous organizational-level analytics
* Cloud-based deployment
* Real-time feedback analysis

---

# 🛡️ Responsible Use

The platform should be used to **support**, rather than replace, human decision-making.

AI predictions should not be used as the sole basis for employment decisions, disciplinary actions, medical conclusions, or psychological assessments.

Wellness insights should be interpreted with appropriate organizational policies, privacy safeguards, and human oversight.

---

# 👩‍💻 Author

**V. Divya**

**B.Tech – Computer Science & Engineering**

**Infosys Internship Milestone Project**

---

# 📄 License

This project is licensed under the **MIT License**.

See the [`LICENSE`](LICENSE) file for details.

---

# 🙏 Acknowledgement

This project was developed as part of an **Infosys Internship Milestone Project**, applying Artificial Intelligence, Machine Learning, Natural Language Processing, and Transformer-based models to the domain of employee wellness.

---

## ⭐ Project Status

**Milestone 1: Completed ✅**
**Milestone 2: Completed ✅**

Further milestones will focus on extending the NLP components into a more comprehensive employee wellness management platform.
