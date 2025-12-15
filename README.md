# Neural GUI MATLAB – Artificial Intelligence in Mechatronic Systems

Graphical User Interface developed in **MATLAB (App Designer)** for experimentation with classical **neural network models** applied to **classification, regression, adaptive filtering, and complex system modeling**.

---

## 📌 Project Objective

To design and implement an **intuitive GUI** that allows users to:

* Load datasets in `.txt` format
* Configure training parameters
* Train different neural network models
* Visualize graphical results and numerical metrics

---

## 🧠 Implemented Modules

### 1️⃣ Classification – Single Perceptron

* Linearly separable datasets
* User-configurable parameters:

  * Number of epochs
  * Learning rate
  * Allowed error
* Results:

  * Decision boundary plot
  * Pattern distribution
  * Training error and epochs

---

### 2️⃣ Linear Regression – ADALINE Network (Plane)

* Plane fitting over a data cloud
* User-configurable parameters:

  * Number of epochs
  * Learning rate
  * Allowed error
* Results:

  * Fitted regression plane
  * MSE training curve
  * Final weights and bias

---

### 3️⃣ Adaptive Filtering – ADALINE

* Signal filtering using multiple regressors
* User-configurable parameters:

  * Number of epochs
  * Learning rate
  * Allowed error
  * Number of regressors
* Results:

  * Original signal vs. filtered signal

---

### 4️⃣ Complex Modeling – Multilayer Neural Network (MLNN)

* Dynamic system modeling
* Dataset includes time vector, input excitation, and system output
* User-configurable parameters:

  * Number of epochs
  * Learning rate
  * Allowed error
  * Number of neurons per hidden layer
* Results:

  * Desired output vs. network output
  * Training, validation, and test error curves
  * Final error metrics for each phase

---

## 🗂️ Repository Structure

```
Neural-GUI-MATLAB/
│
├── app/
│   └── Neural_GUI.m            # Main MATLAB App Designer file
|
├── data/
│
├── figures/                    # Generated plots and figures
│
└── README.md
```

---

## 🛠️ Tools & Technologies

* MATLAB
* App Designer
* Custom implementations of:

  * Perceptron
  * ADALINE
  * Multilayer Neural Networks

---

## 👤 Authors

* *Felipe Mercado Mercado & José David Gómez Bedoya*


## ✅ Notes

* All algorithms are implemented manually (no AI auto-code tools).
* Input validation is included for `.txt` files.
* Code is documented for academic and learning purposes.
