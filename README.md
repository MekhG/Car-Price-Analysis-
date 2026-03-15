# Car Price Analysis

## Introduction / Description
This project provides a comprehensive exploration of the Indian car market from 2015 to 2024, covering 10 major brands and multiple models. It investigates the interplay between price, fuel efficiency, engine capacity, transmission, and service costs, aiming to identify cars that offer the best value for buyers. Using a combination of Excel, SQL, and Power BI, the project uncovers pricing trends, mileage patterns, and brand-level insights to inform consumer decisions, fleet management strategies, and market positioning for manufacturers.

## Objective
- Explore pricing trends across major Indian car brands.  
- Identify most affordable cars, best mileage options, and lowest service cost brands.  
- Analyze the impact of fuel type, engine capacity, and transmission on price and mileage.  
- Provide actionable insights for buyers, manufacturers, and market analysts.  

## Dataset Preview
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

## Tools and Methods Used
- **Excel:** Data cleaning, exploratory data analysis, pivot tables, bubble charts, brand and fuel type comparisons.  
- **Power BI:** Two-page interactive dashboard with KPI cards, scatter plots, and slicers; light and dark themes for presentation.  
- **SQL (SQLite via Python/Kaggle):** Data cleaning, brand/fuel type/mileage analysis, price aggregation, and queries for reporting.  

## Analysis Steps
1. Loaded dataset and performed EDA in Excel.  
2. Identified most affordable, highest priced, and best mileage cars.  
3. Built brand-wise average price and service cost comparisons.  
4. Created bubble charts correlating Price vs Mileage by Engine CC and Brand.  
5. Analyzed fuel type mileage distribution.  
6. Built interactive Power BI dashboard with brand, model, fuel type, and price slicers.  
7. Ran SQL queries in Kaggle for deeper analysis.  
8. Designed second dark-theme page for portfolio presentation.  

## Key Findings
| Metric | Value |
|---|---|
| Most Affordable Car | Mahindra XUV 700 (Electric, Automatic) |
| Highest Avg Price Brand | Mahindra |
| Best Mileage Fuel Type | CNG |
| Lowest Service Cost Brand | Honda |
| High Mileage, Low Cost Car | Kia EV6 (₹18,800) |

**Price Insights:**  
- Mahindra leads in average price, followed by Tata Motors and Kia.  
- Maruti Suzuki remains the most budget-friendly brand.  

**Mileage Insights:**  
- CNG vehicles deliver the highest mileage (~50+ km/kg).  
- Electric cars show strong mileage equivalence but high upfront cost.  
- Diesel vehicles offer better mileage than Petrol but higher service costs.  

**Service Cost Insights:**  
- Honda has the lowest average service cost.  
- Renault and Maruti Suzuki rank low in service costs.  
- Higher engine CC correlates with higher service cost.  

## Business Insights and Recommendations

**For Individual Buyers:**  
- **Budget-conscious buyers:** Opt for brands like **Maruti Suzuki** or low engine CC CNG models to minimize upfront costs and maximize fuel efficiency.  
- **High-performance buyers:** Consider **Mahindra** or **Kia** for premium features and higher resale value, but be mindful of higher service costs.  
- **Fuel efficiency seekers:** Prioritize **CNG vehicles** for cost-effective mileage or **Electric vehicles** for long-term savings despite higher upfront costs.  

**For Fleet Operators / Corporate Buyers:**  
- **Cost optimization:** Choose **CNG or low-engine CC vehicles** to reduce running costs and minimize fuel expenditures.  
- **Long-term value:** Electric vehicles can offer significant savings on fuel and maintenance over their lifecycle despite higher purchase price.  
- **Maintenance planning:** Favor brands like **Honda** with lower service costs to reduce fleet maintenance budgets.  

**For Manufacturers / Market Analysts:**  
- **Product positioning:** Brands can differentiate by emphasizing either affordability (Maruti, Tata) or premium features (Mahindra, Kia).  
- **Service strategy:** Focus on lowering service costs or offering service packages to increase customer satisfaction and retention.  
- **Fuel type trends:** Growing interest in CNG and Electric vehicles suggests opportunities for expanding EV/CNG lineups and targeting urban buyers.  
- **Pricing strategy:** Monitor high-demand premium vehicles with high mileage efficiency (e.g., Kia EV6) to optimize price positioning without losing market share.  

**Actionable Dashboard Insights:**  
- Use slicers to dynamically explore brand, model, fuel type, and price combinations to identify value-for-money vehicles.  
- Track trends over 2015–2024 to anticipate shifts in affordability, fuel type popularity, and service cost optimization.

## Dashboard Preview
![Dashboard Preview](https://github.com/user-attachments/assets/109fadf6-caaa-4726-b629-31446db18664)  
![Dashboard Preview](https://github.com/user-attachments/assets/1d1b79ff-6ebb-4004-a670-2008617413b9)  

## How to Run
1. Clone the repository:  
   ```bash
   git clone <repo-url>

2. Open Excel analysis: car_price_analysis.xlsx

3. Open Power BI dashboard: car_price_dashboard.pbix

4. Use slicers to filter by Brand, Model, Fuel Type, Engine CC, and Price range.

5. Run SQL queries: car_data_queries.ipynb
