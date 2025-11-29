
---

## 🌟 Overview

This repository includes full implementations of:

### **1. Baseline CNN Training**
- Trains a standard MNIST classifier.

### **2. FGSM (Fast Gradient Sign Method)**
- Generates adversarial examples via linear perturbation.
- Evaluates model robustness as ε increases.
- Reproduces the Goodfellow et al. claim that adversarial examples arise from linearity in high‐dimensional space.

### **3. Adversarial Training**
- Uses FGSM inside the training loop.
- Demonstrates improved robustness to FGSM attacks.

### **4. L-BFGS Adversarial Examples**
- Approximates Szegedy et al.’s box-constrained optimization.
- Produces targeted adversarial examples via L-BFGS.
- Measures L2 distortion vs misclassification success.

### **5. Transferability Between Models**
- Trains two separate models.
- Tests whether adversarial examples crafted on one model fool the other.
- Replicates the transferability phenomenon described in both papers.

---

## 🧠 Key Research Questions

1. Why do adversarial examples exist?  
2. How do FGSM and L-BFGS differ in behavior and distortion?  
3. Can adversarial training improve robustness?  
4. Do adversarial examples transfer across models?  
5. What is the relationship between model gradients, dimensionality, and perturbation sensitivity?

---

## 📦 Installation

To install dependencies:

```bash
pip install -r requirements.txt

