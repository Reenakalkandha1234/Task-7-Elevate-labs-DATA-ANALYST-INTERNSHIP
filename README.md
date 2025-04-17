

# 📊 Task 7:  Get Basic Sales Summary from a Tiny SQLite Database using Python
## 🧠 Objective

To generate and analyze a dataset of sales information using SQL within Python, and visualize it through various chart types including bar, pie, and line charts. This task provides insights into:
- Total quantity sold
- Revenue per product
- Regional performance
- Monthly sales trends

---

## 🛠 Tools & Technologies Used

- **Python 3**
- **SQLite3** (Built-in with Python)
- **Pandas** (For data manipulation)
- **Matplotlib** (For data visualization)
- **Jupyter Notebook** or `.py` script

---

## 🗃 Dataset

The dataset was generated synthetically using Python. It includes 150+ records with the following fields:

- `product`: Name of the product (e.g., Laptop, Mouse)
- `category`: Product category (Electronics or Accessories)
- `quantity`: Quantity sold
- `price`: Price per unit
- `region`: Region of sale (North, South, East, West)
- `sale_date`: Date of sale (random dates from Jan 2024)

---

## 📌 Features & Analysis Performed

### ✅ Data Generation
- Used Python and `random` module to generate diverse sales entries
- Inserted data into an SQLite database table `sales`

### ✅ SQL Queries & Python Integration
- Connected to the database using `sqlite3`
- Executed queries to analyze:
  - Total quantity and revenue by product
  - Revenue by region
  - Top 10 product-region combinations by revenue
  - Monthly revenue trends
  - Product-wise quantity distribution

### ✅ Visualizations
- **Bar Charts** for:
  - Product-wise quantity and revenue
  - Top 10 product-region revenue
- **Pie Charts** for:
  - Revenue by region
  - Product-wise quantity distribution
- **Line Chart** for:
  - Monthly revenue trend

---


