<!-- PROJECT BANNER -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/eef4e5b6-6f58-4bb3-9614-e39d7bd3c6e7" alt="Project Banner" width="55%">
</p>

<h1 align="center"> ECLIPSE – Offline Skin Lesion Classification</h1>

<p align="center">
  <b>Fully Offline · Standalone MSI Installer · Parallel Swin Encoder . DenseNet-169</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue" />
  <img src="https://img.shields.io/badge/Installer-MSI-orange" />
  <img src="https://img.shields.io/badge/Offline-Yes-success" />
  <img src="https://img.shields.io/badge/Framework-.NET%20WPF-blueviolet" />
  <img src="https://img.shields.io/badge/Model-ONNX-yellow" />
</p>

---

## 🚀 Overview

**ECLIPSE** is a **standalone, fully offline** skin lesion classification system built using a  
**Swin Transformer + DenseNet-169 + U-Net encoder architecture**, deployed as a **Windows MSI installer**.

It runs entirely on-device, ensuring:

- 🔒 Complete data privacy  
- ⚡ Fast processing  
- 🌐 Zero internet dependency  
- 🖥️ Seamless deployment on any Windows machine  

---

## 🧠 System Architecture

### 🔄 Workflow  
<p align="center">
  <img src="https://github.com/user-attachments/assets/4a4e640c-9d29-4d2b-8856-f7c8992ae9fa" 
       alt="Workflow Diagram"
       style="max-width: 90%; border-radius: 12px;">
</p>

### 🏗️ Parallel Encoder — DenseNet-169 + U-Net  
<p align="center">
<img width="2048" height="2048" alt="Gemini_Generated_Image_22vc1p22vc1p22vc" src="https://github.com/user-attachments/assets/d97228eb-2bf6-4894-b13a-ea9e27b380bb"
       alt="System Architecture" 
       style="max-width: 75%; border-radius: 12px;">
</p>

---

## 💻 Application Screenshots

### 🖼️ Input View  
<p align="center">
  <img src="https://github.com/user-attachments/assets/bec33f01-50ac-44fa-b243-e86f92bffe86" 
       alt="Input View" 
       width="45%" 
       style="border-radius: 12px;">
</p>

### 📟 Prediction Output  
<p align="center">
  <img src="https://github.com/user-attachments/assets/bd69d7d7-66a8-4f26-8790-2b68dc45b446" 
       alt="Prediction Output" 
       width="90%" 
       style="border-radius: 12px;">
</p>

### 🔍 Classification UI  
<p align="center">
  <img src="https://github.com/user-attachments/assets/b1cc3b32-22e6-4e0a-997f-feb44714d553" 
       alt="Classification UI" 
       width="75%" 
       style="border-radius: 12px;">
</p>

---

## ⭐ Features

- 🔌 **100% Offline** — No cloud, no external API calls  
- 📦 Distributed as a **Windows MSI Installer**  
- 🧠 ONNX Runtime for fast, local inference  
- 🎯 Benign / Malignant classification with confidence %  
- 📊 Optional CSV export  
- 🔒 Guaranteed privacy — images never leave the device  
- 🖥️ Clean and intuitive WPF interface  

---

## 📥 Installation (MSI)

1. Download **`ECLIPSE v1.0.0.msi`**
2. Run the installer  
3. Follow the setup wizard  
4. Launch via:  
   **Start Menu → ECLIPSE – Skin Lesion Classifier**

✔ No dependencies required  
✔ No internet required  
✔ Works instantly after installation  

---

## 📘 Usage

1. Open **ECLIPSE**  
2. Click **Browse** and select a dermoscopic image  
3. Click **Predict**  
4. View:
   - Benign / Malignant classification  
   - Confidence score  
5. (Optional) Export results as CSV

All inference happens **locally** using the embedded ONNX model.

---

## 📊 Results

### 📈 Confusion Matrix  
<p align="center">
  <img src="https://github.com/user-attachments/assets/d701ac5c-2600-43d7-924a-83ea0babfcf6" 
       alt="Confusion Matrix"
       width="70%"
       style="border-radius: 12px;">
</p>

---

## 📉 Training Curves

### 🔹 Training History  
<p align="center">
  <img src="https://github.com/user-attachments/assets/20a102a6-ea6f-404a-9e83-84fce718bb35" 
       alt="Training History"
       width="95%"
       style="border-radius: 12px;">
</p>

### 🔹 Fine-Tune Curves  
<p align="center">
  <img src="https://github.com/user-attachments/assets/d78a8370-f30e-4298-a537-c1d115872ceb" 
       alt="Fine Tune Curves"
       width="75%"
       style="border-radius: 12px;">
</p>

---

## 👥 Contributors

<p align="left">

  <span>
    <b>Anagha P Kulkarni</b> &nbsp;
    <a href="https://github.com/Anu-253" target="_blank" rel="noopener noreferrer">
      <img src="https://skillicons.dev/icons?i=github" width="22" />
    </a>
    <a href="https://www.linkedin.com/in/anagha-p-kulkarni-723498341/" target="_blank" rel="noopener noreferrer">
      <img src="https://skillicons.dev/icons?i=linkedin" width="22" />
    </a>
  </span>
  <br>
  <span>
    <b>Debabrata Kuiry</b> &nbsp;
    <a href="https://github.com/cyrax3589" target="_blank" rel="noopener noreferrer">
      <img src="https://skillicons.dev/icons?i=github" width="22" />
    </a>
    <a href="https://www.linkedin.com/in/debabrata-kuiry/" target="_blank" rel="noopener noreferrer">
      <img src="https://skillicons.dev/icons?i=linkedin" width="22" />
    </a>
  </span>
  <br>
  <span>
    <b>B Chiru Vaibhav</b> &nbsp;
    <a href="https://github.com/Vaibhav5012" target="_blank" rel="noopener noreferrer">
      <img src="https://skillicons.dev/icons?i=github" width="22" />
    </a>
    <a href="https://www.linkedin.com/in/bchiruvaibhav/" target="_blank" rel="noopener noreferrer">
      <img src="https://skillicons.dev/icons?i=linkedin" width="22" />
    </a>
  </span>
</p>

---

Dataset used: [Unified Dataset for Skin Cancer Classification on Kaggle](https://www.kaggle.com/datasets/vinline/unified-dataset-for-skin-cancer-classification)


---

## 📄 License

Academic use only.

---
