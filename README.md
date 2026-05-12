# Machine Learning Specialization — Study Notes & Labs

<p align="center">
  <img src="assets/banner.png" alt="Machine Learning Specialization Banner" width="800"/>
</p>

Personal notes and lab notebooks from the [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) by **DeepLearning.AI & Stanford Online** (Coursera), instructed by **Prof. Andrew Ng**.

---

## 📂 Repository Structure

```
Machine-Learning/
├── Supervised Machine Learning - Regression and Classification/
│   └── (lab notebooks — Week 1–3)
├── Advanced Learning Algorithms/
│   └── (lab notebooks — Week 4–6)
├── Unsupervised Learning, Recommenders, Reinforcement Learning/
│   └── (lab notebooks — Week 7–9)
├── notes/
│   ├── main.tex                  ← LaTeX root file
│   ├── main.pdf                  ← compiled PDF (auto-updated by CI)
│   └── chapters/
│       ├── ch01.tex
│       ├── ch02.tex
│       ├── ch03.tex
│       ├── ch04.tex
│       ├── ch05.tex
│       ├── ch06.tex
│       ├── ch07.tex
│       ├── ch08.tex
│       ├── ch09.tex
│       └── ch10.tex
├── .github/
│   └── workflows/
│       └── compile-latex.yml     ← auto-compile PDF on push
├── .gitignore
└── README.md
```

---

## 📖 Lecture Notes

A self-compiled LaTeX textbook covering all 10 chapters of the specialization — from linear regression to reinforcement learning.

**📄 Read the full PDF: [`notes/main.pdf`](notes/main.pdf)**
**!! More detailed notes PDF: [`notes/Lecture_notes.pdf`](notes/Lecture_notes.pdf) **

### Table of Contents

| Chapter | Title | Topics |
|:-------:|-------|--------|
| [1](notes/chapters/ch01.tex) | **Introduction to Machine Learning** | Overview of ML · Supervised vs. Unsupervised Learning · Linear Regression · Gradient Descent |
| [2](notes/chapters/ch02.tex) | **Linear Regression with Multiple Variables** | Multiple Features · Vectorisation · Feature Engineering · Feature Scaling · Convergence |
| [3](notes/chapters/ch03.tex) | **Classification** | Logistic Regression · Sigmoid Function · Decision Boundaries · Cross-Entropy Loss · Overfitting & Regularisation |
| [4](notes/chapters/ch04.tex) | **Neural Networks** | Biological Intuition · Layered Architecture · TensorFlow Implementation · Forward Propagation in NumPy |
| [5](notes/chapters/ch05.tex) | **Neural Network Training** | Training Framework · Activation Functions · Multiclass & Multi-label Classification · Adam Optimiser · Backpropagation |
| [6](notes/chapters/ch06.tex) | **Advice for Applying Machine Learning** | Bias & Variance · Train/CV/Test Split · Debugging Strategies · Data Augmentation · Transfer Learning · Skewed Datasets |
| [7](notes/chapters/ch07.tex) | **Decision Trees** | Entropy & Information Gain · Recursive Splitting · Tree Ensembles · Random Forests · XGBoost |
| [8](notes/chapters/ch08.tex) | **Unsupervised Learning** | K-Means Clustering · Anomaly Detection · Gaussian Density Model |
| [9](notes/chapters/ch09.tex) | **Recommender Systems** | Collaborative Filtering · Matrix Factorisation · Content-Based Filtering · Principal Component Analysis |
| [10](notes/chapters/ch10.tex) | **Reinforcement Learning** | MDPs · Q-Function · Bellman Equation · Deep Q-Networks · ε-Greedy Policy |

---

## 🧪 Lab Notebooks

Hands-on programming assignments organised by course:

| Course | Folder |
|--------|--------|
| Supervised Machine Learning: Regression and Classification | [`Supervised Machine Learning - R.../`](Supervised%20Machine%20Learning%20-%20R.../) |
| Advanced Learning Algorithms | [`Advanced Learning Algorithms/`](Advanced%20Learning%20Algorithms/) |
| Unsupervised Learning, Recommenders, Reinforcement Learning | [`Unsupervised Learning/`](Unsupervised%20Learning/) |

---

## ⚙️ CI/CD — Auto-compile LaTeX

Every push to `notes/` automatically triggers a GitHub Actions workflow that:
1. Installs TeX Live on an Ubuntu runner
2. Compiles `main.tex` with `pdflatex`
3. Commits the updated `main.pdf` back to the repository

No local LaTeX installation required.

---

## 🙏 Acknowledgements

This set of notes represents my personal journey through the Machine Learning
Specialization — 10 weeks of learning, countless hours of problem sets, and
a deep appreciation for how elegant mathematics can be when applied to real-world
problems.

I would like to express my sincere gratitude to **Professor Andrew Ng** and the
**DeepLearning.AI** team for designing such a thoughtful and accessible curriculum.
The way complex concepts are broken down — from gradient descent to reinforcement
learning — made this an incredibly rewarding experience.

To anyone reading these notes: I hope they serve as a useful companion, whether
you are working through the specialization yourself, revisiting core concepts,
or simply exploring the field of machine learning. These notes are not a
substitute for the course itself — I strongly encourage you to take it firsthand.

If you find any errors or have suggestions for improvement, feel free to open
an **issue** or **pull request**. Feedback is always welcome.

*Happy learning.*
— Truong Dat, 2026

---

## 📚 Reference

> Ng, A., Shyu, E., Bagul, A., & Ladwig, G. (2022). *Machine Learning Specialization* [Online course]. DeepLearning.AI & Stanford Online, Coursera.
> https://www.coursera.org/specializations/machine-learning-introduction

---

## 🏆 Certification

<p align="center">
  <img src="assets/Certification.png" alt="Machine Learning Specialization Certificate" width="700"/>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/LaTeX-notes-blue?logo=latex&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-notebooks-yellow?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-green"/>
  <img src="https://img.shields.io/github/actions/workflow/status/TruongDat05/Machine-Learning/compile-latex.yml?label=PDF%20build"/>
</p>
