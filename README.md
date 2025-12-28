# VisionHeal AI: Deep Learning for Rural Diagnostics

## 🚀 The Vision
[cite_start]To provide a first-line diagnostic screening tool for Tuberculosis and Eye Diseases in areas with zero access to specialists[cite: 6, 7].

## 🛠️ Technical Stack
- [cite_start]**Framework:** TensorFlow / Keras [cite: 15]
- [cite_start]**Architecture:** MobileNetV2 / ResNet50 (Transfer Learning) 
- [cite_start]**Explainability:** Grad-CAM Class Activation Maps [cite: 20]
- [cite_start]**Interface:** Streamlit Web UI [cite: 17]

## 🧠 Model Logic
1. [cite_start]**Input:** Chest X-ray or Retinal Fundus image[cite: 13].
2. [cite_start]**Analysis:** The CNN identifies morphological abnormalities (e.g., opacities for TB, hemorrhages for Eye disease)[cite: 11, 21].
3. [cite_start]**Transparency:** A Grad-CAM heatmap is overlaid to show exactly where the model "looked" to make its decision[cite: 21].
4. [cite_start]**Output:** Diagnostic probability + visual evidence for medical verification[cite: 22].
