# Hybrid CNN-SVM for MNIST Classification
This project implements a hybrid machine learning architecture that combines Deep Learning (CNN) with statistical classification (SVM).

### 🧠 The Logic
Traditional CNNs use a Softmax layer for classification. This project replaces that layer with an **SVM (Support Vector Machine)**. 
- The **CNN** acts as the "eyes," extracting complex patterns from the images.
- The **SVM** acts as the "decision-maker," finding the optimal hyperplane to separate the digits.

### 🛠 Tech Stack
- **Deep Learning:** TensorFlow/Keras
- **Machine Learning:** Scikit-learn (SVM)
- **Visualization:** Matplotlib, Seaborn
- **GUI:** Tkinter, Pillow (PIL)

### 📈 Results
- **Linear Kernel Accuracy:** 99.04%
- **RBF Kernel Accuracy:** 99.26% (Best Performer)
