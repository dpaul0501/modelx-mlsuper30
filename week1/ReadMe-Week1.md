# 📘 ModelX-ML Bootcamp – Week X: Basics of Machine Learning

Welcome to **Week X** of the **ModelX-ML 30-Week Bootcamp**, where we dive into the foundational principles that power modern machine learning algorithms.

**Youtube** https://www.youtube.com/watch?v=pAkNPlLmsUw

Slides and Notes: 
1. https://www.cs.cornell.edu/courses/cs4780/2018fa/syllabus/ - Lecture 6-8
2.[Lecture Notes: Linear & Logistic Regression](http://cs229.stanford.edu/notes2023fall/cs229-notes1.pdf)

## Assignment
https://colab.research.google.com/drive/1dQiOqwxZzCXCbOF848asQ530MuMOASTA?usp=sharing

---

## 🧠 Topics Covered

This week focuses on the **core statistical and mathematical ideas** behind machine learning models. The content is inspired by:

- **Cornell CS4780 (2018 Fall) – Intro to Machine Learning**  
  🔗 [Course Syllabus](https://www.cs.cornell.edu/courses/cs4780/2018fa/syllabus/)

- **Stanford CS229 – Lecture 1**  
  📚 [Lecture Notes: Linear & Logistic Regression](http://cs229.stanford.edu/notes2023fall/cs229-notes1.pdf)

---

## 🗂️ Lecture Summary

### 🔹 1. Maximum Likelihood Estimation (MLE)
- **Goal:** Estimate parameters that maximize the probability of observing the given data.
- **Assumes:** Data is drawn from a known parametric distribution.
- **Example:** Estimating the mean of a Gaussian distribution from sample data.

### 🔹 2. Maximum A Posteriori Estimation (MAP)
- **Goal:** Incorporate prior belief into parameter estimation.
- **Builds on:** MLE, but adds a **Bayesian prior**.
- **Example:** MAP becomes MLE when using a uniform prior.

### 🔹 3. Linear Regression
- **Model:** \( y = \theta^T x + \epsilon \)
- **Assumptions:** Noise \( \epsilon \sim \mathcal{N}(0, \sigma^2) \)
- **Optimization:** Minimizing squared error using closed-form or gradient descent.

### 🔹 4. Logistic Regression
- **Model:** \( P(y=1|x) = \sigma(\theta^T x) \), where \( \sigma \) is the sigmoid.
- **Loss Function:** Cross-entropy (log-loss).
- **Use Case:** Binary classification tasks.

---

## 📌 Key Takeaways

- **MLE vs MAP**: MLE is purely data-driven, MAP blends data with prior belief.
- **Regression vs Classification**: Linear regression is for continuous outputs, logistic regression handles discrete (binary) outcomes.
- **Statistical grounding**: Understanding the **probabilistic interpretations** behind models enables better model design and debugging.

---

## 🔧 Practice Ideas

- Derive the MLE for the mean and variance of a normal distribution.
- Compare MAP vs MLE estimations with small datasets.
- Implement linear regression using both closed-form and gradient descent.
- Train logistic regression on a simple dataset (e.g., breast cancer or Titanic) and visualize decision boundaries.

---

## 📚 Suggested Readings

- CS4780 Lecture Notes: Chapters on Estimation Theory & Regression
- CS229 Lecture 1 PDF: [Link](http://cs229.stanford.edu/notes2023fall/cs229-notes1.pdf)
- Bishop’s *Pattern Recognition and Machine Learning* – Chapters 1–3

---

## 🧭 Next Week Preview: Recommendation Systems

Next week, we’ll dive into **Recommendation Systems**!  
We'll explore:
- Popularity-based and collaborative filtering approaches  
- User-item matrix factorization  
- Embedding-based methods  
- Real-world use cases in Netflix, Amazon, and Spotify

Get ready to personalize at scale! 🎯
