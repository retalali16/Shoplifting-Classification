# 🎥Shoplifting Video Classifier
# Phase 1 Binary video classification using a **CNN** for frame features and a **BiLSTM** for temporal modeling. Includes preprocessing, augmentation, class balancing, and mixed-precision training.

## ✨ Features
-  Supports `.mp4`, `.avi`, `.mov`, `.mkv`, etc.  
-  Uniform frame extraction per video  
-  CNN + BiLSTM architecture  
- **Class balancing** (oversampling & weights)  
-  **Data augmentation**: flips, brightness/contrast, temporal shifts  
-  Automatic F1-based threshold selection  
- 📊 Outputs: classification report, confusion matrix, training curves  


# Phase 2 Shoplifting Detection using MobileNetV2 + BiLSTM

This project detects suspicious or shoplifting activities in CCTV footage using a deep learning model that combines **MobileNetV2** (for spatial feature extraction) and **BiLSTM** (for temporal sequence learning).

### ✅ Key Achievements
- **Test Accuracy:** 98.80%
- **Test Loss:** 0.0500  
- **Backbone:** Pretrained MobileNetV2 (fine-tuned top 20 layers)
- **Temporal Modeling:** Bidirectional LSTM
- **Frames per Clip:** 16 uniformly sampled
- **Augmentation:** Flip, brightness, contrast, and zoom transformations

---
## 🛠️ Requirements
```bash
pip install tensorflow opencv-python numpy scikit-learn matplotlib tqdm
