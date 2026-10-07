# About this Repository 📌

This repository contains the lab report I did as a part of the coursework for the module Statistical Foundations of Artificial Intelligence. The project applies descriptive and inferential statistics to the PhyAAt dataset, which studies the auditory attention of non-native English speakers in e-learning environments.


# Key Takeaways 🔍

1. Descriptive Statistics: Summarised the attention score and demographic datasets using measures such as the mode, and visualised them with boxplots, histograms and bar charts.

2. Estimation: Estimated mean attention scores with 95% confidence intervals under selected experimental conditions (stimulus length, semanticity and noise level).

3. Hypothesis Testing: Compared noisy and noiseless conditions, two individual subjects and two age groups (≤25 and >25), choosing between parametric tests (Student's and Welch's t-test) and non-parametric tests (Wilcoxon and Mann-Whitney U) after checking normality with the Shapiro-Wilk test.

4. Association: Used Pearson and Spearman correlation to test the relationship between attention score and noise level (SNRdB), and between age group and speaking skill.

5. Own Exploration: Investigated whether overall English proficiency (read, write, speak and listen) is associated with attention score.

6. Main Finding: Attention scores were significantly higher in the noiseless environment than in the noisy one, and increased with noise level (SNRdB), while the age group comparison showed no significant difference.


# Stack 🛠️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


# Environment 👩🏻‍💻
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)


# Libraries ⚙️

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)


# Repository Structure 🌲
```text
├──.gitattributes
├── Lab_Report.ipynb
├── PhyAAt_AttentionScoreData_v1.csv
├── PhyAAt_Demographic_Rating_v1.csv
└── README.md
```

# Reflection 🪞
This project showed how choosing the right statistical test depends on the data, since checking assumptions such as normality determines whether a parametric or non-parametric test is appropriate. Reporting both kinds of test where possible made the conclusions more reliable.

It also highlighted the difference between a result that is statistically significant and one that is practically meaningful, and the importance of clearly stating hypotheses before interpreting results. Overall, it strengthened my confidence in using Python to turn data into evidence-based conclusions.
