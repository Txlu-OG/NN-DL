# NN-DL
Neural Network

# Neural Networks and Deep Learning (Fashion-MNIST)

This project explores the fundamentals of neural networks using the **Fashion-MNIST** dataset, a modern alternative to MNIST with 70,000 grayscale images of clothing items across 10 categories.

## 📘 Overview
We trained and compared three models:
1. **Baseline MLP:** Simple feedforward network with 128 neurons.
2. **Improved MLP:** Deeper network (256 + 128 neurons) with dropout and RMSprop optimizer.
3. **MLP + Data Augmentation:** Introduced image rotation and shift transformations.

## ⚙️ How to Run
1. Clone this repository and open the notebook in **Google Colab** or **Jupyter**.
2. Install dependencies:
   ```bash
   pip install tensorflow matplotlib seaborn scikit-learn

📊 Results Summary
Model	Accuracy	Macro F1
Baseline MLP	0.880	0.878
Improved MLP	0.876	0.875
MLP + Augmentation	0.783	0.771
🧠 Key Insights

Adding dropout reduced overfitting and improved model stability.

Data augmentation improved generalization but reduced accuracy due to fewer epochs.

The models effectively learned visual distinctions among most fashion categories.

👩🏽‍💻 Author

Adedamola Ogundipe
Neural Network and Deep Learning Basics
