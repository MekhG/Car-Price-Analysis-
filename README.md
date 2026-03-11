# Car-Price-Analysis
An exploratory analysis of Indian car market pricing from 2015 to 2024, covering 10 major brands and multiple models. The project examines how price, mileage, engine capacity, fuel type, and service cost relate to each other and which brands and fuel types offer the best overall value.

## 📊 Dashboard Preview
<img width="622" height="278" alt="image" src="https://github.com/user-attachments/assets/109fadf6-caaa-4726-b629-31446db18664" />

<img width="637" height="355" alt="image" src="https://github.com/user-attachments/assets/1d1b79ff-6ebb-4004-a670-2008617413b9" />

## 🗂️ Dataset
| Column | Description |
|---|---|
| `Car_ID` | Unique identifier |
| `Brand` | Manufacturer (Honda, Kia, Mahindra etc.) |
| `Model` | Car model name |
| `Year` | Year of manufacture (2015–2024) |
| `Fuel_Type` | CNG, Diesel, Electric, Petrol |
| `Transmission` | Manual / Automatic |
| `Price` | Price in INR |
| `Mileage` | Fuel efficiency (km/l) |
| `Engine_CC` | Engine displacement in CC |
| `Seating_Capacity` | Number of seats |
| `Service_Cost` | Annual service cost in INR |

---

## 🔍 Key Findings

| Metric | Value |
|---|---|
| Most Affordable Car | Mahindra XUV 700 (Electric, Automatic) |
| Highest Avg Price Brand | Mahindra |
| Best Mileage Fuel Type | CNG |
| Lowest Service Cost Brand | Honda |
| High Mileage, Low Cost Car | Kia EV6 (₹18,800) |

### Price Insights
- **Mahindra** leads in average price — premium positioning in the Indian market
- **Tata Motors and Kia** follow close behind in average pricing
- **Maruti Suzuki** remains the most budget-friendly brand on average

### Mileage Insights
- **CNG vehicles** deliver the highest mileage across all fuel types (~50+ km/kg)
- **Electric vehicles** show strong mileage equivalent but high upfront pricing
- **Diesel** offers better mileage than Petrol but higher service costs

### Service Cost Insights
- **Honda** has the lowest average service cost — strong value for money
- **Renault and Maruti Suzuki** also rank low in service costs
- Higher engine CC vehicles generally attract higher service costs

---

## 🛠️ Tools Used
- **Excel** — Data cleaning, EDA, pivot analysis,
  - Dashboard: Brand comparison, bubble chart (Price vs Mileage by Engine CC), service cost ranking
- **Power BI** — Two-page interactive dashboard (light + dark theme)
  - Dark theme with scatter plot, KPI cards, brand slicer
- **SQL (SQLite via Python/Kaggle)** — data cleaning, price analysis as per engine cc, transmission, mileage, etc.
---

## 📁 Repository Structure
```
car-price-analysis/
│
├── data/
│   └── car_price_data.csv
│
├── excel/
│   └── car_price_analysis.xlsx
|
├── sql/
│   └── car_data_queries.ipynb
|
├── dashboard/
│   └── car_price_dashboard.pbix
│
└── README.md
```

---

## 📈 Analysis Steps
1. Loaded dataset and performed EDA in Excel
2. Identified most affordable, highest priced, and best mileage cars
3. Built brand-wise average price and service cost comparisons
4. Created bubble chart correlating Price vs Mileage by Engine CC and Brand
5. Analysed fuel type mileage distribution
6. Built interactive Power BI dashboard with brand, model, fuel type, and price slicers
7. Ran similar queries on SQL in Kaggle notebook
8. Designed second dark-theme page for portfolio presentation

---

## 🚀 How to Run
1. Clone the repo
2. Open `excel/car_price_analysis.xlsx` for EDA and dashboard
3. Open `dashboard/car_price_dashboard.pbix` in Power BI Desktop
4. Use slicers to filter by Brand, Model, Fuel Type, Engine CC, and Price range
5. Open 'sql/car_data_queries.ipynb' for sql queries on the data
