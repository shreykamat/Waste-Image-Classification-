# Multi-Class Waste Classification using Convolutional Neural Networks

Waste sorting is a critical challenge in modern waste management systems. Manual sorting is labour-intensive, error-prone, and poses hygiene and safety risks. Automating waste classification using computer vision can significantly improve efficiency, scalability, and reliability.

This project develops a **Convolutional Neural Network (CNN)** to automatically classify waste items into multiple material categories using image data.

---

## 📌 Project Overview

The objective of this project is to build and evaluate a deep learning–based image classification system capable of identifying common waste materials. The model classifies waste items into the following categories:

- **Plastic**
- **Paper**
- **Metal**
- **Miscellaneous**

The dataset used in this project was **personally collected and curated through a collaborative effort by a team of four**, making it representative of real-world waste sorting conditions rather than benchmark-style datasets.

---

## 🧠 Methodology

- A CNN-based image classification pipeline is implemented using deep learning.
- Images are preprocessed and used to train a supervised multi-class classifier.
- The model learns discriminative visual features to differentiate between waste categories.
- Performance is evaluated using standard classification metrics.

---

## 🗂️ Dataset Description

The dataset consists of **16,281 images** of waste items collected from **waste processing plants and scrapyards in Goa, India**.

### Class Distribution

| Waste Category   | Number of Images |
|------------------|------------------|
| Plastic          | 6,807            |
| Paper            | 2,767            |
| Metal            | 2,283            |
| Miscellaneous    | 4,424            |
| **Total**        | **16,281**       |

### Dataset Characteristics

- **Original dataset collected and curated by the author**
- Images were manually collected from waste plants and scrapyards
- Most waste items were photographed from **multiple orientations**

These characteristics make the dataset representative of **real-world waste sorting scenarios**.

---

## 📂 Repository Contents

- Dataset directory containing labelled waste images
- Notebooks/scripts for:
  - Data preprocessing
  - Model training
  - Model evaluation

---

## 🎯 Applications

- Automated waste sorting systems
- Smart recycling and waste management solutions
- Robotics-assisted waste segregation
- Environmental monitoring and sustainability initiatives

---

## 📖 Disclaimer

This project is intended for **research and educational purposes**. While the dataset reflects real-world conditions, additional validation would be required before deployment in an operational waste management system.
