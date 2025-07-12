# 📊 Flipkart Customer Support - Exploratory Data Analysis (EDA)

This project performs an in-depth Exploratory Data Analysis (EDA) on **Flipkart's customer support data**, focusing on agent performance, CSAT scores, customer remarks, and issue resolution efficiency.

---

## 🔍 Objective

- Analyze customer service efficiency using timestamps, satisfaction scores, and remarks.
- Visualize key metrics such as response time, agent shift impact, and issue categories.
- Identify trends and actionable insights to improve support team performance.

---

## 📁 Dataset

📌 **File**: `Customer_support_data.csv`

### Key Columns:
- `Order_id`, `Issue_reported_at`, `issue_responded`, `Survey_response_Date`
- `CSAT Score`, `connected_handling_time`, `Item_price`
- `Agent_name`, `Agent Shift`, `Supervisor`, `Tenure Bucket`
- `Customer Remarks`, `channel_name`, `Product_category`, etc.

---

## 📊 Analysis Highlights

- ✅ Calculated response_time_minutes from issue reported and responded timestamps.
- ✅ Analyzed average CSAT scores by shift and supervisor.
- ✅ Plotted correlation heatmaps between price, handling time, CSAT score.
- ✅ Explored category-wise issue frequencies and visualized via bar plots.
- ✅ Investigated relationships between handling time and CSAT.
- ✅ Text analysis of customer remarks (future scope).

---

## 📈 Visualizations Included

- 🔥 Correlation Heatmap: Price vs. CSAT vs. Response Time
- 📊 Bar Charts: CSAT Score by Agent Shift
- 📉 Distribution Plots: Handling Time & Response Time

---

## 💻 Tech Stack

- Python
- Pandas, NumPy  
- Matplotlib, seaborn  
- Jupyter Notebook
