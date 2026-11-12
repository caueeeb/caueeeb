[GITHUB_PROFILE_README_DRAFT.md](https://github.com/user-attachments/files/34729310/GITHUB_PROFILE_README_DRAFT.md)
# Hi, I'm Cauê Buzolin 👋

**Analysis and Systems Development (ADS) student | Machine Learning & AI Engineering projects**

I am an ADS student at Fatec Taquaritinga, interested in building practical software and machine learning projects. I use Python and data analysis to explore real-world problems, train models, evaluate their limitations, and expose predictions through APIs.

## Featured projects

### 1. E-commerce Delivery Delay Prediction — Olist

A machine learning project that investigates late-delivery prediction using the Brazilian Olist e-commerce dataset.

- Built a dataset of 96,470 delivered orders and engineered 26 model features.
- Compared classification models and evaluated the selected Logistic Regression model with a chronological train/validation/test split.
- Exposed predictions through a FastAPI application with `/health`, `/model-info`, and `/predict` endpoints.
- Added automated tests; 13 tests passed in the local test suite.
- Investigated temporal distribution shift, monthly performance, classification errors, and probability calibration.

**Repository:** [delivery-prediction-ml](https://github.com/caueeeb/delivery-prediction-ml)

### 2. Titanic Survival Prediction — Kaggle

A binary-classification project for the Kaggle Titanic competition.

- Performed exploratory data analysis and feature engineering.
- Compared Logistic Regression, Random Forest, Extra Trees, and SVM using stratified cross-validation.
- Built a scikit-learn pipeline and generated the competition submission.
- **Kaggle score: 0.77033.**

**Repository:** [kaggle-titanic](https://github.com/caueeeb/kaggle-titanic)  
**Hugging Face model:** [titanic-survival-logistic-regression](https://huggingface.co/caueeb/titanic-survival-logistic-regression)

## Technical research and writing

- **Temporal distribution shift in e-commerce delivery prediction:** an empirical study of changing feature distributions, target prevalence, monthly classification performance, false alerts, and probability quality.
- **Research and article source:** [Olist research folder](https://github.com/caueeeb/delivery-prediction-ml/tree/main/research)
- **Technical article:** [When Machine Learning Models Meet Temporal Distribution Shift](https://github.com/caueeeb/delivery-prediction-ml/blob/main/research/ARTICLE_TEMPORAL_DISTRIBUTION_SHIFT.md)

## Technologies

- **Programming:** Python, SQL, C
- **Data and machine learning:** pandas, NumPy, scikit-learn, Matplotlib, Seaborn
- **APIs and testing:** FastAPI, Uvicorn, pytest
- **Tools:** Git, GitHub, VS Code, Jupyter Notebook, MySQL

## Current focus

Developing practical skills in machine learning, model evaluation, data analysis, API development, and communicating technical findings.
