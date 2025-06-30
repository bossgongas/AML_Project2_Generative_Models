# 🧠 Generative Models for Traffic Sign Augmentation – ACA Project 2

This project explores the use of **generative models** to **augment a dataset of traffic signs** and improve classification performance.  
Developed for the course **Advanced Machine Learning (ACA)** of the **Master’s in Engineering and Data Science**, University of Coimbra (2023/2024).

> **Project Title:** *Do you need more signs?*  
> **Authors:** Gonçalo Bastos - eusoudebastos@gmail.com · Leonardo Cordeiro - leoleocordeiro@gmail.com

---

### GAN Generated images
<img width="339" alt="image" src="https://github.com/user-attachments/assets/62a82e11-4a41-4afa-9a98-7507464dbd84" />
### AutoEncoder Generated images
<img width="339" alt="image" src="https://github.com/user-attachments/assets/e33c0d4c-ecaf-4df1-9507-59e4b76f1afd" />

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

- `/notebooks`: Project report with all methodology and results  
- `Code_Final.ipynb`: Implementation notebook (training AE, GAN and CNN)  
- `data-students.rar`: Provided dataset (extract to `./data/`)  

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

