# iris-flower-classification-ann
Artificial Neural Network (ANN) model built with TensorFlow/Keras to classify Iris flowers into Setosa, Versicolor, and Virginica species.

# Iris Flower Classification using Artificial Neural Networks (ANN)

## 📌 Project Overview

This project implements an Artificial Neural Network (ANN) using TensorFlow/Keras to classify Iris flowers into three species:

- Setosa
- Versicolor
- Virginica

The model is trained on the famous Iris dataset and demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model training, evaluation, model saving, and prediction on unseen samples.

---

## 🎯 Objective

To build a deep learning model capable of accurately classifying Iris flowers based on their sepal and petal measurements.

---

## 📊 Dataset

The Iris dataset contains 150 flower samples with the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:

| Class | Label |
|---------|---------|
| Setosa | 0 |
| Versicolor | 1 |
| Virginica | 2 |

Dataset Source: Scikit-Learn Iris Dataset

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow
- Keras
- Matplotlib
- Seaborn

---

## ⚙️ Project Workflow

### 1. Import Libraries
- Load required Python libraries.

### 2. Load Dataset
- Load the Iris dataset using Scikit-Learn.
- Convert the dataset into a Pandas DataFrame.

### 3. Data Preprocessing
- Check for missing values.
- Explore dataset structure.
- Encode target labels.
- Split data into training and testing sets.
- Apply feature scaling using StandardScaler.

### 4. Build ANN Model
- Input Layer
- Hidden Layers with ReLU activation
- Output Layer with Softmax activation

### 5. Train Model
- Train the ANN using training data.
- Monitor training and validation accuracy.

### 6. Evaluate Model
- Calculate test accuracy.
- Generate predictions.
- Analyze model performance.

### 7. Save Model
- Save trained ANN model.
- Save fitted scaler for future predictions.

### 8. Predict New Samples
- Test the model using unseen Iris flower measurements.

---

## 🧠 ANN Architecture

```text
Input Layer (4 Features)
        ↓
Dense Layer (16 Neurons, ReLU)
        ↓
Dense Layer (8 Neurons, ReLU)
        ↓
Output Layer (3 Neurons, Softmax)
```

---

## 📈 Model Performance

The model achieves high classification accuracy on the Iris dataset due to the clear separation between flower species.

Example Metrics:

- Accuracy: ~95% - 100%
- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam

---

## 📂 Project Structure

```text
iris-flower-classification-ann/
│
├── Iris Classification.ipynb
├── iris_ann_model.h5
├── scaler.pkl
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/iris-flower-classification-ann.git
```

Navigate to the project folder:

```bash
cd iris-flower-classification-ann
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
Iris Classification.ipynb
```

---

## 🔮 Sample Prediction

Example Input:

```python
[[5.1, 3.5, 1.4, 0.2]]
```

Predicted Output:

```text
Setosa
```

---

## 📷 Visualization

The project includes:
- Training Accuracy Graph
- Validation Accuracy Graph
- Loss Curve
- Dataset Exploration Charts

---

## 📌 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deploy as a web application
- Convert model into REST API

---

## 👨‍💻 Author

Mohammed Sinan

---

## ⭐ Support

If you found this project useful, please give it a ⭐ on GitHub.
