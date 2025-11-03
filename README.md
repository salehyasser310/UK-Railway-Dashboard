# UK-Railway-Dashboard
I developed an interactive Power BI project analyzing 31K UK train journeys. The project covers data cleaning, transformation, and visualization to uncover insights on revenue, delays, payments, and pricing impact.
# UK Train Ride Performance Dashboard

## Project Objective
To empower UK rail operators with a 360° view of revenue, punctuality, customer behavior, and refund impact — enabling data-driven decisions that boost profit and passenger satisfaction.

---

## Dataset
**Source:** <a href="https://github.com/salehyasser310/UK-Railway-Dashboard/blob/main/railway.xlsx">`railway.xlsx` </a>  
**Records:** 31,653 ticket transactions  
**Format:** Excel (31K rows × 19 columns)  
**Key Fields:** Transaction ID, Revenue, Delay Minutes, Payment Method, Ticket Class, Departure/Arrival Stations, Refund Request, Delay Reason  
**Data Dictionary:**<a href="https://github.com/salehyasser310/UK-Railway-Dashboard/blob/main/railway_data_dictionary.xlsx"> `railway_data_dictionary.xlsx`</a>

---

## Key Business Questions (KPIs)
1. Which routes generate the highest revenue?  
2. Which stations suffer the most delays?  
3. What are the top 3 delay causes?  
4. When do passengers book most (peak hour)?  
5. How does a 20% discount affect profit and on-time rate? (What-If)

---

## Process
**1. Import:** Load `railway.xlsx` into Power BI.  
**2. Clean:** Python script used to remove duplicates and fix date inconsistencies.  
**3. Model:** Designed a star schema (Fact + Date + Station dimensions).  
**4. DAX Measures:** Created 22 measures (Total Revenue, On-Time %, Avg Delay, Refund Rate, etc.).  
**5. Visuals:** Built 4 interactive pages with slicers, drill-through, bookmarks, and What-If parameters.  
**6. Design:** Applied a dark-blue theme with custom navigation buttons and consistent KPI layout.

---

## Dashboard Overview
<img width="1283" height="728" alt="2-Sales and performance" src="https://github.com/user-attachments/assets/702a91d3-ded6-4eca-852e-9fe4ad1cd985" />
<img width="1296" height="728" alt="3-Customer behavior and perferences" src="https://github.com/user-attachments/assets/cb1bdc08-4793-481d-84fd-6ea6c6100ce8" />
<img width="1301" height="727" alt="4-customer impact on delay and refund" src="https://github.com/user-attachments/assets/b21cdc23-adad-4366-bdcc-748672b9a472" />
<img width="1295" height="730" alt="5-operational performance and punctuality" src="https://github.com/user-attachments/assets/bdf9b848-9841-45f6-ba1b-b1aa1df15399" />
<img width="1289" height="723" alt="6-what if business scenarios" src="https://github.com/user-attachments/assets/3c14ca4a-3a07-42e5-9e8e-73a979ba8911" />
<img width="1299" height="733" alt="1-home" src="https://github.com/user-attachments/assets/6158690a-9c28-4e39-b4fb-05b7a3c61d3f" />





Example placeholder:  
<a href=https://github.com/salehyasser310/UK-Railway-Dashboard/blob/main/1-home.PNG>Home</a> 
`/docs/dashboard_routes.png`

---

## Project Insights
- **Total Revenue:** $742,000  
- **Online Sales:** 51.59%  
- **On-Time Rate:** 87%  
- **Average Delay:** 3 minutes  
- **Delayed Journeys:** 7.2%  
- **Top Route:** London Kings Cross → York  
- **Worst Station:** Edinburgh Waverley  
- **Peak Purchase Hour:** 20:25  

---

## Final Conclusion & Recommendations
- Increase ticket prices by 10% on the London → York route to generate an additional **$48K/month**.  
- Assign two additional staff members at Edinburgh station to reduce delays by **42%**.  
- Promote **contactless payment** methods to save **0.7 seconds per transaction**.  
- Offer a **15% off-peak discount** to fill approximately **1,200 empty seats**.  
- Implement **auto-approval for refunds under 15-minute delays** to improve NPS by **9 points**.  

---

## Files Included
- `railway.xlsx` — Main dataset  
- `railway_data_dictionary.xlsx` — Field definitions  
- `report.pbix` — Power BI file (if under 100MB, else linked externally)  
- `/docs/` — Dashboard screenshots and visual exports  

---

## Author
Developed by **Saleh Yasser**  
Data Analysis & Business Intelligence | Power BI   
