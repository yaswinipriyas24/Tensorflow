# Student Marks Prediction using TensorFlow

## 📖 *Project Overview*

This is a simple machine learning project where we use *TensorFlow* to build and train a regression model that predicts student marks based on hours studied. It’s designed for beginners to understand how machine learning models are built, trained, and used for predictions using TensorFlow’s Sequential API.

The project walks through:
- Dataset preparation
- Model creation
- Compilation with loss and optimizer
- Model training
- Evaluation and prediction
- Visualization of results

This project helps learners understand the fundamentals of neural networks, loss functions, optimizers, and how data types and shapes influence learning.

---

## 🟠 *Problem Statement*

The task is to predict student marks based on the number of hours studied using a simple neural network.

- *Input:* Hours studied (numerical feature)
- *Output:* Marks obtained (continuous target)

The goal is to train the model to learn the relationship and predict marks for new input values.

---

## ✅ *Key Learnings*

✔ TensorFlow’s tensor structure and data types  
✔ Building neural networks with Sequential API  
✔ Regression problems vs classification problems  
✔ Loss functions like Mean Squared Error  
✔ Optimizers like SGD and Adam  
✔ How weights and bias influence predictions  
✔ Training the model over multiple epochs  
✔ Evaluating and visualizing the results

---

## 📂 *Dataset*

The dataset is small and manually created for demonstration purposes:

```python
X = [2, 3, 5, 7, 8]   # Hours studied
Y = [10, 15, 25, 35, 40]  # Marks obtained
