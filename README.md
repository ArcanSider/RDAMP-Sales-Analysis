# RDAMP-Sales-Analysis

## 1. Approach and Tools Used

In this analysis, we explore the sales performance data of Ace Superstore to gain insights into regional sales performance, product category profitability, and customer behavior. The main objectives of this report were:

- **Summarize total sales, revenue, and discount rates** by region and product category.
- **Identify best-selling products** and underperforming products by revenue.
- **Provide insights into product categories with the highest margins**.
- **Analyze sales distribution across Order Modes** (Online vs In-Store).

### Tools Used:
- **Python**: For data analysis and visualization.
- **Pandas**: For data manipulation and aggregation.
- **Matplotlib**: For creating visualizations (bar charts, pie charts).
- **VS Code**: For writing and running the code, and previewing the Markdown report.

## 2. Key Insights and Visualizations

### **Total Sales, Revenue, and Discount Rates by Region and Category**

#### Key Findings:
- The **East Midlands** region has the highest sales and revenue, particularly in categories such as *Accessories* and *Audio*.
- Categories like **Automotive** and **Art Supplies** have significant sales but varying revenue across regions.
  
#### Visualization:
![Sales by Region](visualizations/sales_by_region.png)
*Bar chart showing total sales by region.*

### **Sales Distribution Across Order Mode (Online vs In-Store)**

#### Key Findings:
- **Online orders** generate slightly higher total sales compared to **In-store** sales. This suggests that customers prefer shopping online over visiting stores.
  
#### Visualization:
![Sales Distribution by Order Mode](visualizations/sales_distribution_by_order_mode.png)
*Pie chart showing the distribution of sales between online and in-store orders.*

### **Top 5 Best-Selling Products by Revenue**

#### Key Findings:
- The **Electric Bike** is the top-performing product, with the highest total revenue.
- Other popular products include the **Digital Camera** and **Compact Digital Camera**.

#### Visualization:
![Top 5 Best-Selling Products](visualizations/top_5_best_selling_products.png)
*Bar chart showing the top 5 best-selling products by revenue.*

### **Product Categories with the Highest Margins**

#### Key Findings:
- Categories such as **Kitchen**, **Outdoor**, and **Electronics** have the highest profit margins, making them the most profitable categories.

#### Table:
| Category      | Total Margin |
|---------------|--------------|
| Kitchen       | 12480.50     |
| Outdoor       | 10803.11     |
| Electronics   | 7574.99      |
| Home          | 7201.22      |
| Fitness       | 4843.01      |

### **Underperforming Products**

#### Key Findings:
- Products such as **LED Strip Lights Kit** and **Electric Milk Frother** have shown zero revenue, suggesting potential issues with sales or stock availability.

#### Table:
| Product Name                   | Total Revenue |
|---------------------------------|---------------|
| LED Strip Lights Kit            | 0.00          |
| Electric Milk Frother           | 0.00          |
| Chic Ankle Strap Heels          | 0.00          |
| Workstation Laptop Stand        | 0.00          |
| Garden Hose Reel                | 0.00          |

## 3. Conclusions and Recommendations

### **Conclusions**:
- The **East Midlands** and **London** regions lead in total sales and revenue, with **Accessories** and **Automotive** categories performing well across regions.
- **Online orders** are favored over in-store orders, suggesting a growing preference for e-commerce.
- The **Kitchen** and **Outdoor** categories are the most profitable, and there is a significant opportunity to increase sales in these high-margin areas.

### **Recommendations**:
1. **Focus marketing efforts on high-margin categories**, such as *Kitchen* and *Outdoor*, to maximize profitability.
2. **Investigate underperforming products** like the *LED Strip Lights Kit* and *Electric Milk Frother* to identify the cause of low sales.
3. **Expand efforts in the online sales channel**, given the higher performance compared to in-store sales.
4. **Boost in-store sales strategies** in regions with low in-store sales, especially in areas where online sales are higher.

---

## 4. How to Reproduce the Analysis

### Prerequisites:
To reproduce the analysis, you will need to install the following Python packages:

```bash
pip install pandas matplotlib
