# 🎓 Transformer-Based Approaches for Automated Detection of Suicidal Ideation on Social Media

**B.Eng. Graduation Thesis Project | College of Software Engineering, Sichuan University**

---

### 🧑‍🎓 Student Information

| Role | Name | ID | Advisor | Major |
|------|------|----|----------|--------|
| 👨‍💻 Student | **Shakib Al Hasan** | 2021521460124 | **Dr. Dasha Hu**, Associate Professor | Software Engineering |

---

## ✨ Overview

This repository encapsulates the **complete source code, experimental notebooks, results, and thesis manuscript** of my Bachelor of Engineering graduation project:  
**“Transformer-Based Approaches for Automated Detection of Suicidal Ideation on Social Media.”**

This work presents the **first comprehensive cross-paradigm evaluation** of suicide ideation detection systems — spanning **classical machine learning**, **deep learning**, and **state-of-the-art transformer models** — applied to over **232,000 Reddit comments**.

> 🧠 **Key Insight:**  
> Fine-tuned **BERT** models achieved an **F1-score of 97.63%** and **AUC = 1.0**, decisively outperforming traditional and deep learning approaches — highlighting the power of contextual embeddings for early suicide risk detection.

---

## 🧩 Highlights & Contributions

- **🚀 Decisive Benchmark:**  
  Achieved **F1 = 97.63%** and **AUC = 1.0** using fine-tuned BERT, setting a new reproducible benchmark for suicide ideation classification.

- **🔍 Methodological Rigor:**  
  Implemented and compared **10 computational models** — including Logistic Regression, Naive Bayes, SVM, Random Forest, CNN, LSTM, BERT, and RoBERTa hybrids — under a unified preprocessing and evaluation pipeline.

- **🧼 Custom NLP Pipeline:**  
  Developed a **specialized text preprocessing framework** preserving subtle linguistic cues (e.g., negations, personal pronouns) critical in mental health data.

- **⚖️ Ethical Sensitivity:**  
  Prioritized minimizing **false negatives (missed detections)** through detailed ROC and precision-recall analyses to ensure practical and ethical reliability.

---

## 📂 Repository Structure

suicidal-ideation-detection-transformers/
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── 1_Data_and_Preprocessing/
│   ├── data_cleaning.ipynb
│   ├── preprocessing_pipeline.py
│   └── raw_data/                     # (Empty placeholder for dataset CSV)
│
├── 2_Model_Training_and_Evaluation/
│   │
│   ├── 2.1_Classical_ML/
│   │   ├── logistic_regression/
│   │   ├── naive_bayes/
│   │   ├── random_forest/
│   │   ├── svm/
│   │   ├── classical_ml_all.ipynb
│   │   └── all_models_combined.py
│   │
│   ├── 2.2_Deep_Learning/
│   │   ├── cnn_model.ipynb
│   │   ├── lstm_model.ipynb
│   │   ├── cnn_lstm_hybrid.ipynb
│   │   └── saved_models/
│   │
│   └── 2.3_Transformer_Models/
│       ├── bert_finetuning.ipynb
│       ├── roberta_lstm_hybrid.ipynb
│       ├── roberta_san_model.ipynb
│       └── saved_models/
│
├── 3_Results_and_Analysis/
│   ├── model_comparison.ipynb
│   ├── combined_roc_curves.pdf
│   ├── metrics_summary.csv
│   └── performance_plots/
│
└── 0_Thesis_Document/
├── 2021521460124_thesis.pdf
└── presentation_slides.pptx



---

## ⚙️ Installation & Reproducibility

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/shakib2412/suicidal-ideation-detection-transformers.git
cd suicidal-ideation-detection-transformers
````

### 2️⃣ Install Dependencies

Requires **Python ≥ 3.8**

```bash
pip install -r requirements.txt
```

### 3️⃣ Download the Dataset

**Dataset:** [Suicide and Depression Detection (Kaggle)](https://www.kaggle.com)
Place the downloaded CSV (e.g., `Suicide_Detection.csv`) into:

```
1_Data_and_Preprocessing/raw_data/
```

### 4️⃣ Run the Project

Execute notebooks in sequential order:

1. `1_Data_and_Preprocessing/data_cleaning.ipynb`
2. `2_Model_Training_and_Evaluation/` notebooks
3. `3_Results_and_Analysis/model_comparison.ipynb`

---

## 📈 Key Experimental Results

| Paradigm             | Example Model       | F1-Score  | Key Insight                                                         |
| -------------------- | ------------------- | --------- | ------------------------------------------------------------------- |
| 🧠 **Transformer**   | BERT                | **0.976** | Bidirectional encoding captured contextual nuances most effectively |
| 🧬 **Deep Learning** | LSTM                | 0.930     | Strong sequential modeling but limited context depth                |
| ⚙️ **Classical ML**  | Logistic Regression | 0.930     | Solid baseline yet reliant on manual feature extraction             |

> All detailed charts, ROC curves, and confusion matrices are available in `3_Results_and_Analysis/`.

---

## 🧾 Thesis Abstract (2025)

> Suicide remains a global health crisis, claiming over 700,000 lives each year.
> This study presents the first cross-paradigm evaluation of suicidal ideation detection on social media, comparing classical, deep, and transformer-based models across 232,074 Reddit comments.
> The results establish **Transformer architectures (BERT, RoBERTa)** as the foundation for ethically sound, high-sensitivity suicide prevention systems, balancing detection accuracy with privacy protection and human oversight.

---

## 🧠 Technologies Used

| Category              | Tools                                  |
| --------------------- | -------------------------------------- |
| ML Frameworks         | PyTorch, TensorFlow, Scikit-learn      |
| NLP Libraries         | Hugging Face Transformers, NLTK, SpaCy |
| Data Tools            | Pandas, NumPy, Matplotlib, Seaborn     |
| Visualization         | Plotly, ROC/Confusion Metrics          |
| Deployment (optional) | Flask, Gradio                          |

---

## ⚖️ Ethical Statement

This research complies with ethical guidelines for mental health data analysis.
All datasets are publicly available and anonymized.
No personally identifiable information (PII) was accessed or processed.
The aim is **academic exploration** of NLP techniques for public health awareness.

---

## 🧩 Citation

If you find this work useful, please cite:

```bibtex
@thesis{Shakib2025SuicidalIdeation,
  author    = {Shakib Al Hasan},
  title     = {Transformer-Based Approaches for Automated Detection of Suicidal Ideation on Social Media},
  school    = {Sichuan University},
  year      = {2025},
  advisor   = {Dr. Dasha Hu}
}
```

---

## 💬 Contact

📧 **Shakib Al Hasan**
B.Eng. in Software Engineering
Sichuan University, Chengdu, China
GitHub: [@shakib2412](https://github.com/shakib2412)
