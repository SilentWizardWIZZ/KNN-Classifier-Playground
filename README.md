# 🧪 KNN Classifier Playground

This project is a simple and interactive implementation of the **K-Nearest Neighbors (KNN)** algorithm to classify data visually. It is designed as a learning tool to understand how the KNN algorithm works by allowing users to interact with the classifier in 2D space.

---

## 🧠 What is KNN?

**K-Nearest Neighbors (KNN)** is a **supervised machine learning algorithm** used for **classification and regression**.  
In classification, it works by:

1. Storing all training data.
2. For a new data point, it finds the **K nearest neighbors** (using distance like Euclidean).
3. It assigns the class that is most common among those K neighbors.

➡️ KNN is a **lazy learner** — it doesn’t train a model in advance, but makes decisions when predictions are requested.

---

## 🎯 Features

- Interactive dataset plotting
- Adjustable **K** value slider
- Real-time classification of new data points
- Visualization of decision boundaries (optional)

---

## 💻 Technologies Used

- Python
- Scikit-learn
- Matplotlib
- NumPy
- Streamlit (for UI, if used)

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
