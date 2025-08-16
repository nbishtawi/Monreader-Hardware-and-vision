Page Flip Detection with Computer Vision  

## Overview  
**Page Flip Detection** is a computer vision project designed to classify whether a document page has been flipped or not. Using convolutional neural networks (CNNs) and sequence modeling (LSTMs), the project processes images of documents to detect page states.   

Note: The datasets used in this project are **proprietary** and therefore not included in this repository.  

---

## Goals  
- Detect whether a page is in a **flipped** or **not flipped** state.  
- Build a lightweight vision model suitable for real-time use.  
- Explore CNN + LSTM approaches for robust classification.  

---

## Features  
- **Data Preprocessing:** Image resizing, normalization, and labeling.  
- **Image Classification:** CNN model with Conv2D, MaxPooling, Dense layers.  
- **Sequential Modeling:** Integration of **LSTM** layers for temporal page-flip detection.  
- **Custom Metrics:** F1-score metric implemented with Keras backend.  
- **Reproducibility:** End-to-end Jupyter notebook workflow.  

---

## Methodology  
1. **Data Loading** – Images loaded from `flip/` and `notflip/` folders.  
2. **Preprocessing** – Resizing to 128×128 pixels, normalization of pixel values.  
3. **Model Architecture** –  
   - CNN layers for feature extraction.  
   - Dense layers for binary classification.  
   - Optional **LSTM** integration for temporal detection.  
4. **Training & Validation** – Dataset split into training, validation, and testing sets.  
5. **Evaluation** – Accuracy, F1-score, and error analysis performed.  

---

## Results  
- CNN successfully classified page states with strong accuracy.  
- Custom F1 metric provided balanced performance evaluation.  
- Potential for integration into **document digitization systems** and **assistive reading devices**.  

---

## Tools & Technologies  
- **Python**  
- **TensorFlow / Keras** – deep learning models  
- **NumPy, Pandas** – data handling  
- **Scikit-learn** – evaluation metrics and train/test splitting  
- **Matplotlib** – visualization  
