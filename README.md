# 🎥Shoplifting Video Classifier:  CNN + BiLSTM

Binary video classification using a ** CNN** for frame features and a **BiLSTM** for temporal modeling. Includes preprocessing, augmentation, class balancing, and mixed-precision training.

## ✨ Features
-  Supports `.mp4`, `.avi`, `.mov`, `.mkv`, etc.  
-  Uniform frame extraction per video  
-  CNN + BiLSTM architecture  
- **Class balancing** (oversampling & weights)  
-  **Data augmentation**: flips, brightness/contrast, temporal shifts  
-  Automatic F1-based threshold selection  
- 📊 Outputs: classification report, confusion matrix, training curves  

## 🛠️ Requirements
```bash
pip install tensorflow opencv-python numpy scikit-learn matplotlib tqdm
