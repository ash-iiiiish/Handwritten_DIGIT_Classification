# Handwritten Digit Classification 🖊️🔢

This repository implements a **Handwritten Digit Classification** model using the **MNIST dataset**. The project demonstrates deep learning with **PyTorch**, along with **Optuna hyperparameter tuning**, and evaluation using `scikit-learn`.  

The model achieves **97% accuracy on the test dataset** and **98% accuracy on the training dataset**.

---

## 🚀 Features

- Uses the **MNIST dataset** (28×28 grayscale images of handwritten digits 0–9)  
- **CNN (Convolutional Neural Network)** architecture for digit recognition  
- **Hyperparameter optimization with Optuna**  
- Evaluation metrics using **scikit-learn** (accuracy, confusion matrix, etc.)  
- Visualization of training and validation metrics  

---

# Requirements file
pip install -r requirements.txt


# 🔎 Hyperparameter Tuning with Optuna

This project integrates Optuna for automatic hyperparameter optimization.
The tuning process explored:

Learning rate

Optimizer choice (SGD, Adam, RMSprop, etc.)

Dropout rate

Batch size

Number of filters in CNN layers

Optuna automatically selected the best-performing configuration.

# 🏋️ Training

Optimizer: (best found by Optuna, e.g., Adam/SGD)

Loss Function: CrossEntropyLoss

Batch Size: Tuned

Epochs: Tuned via Optuna

Final Accuracy:

Train: 98%

Test: 97%


🤝 Contributing

Contributions are welcome!
Feel free to open an issue or submit a pull request for improvements, new features, or bug fixes.
