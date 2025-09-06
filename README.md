# EEG-Based Emotion Recognition using Regularized Graph Neural Network (RGNN)

This repository contains the implementation of **EEG-based emotion recognition** using a **Regularized Graph Neural Network (RGNN)** with **domain adaptation techniques**.  
The model captures both **local and global inter-channel dependencies** in EEG signals, and introduces methods to improve **cross-subject generalization** and handle **noisy emotion labels**.

---

## 🚀 Key Features
- **Regularized GNN architecture** with learnable adjacency matrices inspired by brain connectivity.
- **Node-wise Domain Adversarial Training (NodeDAT)** to improve subject-independent performance.
- **Emotion-aware Distribution Learning (EmotionDL)** to mitigate label noise.
- **Supports SEED and SEED-IV datasets** for benchmarking EEG emotion recognition.
- Outperforms existing baselines with state-of-the-art accuracy.

---

## 📊 Results
- **SEED dataset**  
  - Subject-dependent: **94.2%**  
  - Subject-independent: **85.3%**  

- **SEED-IV dataset**  
  - Subject-dependent: **79.4%**  
  - Subject-independent: **73.8%**  

---

## 🛠️ Tech Stack
- **Python 3.8+**
- **PyTorch** & **PyTorch Geometric**
- **NumPy**
- **Torch Scatter**
- EEG Signal Processing libraries

---

## 📂 Repository Structure
  ├── model_simple.py   # your RGNN model code
  └── README.md         # documentation

## ⚙️ Installation

1. Clone this repository:
   
   git clone https://github.com/your-username/RGNN-EEG-Emotion.git
   cd RGNN-EEG-Emotion

2. Install dependencies:

  pip install torch torchvision torchaudio
  pip install torch-geometric torch-scatter
  pip install numpy        
