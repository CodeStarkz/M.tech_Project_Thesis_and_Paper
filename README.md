Here’s a clean, GitHub-friendly **README summary** you can drop straight into your repository 👇

---

## Discrimination of Normal and Abnormal Knee Joint VAG Signals Using EMD

This repository presents a signal-processing–based framework for **automated discrimination of normal and abnormal knee joint conditions** using **Vibroarthrography (VAG) signals**. The proposed approach leverages **Empirical Mode Decomposition (EMD)** to analyze the nonlinear and non-stationary nature of knee joint vibrations.

### 🔍 Methodology

* **Dataset**: Publicly available knee joint VAG database containing signals from **51 normal** and **38 abnormal** subjects.
* **Signal Decomposition**: EMD is used to decompose each VAG signal into multiple **Intrinsic Mode Functions (IMFs)**.
* **Feature Extraction**: A total of **12 features** (statistical, nonlinear, entropy-based, and shape-based) are extracted from each IMF.
* **Feature Selection**: The **Kruskal–Wallis (K-W) non-parametric test** is employed to identify the most discriminative features between normal and abnormal classes.

### 📊 Key Findings

* **Entropy-based features**, particularly from the **first few IMFs**, show strong discriminatory power.
* Lower-order IMFs contain most of the diagnostically relevant information.
* The EMD + K-W test combination effectively reduces feature dimensionality while preserving class separability.

### ✅ Conclusion

The study demonstrates that **EMD-based decomposition combined with statistical feature selection** is a promising approach for **non-invasive, low-cost screening of knee joint abnormalities**. This framework can serve as a foundation for developing **automated clinical decision-support systems**, with future extensions involving machine learning classifiers for full automation.

### 🛠 Tools

* MATLAB
* Signal Processing Toolbox

---



