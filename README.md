# ai-data-quality-analysis

# AI Data Quality and Human Annotation Analysis

This repository explores how **human-labeled datasets** influence machine learning model performance.  
Through exploratory data analysis and visualization, these notebooks examine **label noise, annotator reliability, and dataset quality**, and propose strategies to improve training data.

Human annotations are widely used in modern AI systems for training and evaluation. However, inconsistencies across annotators can introduce **noisy labels**, which may negatively affect model performance. These projects investigate methods for analyzing and improving the reliability of human-labeled datasets.

---

## Repository Contents

### 1. AI Preference Data Analysis

**Notebook:** `AI_Preference_Data_Analysis.ipynb`

This notebook analyzes a human preference dataset to understand how **annotator agreement and label noise** affect the quality of training signals.

Key topics explored:

- Exploratory analysis of human preference datasets
- Measuring annotator agreement
- Identifying potential label noise
- Designing weighting strategies to improve training data quality
- Connecting dataset quality to model evaluation metrics

The notebook also proposes a **data weighting framework** that incorporates:

- annotator reliability
- agreement rate
- number of annotations

to reduce the impact of noisy labels.

GitHub:  
https://github.com/jachou27/ai-data-quality-analysis/blob/main/AI_Preference_Data_Analysis.ipynb

Run in Colab:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jachou27/ai-data-quality-analysis/blob/main/AI_Preference_Data_Analysis.ipynb)

---

### 2. SNLI Label Noise and Annotator Reliability Analysis

**Notebook:** `SNLI_Label_Noise_Annotator_Reliability_Analysis.ipynb`

This notebook analyzes the **Stanford Natural Language Inference (SNLI)** dataset to evaluate annotator reliability and identify potential label noise.

Key analyses include:

- measuring agreement between annotators and gold labels
- visualizing annotator agreement patterns
- identifying low-confidence examples
- distinguishing between **label noise** and **low-confidence labels**
- proposing strategies to improve dataset quality

The notebook introduces a **row-weighting framework** based on:

- annotator reliability
- agreement rate
- number of annotations

to improve the quality of training data used for machine learning models.

GitHub:  
https://github.com/jachou27/ai-data-quality-analysis/blob/main/SNLI_Label_Noise_Annotator_Reliability_Analysis.ipynb

Run in Colab:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jachou27/ai-data-quality-analysis/blob/main/SNLI_Label_Noise_Annotator_Reliability_Analysis.ipynb)

---

## Key Insights

Across both analyses, several important observations emerge:

- Human-labeled datasets often contain **annotator disagreement**
- Low agreement examples may introduce **label noise**
- Annotator reliability varies across contributors
- Dataset quality can be improved by incorporating **agreement and reliability signals**

Understanding these factors is important for improving **AI training data quality**, especially in systems that rely heavily on human annotations.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter / Google Colab

---

## Author

Jason Chou 
