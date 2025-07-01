# Task-04: Image-to-Image Translation with Pix2Pix

### Internship: Prodigy Infotech – Generative AI (15 June – 15 July 2025)

---

## 🔍 Overview

This project implements a Pix2Pix (Conditional GAN) model for converting **building edge maps into realistic building images** using the **facades dataset**.

---

## 🧠 About the Model

- Model: Pix2Pix (cGAN)
- Framework: PyTorch
- Dataset: Facades (paired edge-photo images)
- Direction: B → A (edges → buildings)

---

## 📈 Results

Generated images from the test set:

## 📷 Sample Output from Pix2Pix

| Input (Edge Map) | Generated Image | Ground Truth |
|------------------|------------------|---------------|
| ![](https://github.com/tusharparmar29/PRODIGY_GA_04/blob/main/results/1_real_A.png?raw=true) | ![](https://github.com/tusharparmar29/PRODIGY_GA_04/blob/main/results/1_fake_B.png?raw=true) | ![](https://github.com/tusharparmar29/PRODIGY_GA_04/blob/main/results/1_real_B.png?raw=true) |


---

## 📁 Files Included

- `train.py` – for training
- `test.py` – for testing
- `results/` – output images
- `README.md` – project summary

---

✅ **Task completed successfully.**
