# 🧠 Research Projects @ IIT Bombay

### Physics-Informed AI & Computer Vision for Material Behavior Analysis

This repository showcases research projects completed during my internship at **IIT Bombay**, focusing on the intersection of **machine learning, physics, and materials science**.

> ⚠️ **Note:** Due to institutional and publication constraints, source code and detailed datasets are not included. This repository serves as a **project overview and research summary**.

---

# 📌 Table of Contents

* [Project 1: Crack Segmentation using U-Net](#-project-1-crack-segmentation-using-u-net)
* [Project 2: Physics-Informed Neural Networks (PINNs)](#-project-2-physics-informed-neural-networks-pinns)
* [Key Learnings](#-key-learnings)
* [Acknowledgements](#-acknowledgements)

---

🧩 Project 1: Crack Segmentation using U-Net
🏗️ Title

Automated Crack Detection in Materials Using Deep Learning Segmentation

👨‍🔬 Role

Research Intern (Individual Project)
Guided by ICME Lab, IIT Bombay

📖 Overview

This project focuses on building a U-Net deep learning model to detect and segment cracks in material stress test images.

The model performs pixel-level segmentation, enabling:

Precise crack localization
Automated defect detection
Structural integrity analysis
📊 Dataset
Training Data: 7000 images
Test Data: 300 images
⚙️ Tech Stack
Languages: Python
Frameworks: TensorFlow, Keras
Libraries: NumPy, OpenCV
Tools: Google Colab, Jupyter Notebook
Architecture: U-Net (Encoder-Decoder with Skip Connections)
🧠 Model Architecture (Summary)

A 2-level U-Net architecture with an encoder–decoder structure and skip connections.
The encoder extracts features via convolution and pooling, the bottleneck captures high-level representations, and the decoder upsamples while preserving spatial details.
The model outputs a binary segmentation mask (crack vs background) using sigmoid activation.

📊 Results
✅ Successfully trained U-Net model for crack segmentation
🎯 Achieved accurate binary segmentation (crack vs background)
🔬 Demonstrated feasibility of automated crack detection
📈 Model converged over 50 training epochs

Sample Output:

<img width="1173" height="2990" alt="crack_segmentation_results" src="https://github.com/user-attachments/assets/ad4b5d85-23f3-4cce-a4f8-cec3ee8f8a36" />

# 🔬 Project 2: Physics-Informed Neural Networks (PINNs)

### 🏗️ Title

**Physics-Informed Neural Networks for Accelerated Material Behavior Simulation**

### 👨‍🔬 Role

Research Intern (Individual Project)
Supervised by **Prof. Alankar Alankar**, IIT Bombay

---

## 📖 Overview

This project focuses on developing a **Physics-Informed Neural Network (PINN)** to simulate material behavior under varying stress conditions.

Traditional approaches like the **Finite Element Method (FEM)** are computationally expensive. This work explores PINNs as a **faster, physics-aware alternative** capable of predicting:

* Stress distribution
* Strain fields
* Plastic deformation
* Fracture points

---

## ⚙️ Tech Stack

* **Languages:** Python
* **Frameworks:** TensorFlow, Keras, PyTorch
* **Libraries:** NumPy, SciPy, Matplotlib
* **Tools:** Jupyter Notebook, Google Colab, ANSYS
* **Hardware:** NVIDIA GPUs
* **Concepts:**

  * Physics-Informed Neural Networks (PINNs)
  * Operator Learning

---

## 🚧 Challenges & Solutions

### 1. Loss Function Formulation

* **Challenge:** Embedding physics laws into the learning process
* **Solution:** Iteratively tested multiple formulations to balance accuracy and efficiency

### 2. Boundary & Initial Conditions

* **Challenge:** Ensuring physical consistency
* **Solution:** Refined constraints through experimentation and validation

### 3. Collocation Point Selection

* **Challenge:** Efficient domain sampling
* **Solution:** Used:

  * Latin Hypercube Sampling
  * Sobol Sequences

### 4. Network Design

* **Challenge:** Balancing complexity vs performance
* **Solution:** Experimented with architectures, activations, and optimizers

### 5. Training Stability

* **Challenge:** Convergence issues
* **Solution:** Applied advanced optimization and iterative tuning

### 6. Domain Complexity

* **Challenge:** Bridging ML with mechanical physics
* **Solution:**

  * Research paper reviews
  * Expert consultations

---

## 📊 Results

* ⚡ **60× faster** than FEM simulations
* 🎯 **98.2% accuracy** compared to FEM
* 🚀 Demonstrated PINNs as a viable real-time simulation tool

---

## 🌍 Impact

This work contributes toward:

* Real-time material simulation
* Civil & mechanical engineering applications
* Advanced materials research
* AI-driven scientific computing

---

## 🔒 Code Availability

> Due to a contractual agreement with IIT Bombay, the code cannot be shared until the associated research publication is released.

---

# 🖼️ Research Poster

📍 Presented at a IRCC Poster Presentation

---

# 📚 Key Learnings

* Bridging **physics and machine learning**
* Designing **scientifically grounded AI models**
* Working with **real-world experimental data**
* Handling **high-performance computing workflows**
* End-to-end research execution:

  * Problem formulation
  * Experimentation
  * Validation
  * Presentation

---

# 🙏 Acknowledgements

* **Prof. Alankar Alankar** — Guidance on physics & simulation
* **ICME Lab, IIT Bombay** — Domain expertise & resources
* **CMINDS Facility** — Computational support
