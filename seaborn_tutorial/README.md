# 📊 Seaborn Tutorial – Complete Guide

This repository provides a **step-by-step tutorial on Seaborn**, one of the most powerful Python libraries for **data visualization in Data Science and Machine Learning**.

---

## 🚀 What is Seaborn?

Seaborn is a Python data visualization library built on top of Matplotlib. It provides a **high-level interface** for creating **attractive and informative statistical graphics**.

---

## 📦 Installation

```bash
pip install seaborn
```

---

## 📚 Topics Covered

* Introduction to Seaborn
* Figure-Level vs Axes-Level Functions
* Distribution Plots
* Relational Plots
* Categorical Plots
* Regression Plots
* Heatmaps
* Styling & Themes

---

## 🧠 Why Use Seaborn?

* Built-in themes for better visuals
* Works seamlessly with Pandas DataFrames
* Simplifies complex visualizations
* Ideal for statistical analysis

---

## 📊 Basic Example

```python
import seaborn as sns
import matplotlib.pyplot as plt

tips = sns.load_dataset("tips")

sns.scatterplot(data=tips, x="total_bill", y="tip")
plt.show()
```

---

## 📈 Example Plots

### 🔹 Distribution Plot

```python
sns.histplot(data=tips, x="total_bill", kde=True)
```

### 🔹 Categorical Plot

```python
sns.barplot(data=tips, x="day", y="total_bill")
```

### 🔹 Heatmap

```python
corr = tips.corr(numeric_only=True)
sns.heatmap(corr, annot=True)
```

---

## 🎨 Styling Example

```python
sns.set_style("darkgrid")
sns.set_palette("pastel")
```

---

## 🧪 Mini Project Idea

📌 Analyze a dataset (like Titanic or Tips) and create:

* Distribution plots
* Correlation heatmap
* Category comparisons

---

## 🌐 Part of Bigger Project

This tutorial is part of my repository:

👉 **AI & ML Libraries Guide**

Where I document all essential libraries required to become a **Data Scientist / ML Engineer**.

---

## 💡 Bonus

I also built an **AI-powered learning tool using prompt engineering** to explain libraries interactively.

---

## 🤝 Contributing

Feel free to:

* Fork this repo
* Improve explanations
* Add more examples

---

## ⭐ Support

If this helped you, consider giving it a ⭐ on GitHub!
