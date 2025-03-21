# 🍇 Bayesian Modeling of Italian Wine Quality

**Author:** Beyza Kordan  
**Program:** MSc in Economics and Data Analytics, University College Dublin  
**Date:** March 2024

---

## 📘 Project Overview

This project explores the chemical properties of 178 Italian wines through Bayesian linear modeling using the `rstan` package. The objective was to predict alcohol content using various predictors such as magnesium, color intensity, and proline. Three models were developed with increasing complexity, enabling comparisons of fit and explanatory power.

---

## 🧠 Key Methods Applied

**Bayesian Linear Regression** (via Stan)
**Model Development & Interpretation**
**Posterior Distributions Summaries**
**Posterior Predictive Checks**
**Prior Selection Justification**

---

## 📊 Highlights

**Model 1:**  
Simple linear model with magnesium as a predictor.  
🧪 Result: Positive correlation with alcohol content.

**Model 2:**  
Added color intensity to improve predictive power.  
📉 Reduced residual variance, tighter fit.

**Model 3:**  
Full model including magnesium, color intensity, and proline.  
🎯 Best fit with lowest σ and most nuanced insights.

**Posterior Predictive Checks:**  
Visual and numerical checks validate model assumptions and fit.

---

## 🔧 Technologies Used

R  
rstan, bayesplot, ggplot2  
Stan for Bayesian inference

---

## 📎 Notes

This project was part of a university assignment focused on Bayesian methods. All code, interpretation, and write-up are authored by me. The analysis emphasizes reproducibility and thoughtful model comparison using probabilistic programming.

---
