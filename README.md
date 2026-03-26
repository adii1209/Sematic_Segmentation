

# Semantic Segmentation using Deep Learning (MobileNet, U-Net, DeepLabV3)

## 📌 Overview

This project implements and compares three popular deep learning models for **image semantic segmentation** using PyTorch:

* MobileNet-based segmentation
* U-Net
* DeepLabV3

The objective is to evaluate their performance on a segmentation dataset using standard metrics and visualization techniques.

---

## 🚀 Features

* Implementation of 3 segmentation architectures
* Custom dataset handling using PyTorch
* Data augmentation using Albumentations
* Training and evaluation pipelines
* Performance metrics:

  * Precision
  * Recall
  * F1-score
  * Confusion Matrix
  * Cohen Kappa Score
* Visualization of predictions and results

---

## 🧠 Models Implemented

### 1. MobileNet-based Segmentation

* Lightweight architecture
* Efficient for real-time applications

### 2. U-Net

* Encoder-decoder structure
* Highly effective for segmentation tasks

### 3. DeepLabV3

* Uses atrous (dilated) convolutions
* Captures multi-scale contextual information

---

## 🛠️ Tech Stack

* Python
* PyTorch
* segmentation-models-pytorch
* Albumentations
* OpenCV
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Project Structure

```
├── Mobilenet.ipynb
├── Unet.ipynb
├── Deeplabv3.ipynb
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

pip install torch torchvision
pip install segmentation-models-pytorch
pip install albumentations opencv-python matplotlib seaborn scikit-learn
```

---

## ▶️ Usage

Run the notebooks:

```bash
jupyter notebook
```

Then open and execute:

* `Mobilenet.ipynb`
* `Unet.ipynb`
* `Deeplabv3.ipynb`

Each notebook includes:

* Data preprocessing
* Model training
* Evaluation
* Visualization

---

## 📊 Evaluation Metrics

* Precision
* Recall
* F1-score
* Confusion Matrix
* Cohen Kappa Score

---

## 📸 Results

* Predicted vs Ground Truth mask visualization
* Confusion matrix heatmaps
* Model performance comparison

---

## 🎯 Applications

* Medical image segmentation
* Autonomous driving
* Satellite imagery analysis
* Object detection preprocessing

---

## 🔮 Future Work

* Hyperparameter tuning
* Model comparison plots
* Deployment on edge devices
* Real-time inference support

---

## 👨‍💻 Author

Adithya Shankar


