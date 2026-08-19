# 🛒 Nexora.ai – E-Commerce Intelligence

Nexora.ai is a **Python and Streamlit-based E-Commerce Business Analytics Dashboard** that helps analyze sales, customers, products, marketing performance, delivery, and returns from an uploaded CSV dataset.

## 🚀 Features

* 📂 Upload E-Commerce CSV files directly
* 📊 Command Center with business KPIs
* 💰 Revenue and Profit analysis
* 🛍️ Order and Customer analysis
* 📦 Product performance analysis
* 🎯 Marketing Channel analysis
* 🚚 Delivery and Return analysis
* 🧠 Rule-based AI Business Advisor
* 🔎 Data Explorer with search functionality
* 📥 Download filtered data as CSV
* 📅 Date and Year filters
* 🏙️ City filter
* 🏷️ Product Category filter
* 📢 Marketing Channel filter

## 🛠️ Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Matplotlib

## 📁 Project Structure

```text
Nexora.ai/
│
├── app.py
├── README.md
└── dataset.csv
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Go to the project folder:

```bash
cd YOUR-REPOSITORY
```

Install the required libraries:

```bash
pip install streamlit pandas numpy matplotlib
```

## ▶️ Run the Project

Start the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your browser.

## 📂 How to Use

1. Start the Streamlit application.
2. Upload your E-Commerce CSV file using the sidebar.
3. Select filters such as:

   * City
   * Product Category
   * Marketing Channel
   * Date Range
   * Year
4. Explore the different dashboard sections.
5. Use **Data Explorer** to search and view records.
6. Download the filtered dataset when required.

## 📊 Dashboard Sections

### Command Center

Provides an overview of the business with:

* Total Revenue
* Total Profit
* Total Orders
* Customers
* Conversion Rate
* Return Rate
* Revenue Trends
* Category Performance
* Marketing Performance

### Sales Intelligence

Analyzes:

* Revenue
* Profit
* Profit Margin
* Daily Sales
* Category Performance

### Customer Intelligence

Analyzes:

* Unique Customers
* Customer Lifetime Value
* Customer Value Score
* Customer Segments
* Customer Age vs Lifetime Value

### Product Intelligence

Analyzes:

* Products
* Units Sold
* Revenue
* Profit
* Return Rate
* Category Performance

### Marketing Intelligence

Analyzes:

* Marketing Channels
* Orders
* Revenue
* Profit
* Website Visits
* Conversion Rate

### Delivery & Returns

Analyzes:

* Average Delivery Time
* Returned Orders
* Return Rate
* Return Reasons
* Delivery Days vs Return Risk

### AI Business Advisor

Provides rule-based business recommendations based on:

* Return Rate
* Profit Margin
* Top Product Categories
* Top Cities
* Marketing Channels
* High-Risk Products

> Note: The AI Business Advisor is a rule-based analytical module and is not a machine-learning predictive model.

### Data Explorer

Allows users to:

* Search orders
* Search customers
* Search products
* Search cities
* Search categories
* View filtered records
* Download filtered CSV data

## 📌 Dataset Requirements

The uploaded CSV should contain the columns required by the dashboard, such as:

```text
Order_ID
Order_Date
Customer_ID
City
Product_Category
Product
Revenue
Profit
Quantity
Return_Status
Return_Reason
Marketing_Channel
Customer_Segment
Conversion_Rate_pct
Delivery_Days
Customer_Rating
Shipping_Cost
Customer_Lifetime_Value
Customer_Value_Score
Return_Risk_Score
Profit_Margin_pct
Website_Visits
```

## 🎯 Project Purpose

The purpose of Nexora.ai is to provide a simple business intelligence dashboard for analyzing e-commerce data and helping users understand important business metrics through interactive visualizations and filters.

## 👨‍💻 Developer

**Tanmay Bagade**

Python & Streamlit Data Analyst

## ⭐ Future Improvements

* Machine Learning-based sales prediction
* Customer churn prediction
* Advanced forecasting
* Automated PDF reports
* More interactive charts
* Database integration
* Real-time e-commerce analytics

---

⭐ If you find this project useful, consider giving the repository a star!
