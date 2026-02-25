# Face Mask Detection Using CNN
CNN-based face mask detection system using TensorFlow

## 👥 Team Members
- J.M.D.T.Abesingha (ICT/2022/116)
- M.H.M.S.Vimukthi (ICT/2022/015)
- A.W.Wasma (ICT/2022/090)
- S.W.H.I.Wickramasingha (ICT/2022/041)
- K.A.O.C.Kumbalathara (ICT/2022/021)

## 📋 Project Overview
This project implements a Convolutional Neural Network (CNN) to detect whether a person is wearing a face mask. 

## 📊 Dataset
- **Source:** Kaggle Face Mask Detection Dataset
- **Classes:** With Mask (11,218 images), Without Mask (11,346 images)
- **Split:** Training (17,417), Validation (1,934), Test (1,279)

## 🏗️ Model Architecture
- CNN with Conv2D, MaxPooling, Dense layers
- Binary classification using sigmoid activation
- Dropout for regularization

## 📈 Results
- **Test Accuracy:** 95.31%
- **Precision:** 0.95 (both classes)
- **Recall:** 0.95 (both classes)

## 🛠️ Technologies Used
- Python, TensorFlow/Keras, NumPy
- Google Colab, Matplotlib, Scikit-learn

## 📁 Files in this Repository
- `faceMask.ipynb` - Main implementation notebook

## 📝 Notes
This is Implementation 1 (Baseline). Model shows signs of overfitting which will be addressed in Implementation 2.
