# RFM-Cohort-Analysis

# 🧩 RFM Prediction Project

## 📖 Overview

This project performs **customer segmentation and prediction** using **RFM (Recency, Frequency, Monetary) analysis**.
RFM analysis is a powerful marketing technique that helps businesses understand customer behavior based on their purchase patterns — how recently, how frequently, and how much they spend.

By analyzing these metrics, we can segment customers into distinct groups and identify high-value, at-risk, or dormant customers for targeted marketing strategies.

---

## 🎯 Objectives

* Calculate **RFM metrics** from transactional data.
* Assign **RFM scores** and derive **customer segments**.
* Apply **machine learning models** to predict customer behavior.
* Visualize insights and segment characteristics for actionable decisions.

---

## 🧠 Methodology

1. **Data Preparation**

   * Load and clean transactional data.
   * Handle missing values and duplicates.
   * Filter relevant date ranges and customer transactions.

2. **Feature Engineering**

   * Compute Recency, Frequency, and Monetary metrics for each customer.
   * Normalize or scale RFM values for model input.

3. **Segmentation**

   * Assign RFM scores (1–5 scale) based on quantiles or thresholds.
   * Combine scores into segments (e.g., “Champions”, “Loyal Customers”, “At Risk”, “Hibernating”).

4. **Modeling**

   * Use **K-Means clustering** (or alternative ML models) to identify customer groups.
   * Evaluate and visualize cluster characteristics.

5. **Visualization**

   * Generate plots for RFM distributions and cluster insights using Matplotlib and Seaborn.

---

## 🧰 Tech Stack

| Category             | Tools               |
| -------------------- | ------------------- |
| Language             | Python 3.x          |
| Data Handling        | Pandas, NumPy       |
| Visualization        | Matplotlib, Seaborn |
| Machine Learning     | Scikit-learn        |
| Notebook Environment | Jupyter Notebook    |

---

## 📊 Results

* Customers are segmented into groups based on their purchase behavior.
* Key insights on customer loyalty, value, and churn risk are visualized.
* The model helps identify segments for targeted marketing actions.

Example segments:

| Segment       | Description                                      |
| ------------- | ------------------------------------------------ |
| Champions     | Recent, frequent, and high-spending customers    |
| Loyal         | Frequent buyers with moderate spending           |
| At Risk       | Previously active but haven’t purchased recently |
| Hibernating   | Long inactive customers                          |
| New Customers | Recently acquired users with few purchases       |

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/RFM-prediction-project.git
cd RFM-prediction-project
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

Open the notebook in Jupyter:

```bash
jupyter notebook "RFM prediction Project.ipynb"
```

---

## 📂 Project Structure

```
RFM-prediction-project/
│
├── RFM prediction Project.ipynb     # Main analysis notebook
├── data/                            # Folder for dataset(s)
├── results/                         # Output visuals or CSVs
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies
```

---

## 📈 Example Visuals

* RFM distribution plots
* Cluster heatmaps
* Customer segment visualizations

*(Visuals generated within the notebook)*

---

## 💡 Future Improvements

* Integrate **predictive models** for churn probability.
* Automate **real-time RFM updates** from live transactional data.
* Build a **dashboard (Streamlit/Power BI)** for interactive analysis.

---

## 📜 License

This project is released under the **MIT License**.
Feel free to use, modify, and share for educational or commercial purposes.

---

## 👤 Author

**[PRAKASH P]**
📧 [[prakashsivam725@gmail.com]]
🌐 [[LinkedIn / GitHub / Portfolio link]](https://www.linkedin.com/in/prakash-p-294937251?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

