<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Meryem%20Hanyn&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=45&desc=AI%20Engineer%20%7C%20Machine%20Learning%20%7C%20Luxembourg&descAlignY=65&descSize=16" width="100%"/>
</div>

<h3 align="center">AI Engineer &nbsp;·&nbsp; Machine Learning &nbsp;·&nbsp; Software Engineering</h3>

<div align="center">
  <a href="mailto:mar.hanyn@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-mar.hanyn%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Luxembourg-🇱🇺-red?style=for-the-badge"/>
</div>

<br/>

---

## About Me

**AI Engineer** based in Luxembourg. <br/>
**Master's Researcher** focused on clinical AI and few-shot learning. <br/>
**Former IT Project Manager** who crossed over to the building side, and never looked back. <br/>
**Drawn to hard problems** where data is scarce, stakes are high, and the model needs to know what it doesn't know. <br/>
**Open to collaboration** on AI, ML engineering, and anything where explainability matters.

> *"The most interesting question isn't whether a model is accurate, it's whether it knows when it's wrong."*

---

## 🔬 Research

### 🫁 Few-Shot Learning for Rare Kidney Disease Detection

**The problem:** rare renal tumours don't have thousands of labelled scans. You can't just throw data at it.

Built a unified pipeline that learns from very few examples using episodic meta-learning (Prototypical Networks), trained on the multi-centre **KiTS23** dataset (599 cases, 123 hospitals). The model uses **Monte Carlo Dropout** to flag ambiguous cases for human review instead of silently getting them wrong. Integrated Grad-CAM for spatial explainability so predictions can be inspected visually.

The combination of episodic meta-learning + Bayesian uncertainty + spatial explainability on a realistic multi-centre cohort hadn't been done before. That gap was the whole motivation.

`Python` `PyTorch` `MONAI` `Prototypical Networks` `Monte Carlo Dropout` `Grad-CAM` `KiTS23`

---

### 🧠 Alzheimer's Disease Staging from Structural MRI

Four-stage Alzheimer's classification from 6,400 MRI scans. Benchmarked a custom CNN against ResNet50 and EfficientNetB0 — the custom architecture won at **93% accuracy, macro F1 of 0.93**. Grad-CAM analysis showed activations consistently landing on the hippocampus and ventricles, matching established neuropathology. That alignment is what makes AI trustworthy in a clinical setting.

`Python` `TensorFlow/Keras` `Custom CNN` `ResNet50` `EfficientNetB0` `Grad-CAM`

---

### 🧬 Brain Tumor Detection from MRI — CNN-Based Diagnosis
[github.com/Mhanyn/Brain-Tumor-Detector](https://github.com/Mhanyn/Brain-Tumor-Detector)

Research project comparing custom and pre-trained architectures for 4-class brain MRI classification (Glioma, Meningioma, Pituitary, Healthy). The custom CNN reached **99.25% test accuracy**, outperforming DenseNet201 and Xception. Full evaluation suite including per-class precision, recall, F1, confusion matrices and ROC curves.

`Python` `TensorFlow/Keras` `CNN` `DenseNet201` `Xception` `Google Colab`

---

## 💻 Projects

### 🎗️ [Breast Cancer Predictor](https://github.com/Mhanyn/breast-cancer-predictor)
**Binary malignancy classification on cell nuclei features**

Logistic Regression vs. KNN with GridSearchCV hyperparameter tuning. Evaluated on AUC-ROC and stratified F1. Clean end-to-end pipeline from preprocessing through evaluation.

`Python` `Scikit-learn` `Pandas` `Seaborn` `GridSearchCV`

---

### 🚭 [Smoking & Drinking Predictor](https://github.com/Mhanyn/smoking-drinking-predictor)
**End-to-end deployed health prediction app**

Random Forest classifier on lifestyle biomarker data, serialised and served as a live Flask REST API with a StandardScaler preprocessing pipeline. The full trip from notebook to something that actually runs.

`Python` `Scikit-learn` `Random Forest` `Flask`

---

### 🧠 Hybrid Parallel K-Means Clustering on High-Dimensional Personality Data
**HPC — MPI/OpenMP implementation of parallelised K-Means**

Implemented a hybrid parallel K-Means clustering algorithm combining MPI for inter-node communication and OpenMP for intra-node threading. Designed to handle high-dimensional personality trait datasets, with performance benchmarked against a sequential baseline to quantify speedup across varying core counts and node configurations.

`C` `MPI` `OpenMP` `High-Performance Computing` `Parallel Algorithms`

---

### 🖼️ Parallel Image Blurring — Synchronization, Communication & Performance Study
**HPC — performance analysis of distributed image processing**

Research project analysing the performance trade-offs in parallel image blurring across different parallelisation strategies. Evaluated synchronization overhead, communication patterns, and load balancing across processes to understand how data distribution and inter-process communication impact scalability on multi-core and distributed systems.

`C` `MPI` `OpenMP` `High-Performance Computing` `Performance Analysis`

---

### ♟️ [N-Queens Solver](https://github.com/Mhanyn/n-queens-solver)
**Exhaustive Search vs. Genetic Algorithm — where does brute force break down?**

Benchmarked DFS and GA across increasing board sizes and pinpointed the exact crossover where exact search becomes computationally hopeless and heuristics take over. Classic CS, but satisfying to measure precisely.

`Python`

---

## 🛠️ Tech Stack

#### Core ML & Research
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/MONAI-1a1a2e?style=for-the-badge&logo=python&logoColor=white"/>
</p>

#### Data & Visualisation
<p>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white"/>
</p>

#### Cloud, DevOps & Deployment
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

---

## 🌍 Languages

`English` &nbsp; `French` &nbsp; `Arabic` &nbsp; `Spanish` &nbsp; `German`

---

## 📬 Say hi

Always glad to hear from people working in AI, ML engineering, or anything related to data.

📧 [mar.hanyn@gmail.com](mailto:mar.hanyn@gmail.com)

---

<!-- FOOTER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
</div>
