![R](https://img.shields.io/badge/R-4.4.0-blue?logo=r)
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![License](https://img.shields.io/github/license/celsomsilva/datasharing)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)



# Walmart Sales Prediction - HLM3 (Hierarchical Linear Models)  

This repository contains my thesis project, analyzing Walmart’s weekly sales using **3-level Hierarchical Linear Models (HLM3)** and comparing them with traditional **Generalized Linear Models (GLM)**.  
The goal is to show the effectiveness of **nonlinear multilevel approaches** in predicting sales across hierarchical structures.  

---

## Evaluation

- **Grade:** 9.0 (University of São Paulo - USP, 2024)  
- **Committee feedback:** *"Interesting and challenging."*  

---

## Repository Status

This repository is a **work-in-progress**. Current focus:  
- Organizing and documenting code, datasets, and figures  
- Translating thesis sections (**Portuguese → English**)  

Planned:  
- Publishing all code and documents in this repository  
- A parallel version with **analytics & storytelling**  
- Extending comparisons with **Deep Learning**  
- Building a **statistical bridge** between hierarchical models (HLM/GLMM) and modern machine learning / deep learning approaches — which resonates with the original purpose of this repository: to share and connect statistical thinking with data science practice.  


---

## Abstract

The thesis investigates Walmart’s weekly sales using a **nonlinear 3-level Hierarchical Linear Model (HLM3)**, and compares it against **generalized linear models (GLMs)** and other **generalized linear mixed models (GLLMs)**, as **Multilevel Negative Binomial**.  
The goal was to evaluate which approach best captures the hierarchical structure of **time → department → store** in retail sales forecasting.


### Modeling process:
- Null models for linear regression, nonlinear regression with **Yeo-Johnson transformation**, and HLM3.  
- Full models for linear and nonlinear regression.  
- Evaluation using **Log-Likelihood (LogLik)**, **Akaike Information Criterion (AIC)**, and **Bayesian Information Criterion (BIC)**.  

Results: multilevel models capture hierarchical patterns better, improving prediction and interpretation for decision-making.  

**Keywords:** Box-Cox, Yeo-Johnson, Multilevel Model, Hierarchical Model, Machine Learning  

---

## Project Structure
```

walmart-sales-hlm3/
│── src/
│   ├── varejo_multinivel_hlm3.R
│   ├── modelagem_multinivel.ipynb
│   ├── tratamento_de_dadosfinal.ipynb
│
│── data/
│   └── varejo_hlm_ready.csv
│
│── docs/
│   ├── TCC_REVISADO.pdf
│   ├── Apresentacao.pdf
│   └── images/
│       ├── aic_bic.png
│       ├── boxplot.png
│       └── ...
│
│── README.md
│── .gitignore
│── LICENSE

```

---

## Models Used
- GLM (Generalized Linear Models)  
- HLM3 (3-Level Hierarchical Models – linear & nonlinear)  
- Transformations: Yeo-Johnson, Box-Cox  
- Model selection: LogLik, AIC, BIC  

---

## Documentation

- [`docs/pt/TCC_REVISADO.pdf`](docs/pt/TCC_REVISADO.pdf) – Final thesis *(in Portuguese)*  
- [`docs/pt/Apresentacao.pdf`](docs/pt/Apresentacao.pdf) – Defense presentation slides *(in Portuguese)*  

*(Coming soon: English versions)*  
- [`docs/en/Thesis_final.pdf`](docs/en/Thesis_final.pdf) – Final thesis *(in English)*  
- [`docs/en/Presentation.pdf`](docs/en/Presentation.pdf) – Defense presentation slides *(in English)*

- [`docs/images/`](docs/images/) – Figures used in thesis.  

---

## Complementary Repositories
- [Analytics & Storytelling Repository](https://github.com/celsomsilva/thesis-storytelling-usp)  

---

## About the Author

Data Science and Analytics (USP postgraduate) | Computer Engineer (UERJ)  
Background spans from Pascal/C/Java roots to Machine Learning, AI, and statistical modeling.  

Focus areas:  

- Computation in general 
- Data Science, Machine Learning and Deep Learning. 
- LLMs, Reinforcement Learning (current studies)  
- Multilevel models (HLM3/HLM2), nonlinear extensions, ICC  
- Model diagnostics, residuals & transformations (Eg: Box-Cox, Yeo-Johnson) 

---

## Contact
- [LinkedIn](https://linkedin.com/in/celso-m-silva)  
- Or open an [issue](https://github.com/celsomsilva/datasharing/issues)  

---

## Original Note from Jeff Leek’s Repository

This repository was originally created by **Jeff Leek (Johns Hopkins University)** to share resources on **data sharing, reproducibility, and collaboration**.  

Please check his main repository here:  
[Jeff Leek – datasharing](https://github.com/jtleek/datasharing) 
 
The original README from Jeff Leek’s datasharing repository has been preserved in docs/HISTORICAL_README.md.




