# 🧠 ADL Final Project — Open Set Recognition on MNIST

This repository contains the final project for the **Advanced Deep Learning** course, exploring **Open Set Recognition (OSR)** using the MNIST dataset.

---

## 📘 Project Description

In many real-world scenarios, models may encounter data from **unknown classes** not seen during training. Traditional classifiers fail in such situations, often misclassifying unknowns as knowns. This project tackles this issue by evaluating methods designed for **Open Set Recognition**.
Refer to this article for theoretical background: https://arxiv.org/pdf/1811.08581
---

## 🔬 Objectives

- Build a standard classifier for digit classification on MNIST (Closed Set).
- Simulate an OSR setup by training on a subset of MNIST digits (classes 0-9) and testing on both known and unknown samples (class 10)

---

## 📁 Files

- `final_notebook.ipynb`: Full pipeline notebook with training, OSR evaluation, and visualization.

---

## 🚀 Running the Notebook
This entire notebook (training and evaluation) ran under 8 minutes, using Google Colab's T4 GPU
