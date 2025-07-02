# 🌸 K-Nearest Neighbors (KNN) on Iris Dataset  
> *"Can a machine learn to recognize flowers just by looking at their neighbors?"*

---

## 👋 Welcome!

In this project, we use a very simple — but surprisingly powerful — algorithm called **K-Nearest Neighbors (KNN)** to teach a computer how to **classify flowers**.

You’ll not only learn how to **build and evaluate KNN**, but also **see how it thinks** using **colorful visualizations**.

If you're a beginner in Machine Learning, this is a great starting point to understand:

- What is KNN?
- How does it make decisions?
- What does “choosing K” really mean?
- Why scaling your data matters?

---

## 🌱 The Story Behind the Dataset

We use the **Iris dataset** — one of the most famous datasets in data science.

Each flower is described by:
- 🌿 **Sepal Length**
- 🌿 **Sepal Width**
- 🌸 **Petal Length**
- 🌸 **Petal Width**

Our goal?  
To correctly classify the flower as one of:
- **Iris-setosa**
- **Iris-versicolor**
- **Iris-virginica**

With just a few centimeters of measurement — can our machine *guess the flower's species*?

Let’s find out.

---

## 🧠 What Is KNN?

> KNN is like asking your neighbors for advice.

It looks at the **K closest data points** (neighbors) and takes a vote to decide the class. That’s it. No training, no equations — just proximity and majority voting.

Simple, yet surprisingly effective for classification.

---

## 🛠️ What We Did — Step by Step

| 🔢 Step | What We Did |
|--------|-------------|
| 1️⃣ | Loaded the Iris dataset (`Iris.csv`) |
| 2️⃣ | Dropped unnecessary columns (`Id`) |
| 3️⃣ | Normalized features using `StandardScaler` |
| 4️⃣ | Split into training & test sets |
| 5️⃣ | Trained KNN using `KNeighborsClassifier` from Scikit-learn |
| 6️⃣ | Tested multiple values of `K` (from 1 to 10) |
| 7️⃣ | Evaluated using **accuracy**, **confusion matrix**, and **classification report** |
| 8️⃣ | Visualized **decision boundaries** using 2D plots |

---

## 🧪 Tools Used

- `pandas` 🐼 – for data handling  
- `scikit-learn` ⚙️ – for KNN, scaling, metrics  
- `matplotlib` & `seaborn` 🎨 – for visualizing model and results  
- `numpy` – for numerical operations

---

## 📊 Key Visualizations

### 📌 Accuracy vs K
We plotted how the model’s accuracy changes with different values of **K** (neighbors).  
This helps us choose the **best K** for this problem.

### 📌 Confusion Matrix
A breakdown of correct vs incorrect predictions — shows where the model struggles.

### 📌 🌈 Decision Boundary Plot
We created a beautiful, color-coded map showing **how KNN splits the world** into regions.  
Each region is where KNN thinks a particular flower species belongs.

> It’s like watching the algorithm’s **“thought process”** come to life!

---

## 🔍 What You’ll Learn

✅ How KNN works in practice  
✅ Why normalization is critical  
✅ How to evaluate classification models  
✅ How decision boundaries are formed  
✅ How feature choice affects learning  
✅ Visual intuition over black-box thinking

---

## 🧠 Sneak Peek

![KNN Decision Boundary Example](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/KnnClassification.svg/640px-KnnClassification.svg.png)

*Replace this image with your actual output when possible.*

---

## ▶️ Run This Yourself

```bash
# Install dependencies
pip install -r requirements.txt

# Run the script
python knn_iris.py

# Or open the notebook
jupyter notebook KNN_Iris.ipynb
```

---

## 📂 Project Structure

```
📦 KNN-Iris-Classification
 ┣ 📄 Iris.csv
 ┣ 📄 knn_iris.py
 ┣ 📄 KNN_Iris.ipynb
 ┣ 📄 README.md
 ┗ 📄 requirements.txt
```

---

## 💬 Suggested Experiments

🔁 Try different values of `K` (e.g. 1, 3, 5, 10)  
📏 Try using different feature combinations  
📉 Add noise and see how it affects predictions  
🌐 Try with a different dataset (e.g., Breast Cancer, Wine)

---

## 🙋 Who This Is For

✅ Beginners in Machine Learning  
✅ Students working on ML assignments  
✅ Anyone who wants to *visualize* how an algorithm "thinks"


> “A machine learning model is only as smart as the features you give it. But sometimes, even the simplest model can surprise you.”

