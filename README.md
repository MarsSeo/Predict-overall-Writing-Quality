<h1 align="center">✍🏻Predict-overall-Writing-Quality</h1>

![header_image](https://github.com/MarsSeo/Predict-overall-Writing-Quality/assets/103374757/468d6059-262f-4878-bd0e-63bd15e5e3e1)

---

## Introduction

This project revolves around an innovative competition designed to predict overall writing quality by analyzing typing behavior and process features. Held from October 3, 2023, to January 10, 2024, this competition merged the realms of data science and linguistic analysis. It provided a unique platform to explore how different aspects of the writing process, captured through extensive keystroke log datasets, influence the quality of written essays.

---

## Background

The essence of this competition extended beyond the boundaries of standard predictive modeling. It explored the complex array of behavioral and cognitive activities involved in writing. The competition recognized that writing involves a variety of techniques for planning, revising, and execution, each of which contributes distinct patterns like pauses, additions, deletions, and revisions. These nuances often go unnoticed in traditional writing assessments, which predominantly focus on the final written product. The competition thus sought to illuminate these overlooked aspects of the writing process.

---

## Objectives

The core challenge was to leverage process features extracted from keystroke logs to predict the overall quality of writing. This ambitious endeavor aimed to reveal deeper connections between writers' behaviors during the writing process and the eventual quality of their work. By focusing on these process features, the competition aspired to enhance current writing assessment tools that typically center on the end product. The broader goal was to influence educational methodologies, potentially leading to improved teaching strategies that foster autonomy, metacognitive awareness, and self-regulation among students in their writing endeavors.

---

## Novel Approach

* Optimized iterative blending of model weights for enhanced predictive accuracy.
* Employed Out-Of-Fold prediction with 10-fold cross-validation for each model number.
* Conducted extensive feature engineering, developing over 400 distinct and informative features.
* Utilized advanced methods in feature engineering for improved model performance.
* Integrated linear models with non-linear (tree-based/deep learning) models for better predictions.

---

## Feature Engineering Method

* Extracted text input activity, then processed and combined changes to reconstruct essays.
* Calculated statistical metrics on word, sentence, and paragraph lengths in essays.
* Aggregated key typing actions and events to understand user input patterns.
* Engineered features from time gaps between typing actions for behavioral insights.
* Developed word-based features, analyzing input words' lengths and frequencies in texts.
* Integrated latency and pause metrics to capture timing dynamics in writing process.

---

## Modeling Method

<img width="600" alt="image" src="https://github.com/MarsSeo/Predict-overall-Writing-Quality/assets/103374757/beabb5bd-af23-4323-98a8-03dbfc49be70">

* Employed LightGBM, CatBoost, XGBoost, SVR models with finely tuned hyperparameters for optimization.
* Conducted rigorous cross-validation, focusing on minimizing RMSE and analyzing feature importance.
* Applied common feature sets across models, enhancing prediction consistency and model effectiveness.
* Optimized ensemble blending weights iteratively to balance model predictions and maximize accuracy.

---

## Result Analysis

In our project's results section, we acknowledge that although our final score didn't meet our highest expectations, our model achieved a noteworthy cross-validation score of 0.59, surpassing many competitors. This solid CV performance underscores the effectiveness of our feature engineering and modeling approach in the context of essay evaluation. Interestingly, our post-competition analysis revealed that some of our unselected submissions fell within the silver medal scoring range. This near-miss with a higher accolade demonstrates the potential of our methods and sets a promising direction for future improvements.

### Our Unselected Submissions
<img width="1223" alt="our_score" src="https://github.com/MarsSeo/Predict-overall-Writing-Quality/assets/103374757/228b63dd-5fd8-4f8f-9fde-3b95fcbdbaa7">

---

### Final Private Leaderboard 
<img width="1216" alt="compare_LB" src="https://github.com/MarsSeo/Predict-overall-Writing-Quality/assets/103374757/c3ce91d4-0b81-4610-838d-9340f4ae6551">

