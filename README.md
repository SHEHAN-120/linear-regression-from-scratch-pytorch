# Simple Linear Regression Using PyTorch

This repository demonstrates how to implement and train a simple **Linear Regression** model using **PyTorch** on a synthetic dataset.

---

## 📊 Project Overview

A toy dataset is generated using the formula:

```
y = 2 * x + 1 + noise
```

I use PyTorch to build and train a linear regression model to learn this relationship.

---

## 🧰 Tools & Technologies Used

* **Python** 🐍
* **PyTorch** 🔥 (model building, training)
* **Matplotlib** 📊 (visualization)
* **Scikit-learn** (for train-test splitting)
* **NumPy** (data manipulation)

---

## 🚀 How to Run

1. Clone this repository

2. Install dependencies

3. Run the script


## 🥪 Output Visualizations

* **Initial scatter plot** of training and test data.
* **Prediction plot** of the untrained model.
* **Training loss curve** over epochs.
* **Test vs predicted values** after training.

---

## ✅ Key Steps

* Data generation with noise
* Data visualization
* Model definition (`nn.Module`)
* Loss function: Mean Squared Error (`nn.MSELoss`)
* Optimizer: Stochastic Gradient Descent (`torch.optim.SGD`)
* Training loop with backpropagation
* Evaluation on test data

---

## 🧐 Challenges Faced

* Handling data reshaping for PyTorch tensors
* Visualizing predictions before and after training
* Tracking loss values for convergence check
* Ensuring proper tensor datatypes (e.g., `float32`)

---

## 📌 Final Result

The trained model learns the underlying linear pattern and makes accurate predictions on unseen data, as shown in the test vs prediction plot.


---

## 📜 License

This project is open-source under the [MIT License](LICENSE).
