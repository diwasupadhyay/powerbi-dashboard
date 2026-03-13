# Power BI Sales Dashboard

An interactive sales analytics dashboard built with **Microsoft Power BI**, using real-world-style e-commerce order data from across India.

---

## Dashboard Preview

![Power BI Sales Dashboard](assets/dashboard-preview.png)

> Open the `.pbix` file in Power BI Desktop to explore the full interactive dashboard.

---

## Dataset

The project uses two CSV files as the data source:

### `Orders.csv`
| Column | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Order Date | Date the order was placed |
| CustomerName | Name of the customer |
| State | Indian state of delivery |
| City | City of delivery |

### `Details.csv`
| Column | Description |
|---|---|
| Order ID | Links to Orders.csv |
| Amount | Total order amount (₹) |
| Profit | Profit earned (₹) |
| Quantity | Number of items ordered |
| Category | Product category (Electronics, Furniture, Clothing) |
| Sub-Category | Product sub-category |
| PaymentMode | Payment method (COD, EMI, Credit Card, UPI) |

---

## Key Insights Covered

- **Total Sales, Profit & Quantity** — KPI summary cards
- **Sales by State & City** — Geographic breakdown
- **Category & Sub-Category Analysis** — Top-selling product segments
- **Payment Mode Distribution** — How customers prefer to pay
- **Monthly Sales Trend** — Performance over time

---

## Tools Used

- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/)
- CSV data files (no external database needed)

---

## How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/diwasupadhyay/powerbi-dashboard.git
   ```
2. Open **Power BI Desktop**
3. Open the `.pbix` file from the cloned folder
4. The dashboard will load with all visuals and data automatically

---

## Project Structure

```
powerbi-dashboard/
├── assets/
│   └── dashboard-preview.png   # Dashboard screenshot
├── Orders.csv                  # Customer and order info
├── Details.csv                 # Order financials and product details
├── Dashboard.pbix              # Power BI report file
└── README.md
```

---

## Author

**Diwas Upadhyay**  
[GitHub](https://github.com/diwasupadhyay)
