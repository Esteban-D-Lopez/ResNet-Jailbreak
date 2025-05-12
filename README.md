# Project 3: Jailbreaking Deep Models - Adversarial Attacks on Image Classifiers

**Course:** Deep Learning CS 6953 - Spring 2025
**Team Members:**
* Esteban D Lopez (ed19434@nyu.edu)
* Shruti Karkamar (spk9869@nyu.edu)
* Steven Granaturov (sg8002@nyu.edu)

## Project Overview

This project explores the vulnerability of deep learning models, specifically image classifiers, to various adversarial attacks. We implement and analyze the effectiveness of the Fast Gradient Sign Method (FGSM), Projected Gradient Descent (PGD), and a localized PGD-based patch attack against a pre-trained ResNet-34 model on a subset of the ImageNet dataset. Furthermore, the transferability of these generated adversarial examples to a different model architecture (DenseNet-121) is investigated.

The primary goals were to:
1.  Establish a baseline performance for the ResNet-34 model.
2.  Implement FGSM and PGD attacks to significantly degrade model performance under specific $L_{\infty}$ constraints.
3.  Implement a localized patch attack.
4.  Evaluate the transferability of these attacks to an unseen model.
5.  Document the methodologies, results, and learnings in a comprehensive report and codebase.

## Project Components

### 1. Codebase

The complete implementation of the adversarial attacks, model evaluations, and visualizations can be found in the Jupyter Notebook:

* **Notebook:** [`Code-DL_Project3_Jailbreak_FINAL.ipynb`](./Code-DL_Project3_Jailbreak_FINAL.ipynb)

The notebook is structured by tasks as outlined in the project requirements:
* **Task 1:** Basics Setup + Evaluation (ResNet-34 baseline)
* **Task 2:** FGSM Attack
* **Task 3:** Improved Attacks (PGD)
* **Task 4:** Patch Attack
* **Task 5:** Transferring Attacks (to DenseNet-121)

### 2. Project Report

A detailed report outlining the project's background, problem definition, methodology, experimental setup, results, discussion, and conclusion is available:

* **Report:** [`Report-DL_Project3_Jailbreak_FINAL.pdf`](./Report-DL_Project3_Jailbreak_FINAL.pdf)

The report follows the AAAI 2024 camera-ready format as specified in the project guidelines.

## Getting Started

### Prerequisites
* Python 3.x
* PyTorch
* TorchVision
* NumPy
* Matplotlib
* Pandas

You can typically install these using pip:
```bash
pip install torch torchvision torchaudio numpy matplotlib pandas