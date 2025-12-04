# 📦 **Lithium – Product Recommendation System**

*An intelligent ML-powered recommendation engine delivering accurate, personalized product suggestions.*

---

## 🔰 **Overview**

Lithium is a Machine Learning–based Product Recommendation System designed to predict user preferences and generate tailored product suggestions. Built using advanced ML models, clean feature engineering, and a Streamlit-based UI, Lithium enhances user engagement and improves product discovery by analyzing rating behavior across thousands of users and items.


---

## 🚀 **Key Features**

* 🔍 **Personalized Recommendations** using Random Forest Classifier
* 📊 **Exploratory Data Analysis (EDA)** with rating distribution, user activity, and product popularity
* 🧹 **Clean Dataset:** 78K records, no missing values, no duplicates
* 🧠 **Multiple ML Models Tested:** Logistic Regression, Random Forest, SVM, Decision Tree, Naive Bayes, KNN
* 🎯 **100% Accuracy** in top-performing models
* 🌐 **Streamlit Web App** for real-time recommendations
* 📦 **Production-ready deployment package**


---

## 📁 **Dataset Summary**

| Attribute           | Description                             |
| ------------------- | --------------------------------------- |
| **78,000 records**  | Full interaction dataset                |
| **76,000 users**    | Large and diverse user base             |
| **40,000 products** | Wide product catalog                    |
| **Columns**         | `userid`, `productid`, `rating`, `date` |

* ✔ No missing values
* ✔ No duplicates
* ✔ Rating scale: **1–5 stars**


---

## 📊 **Exploratory Data Analysis (Highlights)**

* ⭐ Majority of ratings are **4 & 5 stars** (positive sentiment)
* 🔥 Most products have very few ratings (long-tail effect)
* 👤 Most users rate only one item
* 📈 Platform engagement increases steadily over time


---

## 🤖 **Model Training & Evaluation**

**Models Tested:**

* Logistic Regression
* Random Forest
* K-Nearest Neighbors
* Naive Bayes
* Support Vector Machine
* Decision Tree

**Result:**
✔ **Random Forest, Logistic Regression, SVM, Decision Tree = 100% accuracy**
✔ Random Forest selected for deployment due to consistency & generalization


---

## 🏆 **Final Model – Random Forest Classifier**

**Input:**

* `User ID`
* `Product ID`

**Output:**

* Top-N recommended products

**Why Random Forest?**

* High accuracy
* Low overfitting
* Handles sparse data well
* Fast inference time


---

## 🖥️ **Application Interface (Streamlit)**

Your app provides:

### ⭐ **Home Page**

* Clean UI
* Popular product highlights
* Easy user navigation

### ⭐ **Recommendations Page**

* Displays personalized recommendations
* Accepts user inputs
* Fast ML-powered predictions


---

## 📦 **Project Structure**

```
Lithium-Recommendation-System/
│
├── data/
│   └── interactions.csv
│
├── models/
│   └── random_forest.pkl
│
├── notebooks/
│   └── EDA.ipynb
│
├── app/
│   ├── app.py            # Streamlit app
│   └── utils.py
│
├── requirements.txt
└── README.md
```

---

## ⚙️ **Installation & Setup**

### **1️⃣ Clone the repository**

```bash
git clone https://github.com/your-username/Lithium-Recommendation-System.git
cd Lithium-Recommendation-System
```

### **2️⃣ Install dependencies**

```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Streamlit app**

```bash
streamlit run app/app.py
```

---

## 🌐 **Deployment Options**

* Streamlit Cloud
* Render
* HuggingFace Spaces
* Docker container deployment

*(I can generate Dockerfile or Streamlit Cloud config if you want!)*

---

## 🛠️ **Tech Stack**

* **Python**
* **Pandas, NumPy**
* **Scikit-Learn**
* **Random Forest Classifier**
* **Matplotlib, Seaborn**
* **Streamlit**

## 🙌 **Contributors**

* Sunitha
* Govardhan Reddy Sunkara
* Shaik Shamiulla
* Pavan Dudi
* Dharani A
* M. Bharath Kumar Reddy
* Tanisha Giri
  **Mentor:** Karthik




