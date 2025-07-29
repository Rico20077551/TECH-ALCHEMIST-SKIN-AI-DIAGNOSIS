WEBSITE URL:  https://rico20077551.github.io/TECH-ALCHEMIST-SKIN-AI-DIAGNOSIS/





# 🧠 Skin Lesion Classification Using a Hybrid CNN + Clinical Metadata Model

> Leveraging **medical domain knowledge** and **deep learning** for accurate skin lesion classification using dermoscopic images and patient metadata (age, sex, anatomical site).

---

## 📌 Table of Contents

1. [Project Overview](#project-overview)
2. [Motivation](#motivation)
3. [Dataset](#dataset)
4. [Project Highlights](#project-highlights)
5. [Model Architecture](#model-architecture)
6. [Experiments & Results](#experiments--results)
7. [Visualization](#visualization)
8. [Grad-CAM Explainability](#grad-cam-explainability)
9. [License](#license)

---

## 📖 Project Overview

This project presents a **multimodal deep learning pipeline developed on Kaggle** for classifying skin lesions into seven diagnostic categories using:
- **Dermoscopic images**
- **Patient metadata:** sex, age, localization, and diagnosis method

We use a **hybrid model architecture** that merges features from a CNN (DenseNet-121) and tabular MLP inputs to improve classification accuracy and interpretability.

---

## 🎯 Motivation

> Skin cancer is one of the top 3 most commonly diagnosed cancers worldwide, but **early detection saves lives**.

Dermatologists use dermoscopic images along with clinical context (like patient age/sex and body location) to diagnose lesions. Many deep learning models ignore metadata—this project addresses that gap using a **hybrid multimodal approach**.

---

## 📊 Dataset

We use the **[HAM10000: Human Against Machine with 10000 training images](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)** dataset. It contains:

- 🖼️ **10,015 dermoscopic images**
- 🧬 **7 diagnostic classes:**
  - akiec (Actinic Keratoses)
  - bcc (Basal Cell Carcinoma)
  - bkl (Benign Keratosis)
  - df (Dermatofibroma)
  - mel (Melanoma)
  - nv (Melanocytic Nevi)
  - vasc (Vascular Lesions)

- 🩺 **Patient Metadata**:
  - `age`, `sex`, `dx_type`, `localization`

---
