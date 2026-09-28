# Deep Feature Extraction and Huntington Disease Classification (DCSPR + ChPO-ELM)

This repository contains the Google Colab implementation for Huntington Disease  classification using DCSPR feature extraction and ChPO-ELM optimization.

---

## 🚀 Quick Start (Google Colab)



1. Open `code+-.ipynb` in Google Colab.
2. Ensure GPU runtime is enabled (**Runtime > Change runtime type > T4 GPU**).
3. Run all cells sequentially to reproduce feature extraction, training, evaluation, and plot generation.

---

## 📊 Dataset & Ethics Statement

* **Data Source:** Sourced from [Radiopaedia](https://radiopaedia.org), an open-access clinical case repository.
* **Patient Privacy:** All images uploaded to Radiopaedia are fully anonymized (removing Personal Health Information and patient identifiers) under CC BY-NC-SA licensing.

---

## 🛠️ Code Features & Plot Generation

The Colab notebook automatically executes:
* Data preprocessing and feature extraction (DCSPR).
* Model training with Chimp Optimization Algorithm (ChPO) and ELM classifier.
* plot generation for:
  * Confusion Matrix 
  * ROC Curves
  * Performance Charts

---

## 📁 Repository Structure

```text
├── code.ipynb         # Main Google Colab notebook
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
