# AI/ML Virtual Internship — Classification & Prediction Systems using Machine Learning

**IILM University, Greater Noida** | **SmartED Innovations** | **3rd Semester Internship (EduSkill)**

* * *

## 📂 Quick Access

* 📄 [View Internship Report](./Internship_Report_Bappaditya_Das_25SCS1003002304.pdf)
* 📊 [View Presentation (PPT)](./Internship_PPT_Bappaditya_Das_25SCS1003002304.pdf)
* 🎓 [View Completion Certificates](./Internship_Completion_Certificates_Bappaditya_Das_25SCS1003002304.pdf)

* * *

## Table of Contents

1. [Candidate Profile](#candidate-profile)
2. [Internship Overview](#internship-overview)
3. [Repository Structure](#repository-structure)
4. [Problem Statement](#problem-statement)
5. [Project Objectives](#project-objectives)
6. [Scope of Work](#scope-of-work)
7. [Tech Stack](#tech-stack)
8. [System Architecture](#system-architecture)
9. [Methodology](#methodology)
10. [Training Log Book — Module-wise Summary](#training-log-book--module-wise-summary)
11. [Expected Outcomes](#expected-outcomes)
12. [Skills Gained](#skills-gained)
13. [Documents Included](#documents-included)
14. [Declaration](#declaration)
15. [Acknowledgements](#acknowledgements)
16. [Author](#author)

* * *

## Candidate Profile

| Field | Details |
| --- | --- |
| Name | Bappaditya Das |
| Roll No. | 25SCS1003002304 |
| Course & Branch | B.Tech, Computer Science & Engineering (AI/ML) |
| Semester / Batch | 3rd Semester, 2026–27 |
| University | IILM University, Greater Noida, Uttar Pradesh |
| School | School of Computer Science and Engineering |
| Degree Requirement | Submitted in partial fulfilment of the requirement for the degree of B.Tech CSE |

* * *

## Internship Overview

| Field | Details |
| --- | --- |
| Internship Title | AI/ML Virtual Internship: Classification and Prediction Systems using Machine Learning |
| Host Organization | SmartED Innovations |
| Organization Type | Bengaluru-based Ed-Tech company |
| Core Domains (Org) | Artificial Intelligence, Data Science, Web Development, Cyber Security |
| Mode | Virtual / Remote |
| Curriculum Structure | 6 structured theory modules + 2 independent hands-on ML projects |
| Learning Model | Conceptual/theory sessions combined with guided, hands-on project work |

SmartED Innovations partners with universities to deliver industry-oriented virtual internship programs across emerging technology domains, enabling students to apply classroom learning to practical problems while working remotely.

* * *

## Repository Structure

    bappaditya25scs1003002304-cyber/
    │
    ├── README.md                                                      → This file (quick links + full documentation)
    ├── Internship_Report_Bappaditya_Das_25SCS1003002304.pdf           → Full internship report (university format)
    ├── Internship_PPT_Bappaditya_Das_25SCS1003002304.pdf              → Viva / evaluation presentation deck
    └── Internship_Completion_Certificates_Bappaditya_Das_25SCS1003002304.pdf   → Offer letter + Certificate of Completion

> All files sit at the repository root for one-tap access on both desktop and mobile — no folder-hunting required. Use the **Quick Access** links above to jump straight to any resource.

* * *

## Problem Statement

The internship's practical component was centred on two distinct, real-world-style, data-driven problems:

**1. NYC Room Classification**Given a dataset of room/property listings from New York City — with attributes such as location (borough/neighbourhood), room type, price, minimum nights, and availability — the task was to build a **classification model** capable of categorising listings (e.g., by room type or price category).

**2. Mental Health Score Prediction**Given a dataset of lifestyle and behavioural indicators (sleep patterns, screen time, physical activity, stress-related factors), the task was to build a **regression model** capable of estimating a continuous Mental Health Score and identifying the factors that influence it most.

Together, these represent the two foundational supervised-learning paradigms: **classification** and **regression**.

* * *

## Project Objectives

* Understand and apply the end-to-end Machine Learning workflow, from raw data to a working predictive model.
* Perform data cleaning, exploratory data analysis (EDA), and feature engineering on real-world style datasets.
* Implement and compare classification algorithms for the NYC room classification task.
* Implement a regression-based model for mental health score prediction and interpret feature influence.
* Evaluate model performance using appropriate metrics and visualise results for interpretability.
* Gain hands-on exposure to Python's data-science ecosystem (Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn).

* * *

## Scope of Work

Both projects are educational, proof-of-concept implementations built on publicly available/sample datasets and are **not intended for production deployment**:

* The NYC room classification model is restricted to the features present in the dataset used and does not incorporate real-time listing data.
* The mental health score prediction system demonstrates how lifestyle indicators can be modelled statistically to estimate a wellness-related score — it is **not** a diagnostic or clinical tool.
* The focus throughout was on correctly applying the ML pipeline rather than achieving production-grade accuracy.

* * *

## Tech Stack

| Category | Tools / Libraries |
| --- | --- |
| Programming Language | Python 3 |
| Data Handling | Pandas, NumPy |
| Machine Learning | Scikit-learn — classification & regression models, train-test split, evaluation metrics |
| Data Visualisation | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook / Google Colab |
| Tooling Consistency | Standard Anaconda/Python data-science distribution |

* * *

## System Architecture

Both systems follow the standard supervised Machine Learning pipeline:

     ┌────────────────┐   ┌───────────────────┐   ┌─────────────────────┐   ┌────────────────┐   ┌───────────────────┐   ┌──────────────────┐
     │ Data Collection │→ │ Data Preprocessing │→ │ Feature Engineering │→ │ Model Training │→ │ Model Evaluation │→ │ Prediction Output │
     └────────────────┘   └───────────────────┘   └─────────────────────┘   └────────────────┘   └───────────────────┘   └──────────────────┘

Raw data is collected → cleaned and preprocessed → relevant features are engineered/selected → a model is trained on the processed data → the trained model is evaluated on unseen (test) data → predictions are generated on new inputs.

* * *

## Methodology

### NYC Room Classification

1. **Data Loading & Cleaning** — loaded with Pandas; missing values handled via imputation/row removal; high-cardinality ID columns dropped.
2. **Exploratory Data Analysis** — distribution of listings by borough, room type, and price range visualised.
3. **Feature Encoding** — categorical features (neighbourhood group, room type) encoded via Label/One-Hot Encoding.
4. **Train-Test Split** — 80:20 split using Scikit-learn's `train_test_split`.
5. **Model Training** — Logistic Regression, Decision Tree, Random Forest Classifier.
6. **Evaluation** — Accuracy score, Confusion Matrix, Precision/Recall.

### Mental Health Score Prediction

1. **Data Loading & Cleaning** — lifestyle/behavioural indicators (sleep, screen time, exercise, social interaction) loaded and cleaned.
2. **Exploratory Data Analysis** — correlation heatmaps and scatter plots against the target score to identify trends and outliers.
3. **Feature Scaling** — numerical features scaled/normalised for comparability.
4. **Train-Test Split** — for unbiased evaluation.
5. **Model Training** — Linear Regression, Random Forest Regressor.
6. **Evaluation** — MAE, MSE, R² score, and feature importance analysis.

* * *

## Training Log Book — Module-wise Summary

| Module | Title | Key Topics Covered |
| --- | --- | --- |
| 1   | Introduction to AI and Python Essentials | What is AI, Types of AI, Python essentials, NumPy & Pandas, Mathematical foundations & statistics |
| 2   | Problem Solving Agents and Search Algorithms | Agents & rationality, PEAS framework, Problem formulation & state space, Uninformed & Informed search, Search limitations |
| 3   | Rule-Based Systems and Traditional Machine Learning | Rule-based & expert systems, Supervised learning (regression & classification), Model evaluation metrics, Overfitting & regularization, End-to-end ML pipeline |
| 4   | Unsupervised Learning and Probabilistic Reasoning | Clustering (K-Means, Hierarchical), Dimensionality reduction, Bayes' theorem, Naive Bayes classifier, Bayesian networks |
| 5   | Deep Learning and Computer Vision | Neural network foundations, Backpropagation & training, TensorFlow, Keras, PyTorch |
| 6   | NLP, Generative AI and Industry Applications | Text preprocessing, Vectorisation techniques, Sentiment analysis pipeline, Transformers, GPT, Prompt engineering |

* * *

## Expected Outcomes

* A working classification model that categorises NYC room listings with reasonable accuracy based on the chosen features.
* A working regression model that estimates a Mental Health Score from lifestyle indicators, with insight into the most influential factors.
* Practical, transferable familiarity with the full Machine Learning workflow — data cleaning, EDA, feature engineering, model training, and evaluation — using industry-standard Python tools.
* A foundation for further exploration of more advanced algorithms and larger, real-world datasets in future coursework or projects.

* * *

## Skills Gained

* **Technical:** Python programming, data wrangling with Pandas/NumPy, supervised ML (classification & regression), model evaluation, data visualisation.
* **Conceptual:** AI foundations, search algorithms, probabilistic reasoning, deep learning fundamentals, NLP & generative AI basics.
* **Professional:** Structuring an end-to-end ML project, technical documentation, and presenting technical work for evaluation.

* * *

## Documents Included

| Document | Description |
| --- | --- |
| [Internship Report](./Internship_Report_Bappaditya_Das_25SCS1003002304.pdf) | Complete report following the university-prescribed format — Candidate's Declaration, Acknowledgement, Table of Contents, List of Tables/Figures, Project Description, Training Log Book, and Bibliography. |
| [Presentation](./Internship_PPT_Bappaditya_Das_25SCS1003002304.pdf) | Slide deck summarising the internship, organization, problem statements, architecture, methodology, and outcomes, for viva/evaluation. |
| [Completion Certificates](./Internship_Completion_Certificates_Bappaditya_Das_25SCS1003002304.pdf) | Internship offer letter and Certificate of Internship Completion issued by SmartED Innovations. |

* * *

## Declaration

This repository and its contents (report, presentation, and associated documents) have been prepared by the candidate named above to fulfil the 3rd Semester Internship requirement for the degree of B.Tech in Computer Science & Engineering at IILM University, Greater Noida, and have not been submitted elsewhere for any other degree or diploma requirement.

* * *

## Acknowledgements

I would like to thank **SmartED Innovations** for the opportunity to undergo this Virtual Internship in Artificial Intelligence and Machine Learning, and the faculty of the **School of Computer Science and Engineering, IILM University, Greater Noida**, for their continuous support and guidance throughout this internship.

* * *

## Author

**Bappaditya Das**B.Tech CSE (AI/ML) — IILM University, Greater NoidaRoll No.: 25SCS1003002304
