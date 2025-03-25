# Deep Learning Assignment: 3-Layer Neural Network for Nonlinear Regression  

## 📌 Overview  
This repository contains solutions for implementing a **3-layer neural network** for **nonlinear regression** using multiple frameworks:  
- **NumPy (from scratch with manual backpropagation)**  
- **PyTorch (manual, class-based, and Lightning)**  
- **TensorFlow (low-level, built-in layers, and functional API)**  

Additionally, the implementation incorporates:  
- **TensorFlow `einsum` for matrix operations** instead of standard multiplication.  
- **Synthetic 4D data generation** for training.  
- **Proper non-linear activation functions** and **appropriate number of neurons** per layer.  

Each approach includes:  
✔ Code walkthrough 📜  
✔ Model training and evaluation 📊  
✔ Final output and visualization 🎨  

## 📁 Repository Structure  
```sh
📦 deep-learning-nonlinear-regression  
 ┣ 📂 notebooks  
 ┃ ┣ 📜 numpy_manual_backprop.ipynb  
 ┃ ┣ 📜 pytorch_manual.ipynb  
 ┃ ┣ 📜 pytorch_class_based.ipynb  
 ┃ ┣ 📜 pytorch_lightning.ipynb  
 ┃ ┣ 📜 tensorflow_low_level.ipynb  
 ┃ ┣ 📜 tensorflow_builtin_layers.ipynb  
 ┃ ┣ 📜 tensorflow_functional_api.ipynb  
 ┃ ┣ 📜 synthetic_data_generation.ipynb  
 ┃ ┗ 📜 utils.py (common utility functions)  
 ┣ 📂 media  
 ┃ ┗ 📜 walkthrough_video.mp4  
 ┣ 📜 README.md  
 ┣ 📜 requirements.txt  
 ┗ 📜 .gitignore  
