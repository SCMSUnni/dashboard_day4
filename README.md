# Superstore Sales Dashboard (Power BI)

## 📌 Overview
This project is an interactive **Power BI Sales Analytics Dashboard** built using the popular *Superstore Sales Dataset*.  
The dashboard provides insights into sales performance, profit trends, customer purchasing behavior, and regional performance to support data-driven business decisions.

---

## 🗂 Data Source
- **File:** `SuperStore Sales DataSet.xlsx`
- **Type:** Excel Dataset
- **Domain:** Retail / E-commerce
- **Key Fields:**
  - Order Date
  - Ship Date
  - Category & Sub-Category
  - Region
  - Sales
  - Profit
  - Quantity
  - Ship Mode
  - Payment Mode

---

## 📊 Dashboard Components

### 🔢 Key KPIs
- **Total Revenue**
- **Total Profit**
- **Units Sold**
- **Average Ship Days**

### 📈 Visualizations
- Sales by Category
- Sales by Sub-Category
- Sales by Ship Mode
- Sales by Region
- Payment Methods Distribution
- Monthly Sales Trend (YoY)
- Monthly Profit Trend (YoY)

### 🎛 Filters & Slicers
- Region slicer (Central, East, South, West)
- Year comparison (2019 vs 2020)

---

## 🧠 Data Model
- Single fact table sourced from Excel
- Date-based calculations using Order Date
- Measures created using DAX for KPIs and YoY comparisons

---

## 🧮 Key DAX Measures (Examples)
- Total Sales
- Total Profit
- Units Sold
- Average Ship Days
- Sales YoY Growth
- Profit YoY Growth

---

## 🗺 Map Visuals
- Geographic sales distribution by region
- Uses **Bing Maps**
> Note: Map visuals require enabling in  
> `File → Options → Security → Use map and filled map visuals`

---

## 🚀 How to Open the Project
1. Install **Power BI Desktop**
2. Download the `.pbix` file
3. Open Power BI Desktop → File → Open → Select `superstore dashboard.pbix`
4. Ensure map visuals are enabled (Security settings)

---

## 🧪 Key Business Insights
- Technology category contributes the highest revenue
- West and East regions lead in overall sales
- COD is the most used payment method
- Profit shows seasonal spikes towards year-end

---

## 🛠 Tools Used
- Power BI Desktop
- Microsoft Excel

---

## 📎 Use Cases
- Academic project
- Portfolio showcase
- Business intelligence demonstration
- Interview discussion project

---

## 📄 License
This project is for educational and demonstration purposes only.
