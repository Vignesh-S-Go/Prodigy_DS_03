# Prodigy InfoTech Data Science Internship — Task 03

## 📄 Task Overview
**Task 03:** Build a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their demographic and behavioral data.  

The dataset used is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

---

## 📊 Dataset Information
The dataset is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls to promote term deposit subscriptions.

### **Features Include:**
- **Client Information:** `age`, `job`, `marital`, `education`, `default`, `housing`, `loan`
- **Contact Information:** `contact`, `month`, `day_of_week`
- **Campaign Information:** `campaign`, `pdays`, `previous`, `poutcome`
- **Socioeconomic Indicators:** `emp.var.rate`, `cons.price.idx`, `cons.conf.idx`, `euribor3m`, `nr.employed`
- **Target:** `y` — whether the client subscribed to a term deposit (`yes` or `no`)

---

## 🛠️ Tools and Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 🔍 Process

### ✔️ Data Preprocessing
- Loaded and explored the dataset.
- Handled categorical variables using **Label Encoding**.
- Handled missing or unknown values appropriately.

### ✔️ Model Building
- Split the data into **training and testing sets**.
- Built a **Decision Tree Classifier** using `scikit-learn`.
- Limited tree depth to prevent overfitting.

### ✔️ Model Evaluation
- Evaluated using:
  - **Accuracy**
  - **Classification Report** (Precision, Recall, F1-Score)
  - **Confusion Matrix**
- Visualized the decision tree structure.

---

## 📈 Results and Observations
- The Decision Tree model effectively classified customers based on their likelihood to subscribe.
- **Confusion Matrix** and **Classification Report** provided detailed evaluation metrics.
- **Decision Tree Plot** helped visualize decision-making paths based on features like `contact`, `poutcome`, `previous`, and `euribor3m`.

---

## 📌 Conclusion
The Decision Tree Classifier successfully modeled the relationship between customer attributes and their subscription decisions. This task demonstrates how machine learning models can assist businesses in understanding customer behavior and improving marketing strategies.

---

## 🙏 Thank You
Thank you for reviewing my submission for **Task 03** of the Prodigy InfoTech Data Science Internship.
