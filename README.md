# 🐱🐶 Cat vs Dog Image Classifier using SVM

This project implements a Support Vector Machine (SVM) model to classify images of cats and dogs using grayscale image features. It is part of **Prodigy InfoTech Machine Learning Internship - Task 03**.
---
## 📂 Dataset
Used dataset: [Kaggle - Cat and Dog](https://www.kaggle.com/datasets/tongpython/cat-and-dog)
- Training set: `dataset/training_set/Cat` and `Dog`
- Test set: `dataset/test_set/Cat` and `Dog`
---
## 🛠️ Technologies Used
- Python 3
- Google Colab
- OpenCV
- NumPy, Matplotlib
- Scikit-learn (SVM)
---
## 🧠 Model
- **Classifier**: Support Vector Machine (SVC with linear kernel)
- **Preprocessing**: Resized all images to 64x64, converted to grayscale, and flattened
- **Training Size**: 1000 cats + 1000 dogs (balanced)
---
## 📈 Results
- ✅ **Validation Accuracy**: ~86–90%
- ✅ **Test Accuracy**: ~85–89%
- 📊 Classification Report: Includes precision, recall, f1-score
---
## 🔍 Sample Prediction Visualization
Displays predicted vs actual labels for 10 random test images.
---
## 📌 How to Run
1. Download the dataset ZIP from Kaggle.
2. Upload `cat-and-dog.zip` to Google Colab.
3. Run all cells in the provided notebook:  
   `SVM_Cat_vs_Dog_Classifier_Prodigy_Task03.ipynb`

- 🧑‍💻 Submitted by: Rushii (Prodigy ML Intern)
