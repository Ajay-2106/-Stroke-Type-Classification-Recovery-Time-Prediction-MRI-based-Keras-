# 🧠 LabVIEW and Python integration code (LabVIEW Python node) 
**Deep Learning-Based System for Stroke Type Detection & Outcome Estimation**

This Python module uses pre-trained CNN models to analyze MRI images, classify stroke type (Normal, Ischemic, Haemorrhagic), and estimate the recovery time in months for stroke-affected cases. Designed to integrate seamlessly with LabVIEW-based medical systems or standalone prediction tools.

---

## 🚀 Features
- Classifies stroke MRI into:
  - **Normal**
  - **Ischemic Stroke**
  - **Haemorrhagic Stroke**
- Predicts **recovery duration in months** using regression models
- Returns clean JSON outputs — easy to parse in LabVIEW or other frontends
- Handles edge cases: missing files, unexpected shapes, or test inputs
- Supports fast predictions by preloading all models

---

## 🛠 Requirements
- Python 3.x
- TensorFlow / Keras
- Pillow (PIL)
- NumPy
- tensorflow
- pillow numpy
