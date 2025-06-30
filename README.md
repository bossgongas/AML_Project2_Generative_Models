# 🧠 Generative Models for Traffic Sign Augmentation – ACA Project 2

This project explores the use of **generative models** to **augment a dataset of traffic signs** and improve classification performance.  
Developed for the course **Advanced Machine Learning (ACA)** of the **Master’s in Engineering and Data Science**, University of Coimbra (2023/2024).

> **Project Title:** *Do you need more signs?*  
> **Authors:** Gonçalo Bastos · Leonardo Cordeiro

---

## 🎯 Goal

To compare and evaluate the impact of data augmentation using **AutoEncoders (AEs)** and **Generative Adversarial Networks (GANs)** on the performance of a base **CNN classifier**.

---

## 🧪 Pipeline Summary

1. **Train generative models** (AE and GAN) using the original dataset
2. **Generate synthetic samples**
3. **Retrain CNN classifier** on original vs. augmented datasets
4. **Compare performance metrics** (accuracy, loss, training time)

---

## 📁 Files Included

- `Do_you_need_more_signs.pdf`: Project report with all methodology and results  
- `Code_Final.ipynb`: Implementation notebook (training AE, GAN and CNN)  
- `data-students.rar`: Provided dataset (extract to `./data/`)  
- `results/`: Generated samples, training curves, and final plots

---

## 🛠️ Technologies Used

- Python 3.x
- PyTorch
- NumPy, Matplotlib
- Google Colab / Jupyter Notebooks

---

## 📊 Evaluation Metrics

- **CNN Baseline Accuracy** (original data only)
- **CNN + AE Augmented Data** → ↑ modest improvement  
- **CNN + GAN Samples** → ↑ best performance improvement

---

## 📂 How to Run

1. Extract dataset:
   ```bash
   mkdir data && unrar x data-students.rar ./data/
