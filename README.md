# 🧠 Research Projects @ IIT Bombay  
### Physics-Informed AI & Computer Vision for Material Behavior Analysis

This repository showcases research projects completed during my internship at **IIT Bombay**, focusing on the intersection of **machine learning, physics, and materials science**.

> ⚠️ **Note:** Due to institutional and publication constraints, source code and detailed datasets are not included. This repository serves as a **project overview and research summary**.

---

# 📌 Table of Contents
- [Project 1: Physics-Informed Neural Networks (PINNs)](#-project-1-physics-informed-neural-networks-pinns)
- [Project 2: Crack Detection using Mask R-CNN](#-project-2-crack-detection-using-mask-r-cnn)
- [Key Learnings](#-key-learnings)
- [Acknowledgements](#-acknowledgements)

---

# 🔬 Project 1: Physics-Informed Neural Networks (PINNs)

### 🏗️ Title  
**Physics-Informed Neural Networks for Accelerated Material Behavior Simulation**

### 👨‍🔬 Role  
Research Intern (Individual Project)  
Supervised by **Prof. Alankar Alankar**, IIT Bombay  

---

## 📖 Overview

This project focuses on developing a **Physics-Informed Neural Network (PINN)** to simulate material behavior under varying stress conditions.

Traditional approaches like the **Finite Element Method (FEM)** are computationally expensive. This work explores PINNs as a **faster, physics-aware alternative** capable of predicting:

- Stress distribution  
- Strain fields  
- Plastic deformation  
- Fracture points  

---

## ⚙️ Tech Stack

- **Languages:** Python  
- **Frameworks:** TensorFlow, Keras, PyTorch  
- **Libraries:** NumPy, SciPy, Matplotlib  
- **Tools:** Jupyter Notebook, Google Colab, ANSYS  
- **Hardware:** NVIDIA GPUs  
- **Concepts:**  
  - Physics-Informed Neural Networks (PINNs)  
  - Operator Learning  

---

## 🚧 Challenges & Solutions

### 1. Loss Function Formulation  
- **Challenge:** Embedding physics laws into the learning process  
- **Solution:** Iteratively tested multiple formulations to balance accuracy and efficiency  

### 2. Boundary & Initial Conditions  
- **Challenge:** Ensuring physical consistency  
- **Solution:** Refined constraints through experimentation and validation  

### 3. Collocation Point Selection  
- **Challenge:** Efficient domain sampling  
- **Solution:** Used:
  - Latin Hypercube Sampling  
  - Sobol Sequences  

### 4. Network Design  
- **Challenge:** Balancing complexity vs performance  
- **Solution:** Experimented with architectures, activations, and optimizers  

### 5. Training Stability  
- **Challenge:** Convergence issues  
- **Solution:** Applied advanced optimization and iterative tuning  

### 6. Domain Complexity  
- **Challenge:** Bridging ML with mechanical physics  
- **Solution:**  
  - Research paper reviews  
  - Expert consultations  

---

## 📊 Results

- ⚡ **60× faster** than FEM simulations  
- 🎯 **98.2% accuracy** compared to FEM  
- 🚀 Demonstrated PINNs as a viable real-time simulation tool  
<img width="1173" height="2990" alt="download" src="https://github.com/user-attachments/assets/ad4b5d85-23f3-4cce-a4f8-cec3ee8f8a36" />

---

## 🌍 Impact

This work contributes toward:

- Real-time material simulation  
- Civil & mechanical engineering applications  
- Advanced materials research  
- AI-driven scientific computing  

---

## 🔒 Code Availability

> Due to a contractual agreement with IIT Bombay, the code cannot be shared until the associated research publication is released.

---

# 🧩 Project 2: Crack Detection using Mask R-CNN

### 🏗️ Title  
**Crack Detection in Materials Using Mask R-CNN**

### 👨‍🔬 Role  
Research Intern (Individual Project)  
Guided by ICME Lab, IIT Bombay  

---

## 📖 Overview

This project involves building a **Mask R-CNN model** to detect and segment cracks in high-frequency material stress images.

Unlike traditional classification models, this approach provides **pixel-level segmentation**, enabling:

- Crack localization  
- Length & width estimation  
- Structural analysis  

---

## ⚙️ Tech Stack

- **Languages:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, OpenCV, Matplotlib  
- **Tools:** Jupyter Notebook, Google Colab  
- **Concepts:**  
  - Mask R-CNN  
  - Image Segmentation  

---

## 🚧 Challenges & Solutions

### 1. Annotation Availability  
- **Challenge:** Missing annotation files  
- **Solution:**  
  - Created initial annotations  
  - Coordinated external annotation support  

---

### 2. Model Selection  
- **Challenge:** Need for segmentation (not just classification)  
- **Solution:** Selected **Mask R-CNN** for instance segmentation  

---

### 3. Data Quality  
- **Challenge:** Variations in image conditions  
- **Solution:**  
  - Normalization  
  - Resizing  
  - Data augmentation (rotation, flipping, shifts)  

---

### 4. Overfitting  
- **Challenge:** Limited labeled data  
- **Solution:**  
  - Dropout  
  - Regularization  
  - Early stopping  
  - Cross-validation  

---

### 5. Computational Constraints  
- **Challenge:** High training cost  
- **Solution:** Used **CMINDS (IIT Bombay)** GPU resources  

---

### 6. Hyperparameter Tuning  
- **Challenge:** Model optimization  
- **Solution:**  
  - Grid Search  
  - Random Search  

---

## 📊 Results

- ✅ High accuracy in crack detection  
- 🎯 Reliable segmentation of crack regions  
- 🔍 Enabled deeper analysis of material failure  
<img width="1173" height="2990" alt="download" src="https://github.com/user-attachments/assets/ad4b5d85-23f3-4cce-a4f8-cec3ee8f8a36" />
---

## 🌍 Impact

- Structural health monitoring  
- Material testing automation  
- Industrial inspection systems  
- Smart infrastructure solutions  

---

# 🖼️ Research Poster

📍 Presented at a IRCC Poster Presentation

# 📚 Key Learnings

- Bridging **physics and machine learning**  
- Designing **scientifically grounded AI models**  
- Working with **real-world experimental data**  
- Handling **high-performance computing workflows**  
- End-to-end research execution:
  - Problem formulation  
  - Experimentation  
  - Validation  
  - Presentation  

---

# 🙏 Acknowledgements

- **Prof. Alankar Alankar** — Guidance on physics & simulation  
- **ICME Lab, IIT Bombay** — Domain expertise & resources  
- **CMINDS Facility** — Computational support 


