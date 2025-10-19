# Portfolio of Studies: Data Mining and Machine Learning (H9DMML)

**Course:** MSc in Data Analytics  
**Module:** Data Mining and Machine Learning (H9DMML)  
**Lecturer:** Jaswinder Singh  
**Assessment:** Portfolio of Studies (40%)  
**Student:** Muralidhar Kukkala  
**Course Code:** MSCDAD_JAN25A_I  

---

## 📘 Overview

This submission contains two in-depth Jupyter Notebooks, each exploring a real-world dataset and solving a specific business problem using modern machine learning and data analysis techniques:

1. **Smartwatch Health Data** – Classification of stress levels using biometric data.
2. **Netflix Titles Data** – Recommender system using content-based filtering and clustering.

Each notebook includes:

- Comprehensive data preprocessing, feature engineering, and exploratory data analysis (EDA)
- Implementation of at least two advanced models
- Detailed evaluation using visual and statistical diagnostics
- Modular, well-documented, and reproducible code

---

## 📁 Directory Structure

```
.
├── netflix_recommendation_system.ipynb
├── smartwatch_stress_level_analysis.ipynb
├── Smartwatch_data.csv
├── netflix_titles.csv
├── README.md
├── requirements.txt
```

---

## 📊 Notebook Summaries

### 1. 📱 Smartwatch Health Data – Stress Level Classification

**Notebook:** `smartwatch_stress_level_analysis.ipynb`  
**Dataset:** `Smartwatch_data.csv` (Kaggle source)

#### Key Highlights:

- **Target Variable:** `Stress_Level` – predicted using phsiological signals
- **Preprocessing Pipeline:**
  - Missing value imputation
  - Outlier treatment
  - Encoding categorical variables
  - Feature scaling
- **Feature Engineering:**
  - Feature importance analysis
  - Recursive Feature Elimination with Cross-Validation (RFECV)
- **Modeling Techniques:**
  - Stacking Ensemble
  - Light GBM 
  - XGBoost Classifier
  - Baseline Logistic Regression
- **Model Evaluation:**
  - Accuracy, Precision, Recall, F1 Score
  - ROC-AUC, Confusion Matrix
  

---

### 2. 🎬 Netflix Data – Recommender System and Clustering

**Notebook:** `netflix_recommendation_system.ipynb`  
**Dataset:** `netflix_titles.csv` (Kaggle source)

#### Key Highlights:

- **EDA & Preprocessing:**
  - Missing value handling
  - Country, genre, and release year analysis
- **Content-Based Filtering:**
  - TF-IDF vectorization of genres, cast, and director
  - Cosine similarity to recommend similar titles
- **Unsupervised Learning:**
  - K-Means Clustering with evaluation using Silhouette Scores
  - Dimensionality Reduction with t-SNE
- **Hybrid Recommendation:**
  - Combines content and cluster info for improved suggestions
- **Evaluation & Visualization:**
  - Cluster interpretation
  - Genre-match scoring
  - Interactive and static plots using Matplotlib & Seaborn

---

## ▶️ How to Run the Notebooks

### ✅ Requirements

Ensure Python ≥ 3.8 is installed. Then install the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

_Optional:_

```bash
pip install tsne-learn tqdm nltk
```

### 🧪 Steps

1. Download or clone this directory and the datasets.
2. Keep all files in the same directory.
3. Launch Jupyter Notebook/Lab or open in Google Colab.
4. Run:
   - `smartwatch_stress_level_analysis.ipynb`
   - `netflix_recommendation_system.ipynb`

Each notebook includes pre-run outputs for ease of assessment.

---

## 📝 Notes

- Code is modular, reproducible, and well-commented.
- Outputs (plots, tables, diagnostics) are fully visible and not hidden.
- Only analysis and result interpretation are included in the Research Report as per academic guidelines.
- Follow notebook markdown cells for workflow navigation and understanding.

---

## 📚 Dataset Attribution

- **Smartwatch Data:** [Smartwatch Health Data (Uncleaned) - Kaggle](https://www.kaggle.com/datasets/mohammedarfathr/smartwatch-health-data-uncleaned/data)
- **Netflix Data:** [Netflix Data Cleaning, Analysis and Visualization - Kaggle](https://www.kaggle.com/datasets/ariyoomotade/netflix-data-cleaning-analysis-and-visualization/data)

_Citations and academic references are included in the accompanying Research Report._
