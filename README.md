# 🛒 SmartCart Customer Segmentation

This project performs customer segmentation using K-Means clustering to identify distinct groups of customers based on their behavior and features.

---

## 📁 Project Structure

```
SmartCart/
│── smartcart.ipynb          # Main notebook (K-Means + PCA + Elbow Method)
│── smartcart_customers.csv  # Dataset
│── requirements.txt         # Dependencies
│── README.md                # Project documentation
│── elbow.png                # Elbow method graph
```

---

## 🚀 Features

* Customer segmentation using K-Means clustering
* Dimensionality reduction using PCA
* Optimal cluster detection using Elbow Method (KneeLocator)
* Data visualization for insights

---

## 📊 Elbow Method

![Elbow Graph](elbow.png)

The elbow point in the graph indicates the optimal number of clusters for customer segmentation.

---

## 🧰 Libraries Used

* scikit-learn
* pandas
* matplotlib
* kneed

---

## 📌 How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/smartcart.git
```

2. Navigate to the project folder:

```
cd smartcart
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the notebook:

```
smartcart.ipynb
```

---

## 📈 Output

* Segmented customer groups
* Visualization of clusters
* Optimal number of clusters using Elbow Method

---

## 💡 Future Improvements

* Add interactive visualizations
* Deploy as a web app
* Use advanced clustering algorithms

---
