
# 🧬 Predicting Drug Toxicity with QML

This project explores the use of **Quantum Machine Learning (QML)** for predicting the toxicity of chemical compounds. The goal is to leverage **quantum-enhanced feature representations** and **hybrid quantum–classical models** to identify potentially toxic molecules early in the drug discovery process.

## 🚀 Objectives

* Build a robust **QML-based classifier** (e.g., Quantum SVM, Variational Quantum Classifier).
* Accurately predict whether a molecule is **toxic** or **non-toxic** based on its molecular structure.
* Compare **quantum** vs **classical** models to explore possible quantum advantages in molecular toxicology.

## 🧠 Key Components

* **Data Preprocessing:** Molecular feature extraction from SMILES using RDKit.
* **Quantum Feature Encoding:** Mapping molecular descriptors to quantum states.
* **Modeling:** Quantum and hybrid classifiers using **PennyLane** and **Qiskit**.
* **Evaluation Metrics:** Recall, Precision, F1-Score, ROC AUC, and MCC (especially for the toxic class).

## 🧩 Tools & Frameworks

* [RDKit](https://www.rdkit.org/) — molecular feature computation
* [PennyLane](https://pennylane.ai/) / [Qiskit](https://qiskit.org/) — quantum ML frameworks
* [PyTorch](https://pytorch.org/) / [scikit-learn](https://scikit-learn.org/) — classical ML and hybrid training
* [Matplotlib](https://matplotlib.org/) / [Seaborn](https://seaborn.pydata.org/) — visualization

## 📊 Evaluation Focus

The model prioritizes safety-critical metrics:

* **High Recall (True Positive Rate)** for toxic compounds
* **Balanced Precision** to minimize false positives
* **Comprehensive reporting** through F1-score, ROC AUC, and MCC

## 📁 Repository Structure

```
predicting-drug-toxicity-qml/
│
├── data/                  # Dataset (SMILES, toxicity labels, descriptors)
├── notebooks/             # Jupyter notebooks for experimentation
├── src/                   # Core scripts: preprocessing, QML models, training
├── reports/               # Model performance summaries and visuals
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

## 💡 Motivation

Toxicity prediction is a major bottleneck in drug discovery. By applying quantum-enhanced learning techniques, we aim to uncover complex molecular–toxicity relationships that may be difficult to capture classically — accelerating the development of safer drugs.

---


