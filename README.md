<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Meryem%20Hanyn&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=45&desc=AI%20Engineer%20%7C%20Medical%20Imaging%20%7C%20Luxembourg&descAlignY=65&descSize=16" width="100%"/>
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=A855F7&center=true&vCenter=true&width=650&lines=Hey+there!+I'm+Meryem+%F0%9F%91%8B;I+build+AI+that+works+in+the+real+world;Medical+imaging+%7C+Few-shot+learning+%7C+PyTorch;Based+in+Luxembourg+%F0%9F%87%B1%F0%9F%87%BA" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <a href="mailto:mar.hanyn@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-mar.hanyn%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Luxembourg-🇱🇺-red?style=for-the-badge"/>
</div>

<br/>

---

## 👋 Hey, I'm Meryem

I'm an AI engineer based in Luxembourg with a background that's a bit of an unusual mix — I spent several years managing IT and digital transformation projects at a large bank, and at some point decided I wanted to be the one *building* the systems, not just shipping them.

So I went back to school, did a Master's in Software Engineering, and ended up deep in medical imaging research. My thesis is on few-shot learning for rare kidney disease detection — basically, teaching a model to classify tumours it's barely seen before, using as little data as possible, while also being honest about when it's uncertain. Turns out that last part (the honesty) is really hard to get right, and really important when a doctor is on the other end.

I'm particularly drawn to problems at the intersection of **clinical AI and real-world constraints** — rare diseases, small datasets, models that need to be explainable, systems that need to actually be trusted by the humans using them.

When I'm not training models, you'll find me doing yoga, reading about neuroscience, or hiking somewhere in Luxembourg's surprisingly good trails 🥾

---

## 🧪 What I've been working on

### 🫁 Few-Shot Learning for Rare Kidney Disease Detection *(Thesis — 2025–2026)*

This one is my main research project and honestly the most technically interesting thing I've ever built. The problem: rare renal tumours don't have thousands of labelled scans sitting around. So I built a pipeline that learns from very few examples using episodic meta-learning (Prototypical Networks), runs on multi-centre CT data from KiTS23 (599 cases, 123 hospitals), and — crucially — tells you *how confident it is* using Monte Carlo Dropout. Ambiguous cases get flagged for human review instead of silently mislabelled.

The three things I combined (episodic meta-learning + Bayesian uncertainty + spatial explainability) hadn't been jointly evaluated on a realistic multi-centre cohort before. That gap was the whole motivation.

**Stack:** Python · PyTorch · MONAI · Prototypical Networks · Monte Carlo Dropout

---

### 🧠 Alzheimer's Staging from Structural MRI *(2025)*

Four-stage Alzheimer's classification from MRI scans. I trained and compared three architectures (a custom CNN, ResNet50, and EfficientNetB0) on 6,400 scans — the custom one won with 93% accuracy and macro F1 of 0.93. Then applied Grad-CAM to see *where* the model was looking, and the activations landed on the hippocampus and ventricles, which is exactly what you'd expect from the neuroscience literature. That alignment between AI attention and clinical knowledge is what makes a model actually useful to deploy.

**Stack:** Python · TensorFlow/Keras · CNN · ResNet50 · EfficientNetB0 · Grad-CAM

---

### 🧬 [Brain Tumor Detector](https://github.com/Mhanyn/Brain-Tumor-Detector)

Earlier project — CNN classifying brain MRI scans into four categories (Glioma, Meningioma, Pituitary, Healthy). Built a custom architecture from scratch and compared it against DenseNet201 and Xception. The custom model hit 99.25% test accuracy and outperformed both pre-trained baselines. This was the project that got me interested in medical imaging as a field.

**Stack:** Python · TensorFlow/Keras · CNN · DenseNet201 · Xception

---

### 🎗️ [Breast Cancer Predictor](https://github.com/Mhanyn/breast-cancer-predictor)

Binary classification on cell nuclei features — malignant vs. benign. Compared Logistic Regression and KNN with GridSearchCV tuning, evaluated on AUC-ROC and stratified F1. A solid end-to-end ML project from preprocessing through evaluation.

**Stack:** Python · Scikit-learn · Pandas · Seaborn · GridSearchCV

---

### 🚭 [Smoking & Drinking Predictor](https://github.com/Mhanyn/smoking-drinking-predictor)

This one I actually deployed — a Random Forest model predicting lifestyle health risks, wrapped in a Flask REST API and served with a StandardScaler preprocessing pipeline. Fun exercise in taking a model all the way from notebook to something that actually runs.

**Stack:** Python · Scikit-learn · Random Forest · Flask

---

### ♟️ [N-Queens Solver](https://github.com/Mhanyn/n-queens-solver)

A benchmarking study comparing Exhaustive Search (DFS) and a Genetic Algorithm on the N-Queens problem across increasing board sizes. The interesting part was finding the exact crossover point where brute force becomes computationally hopeless and you *need* a heuristic. Classic CS, but satisfying to measure precisely.

**Stack:** Python

---

## 🛠️ Things I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📝 Some things I've written

- *Bridging Precision and Clinical Applicability* — CNN-Based Diagnosis of Brain Tumors
- *Hybrid Parallel K-Means Clustering on High-Dimensional Personality Data* — MPI/OpenMP
- *Parallel Image Blurring: A Study on Synchronization, Communication, and Performance*
- *A Research on Solving the N-Queens Problem using Exhaustive Search and Genetic Algorithm*

---

## 🌍 Languages

`English` · `French` · `Arabic` · `Spanish` · `German`

---

## 📬 Get in touch

If you're working on something in medical AI, rare disease detection, or just want to talk about uncertainty quantification over coffee (virtually or otherwise) — feel free to reach out.

📧 mar.hanyn@gmail.com

---

<!-- FOOTER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
</div>
