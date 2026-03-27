WALMART SLAES ANALYSIS

Objective
  Analyze weekly sales data to identify key factors influencing revenue.

Dataset 
- 6436 rows
- Variables: Store, Date, Weekly Sales, Holiday Flag, Temperature, Fuel Price, CPI, Unemployment

Tools Used
- Google Sheets
- Pivot tables

Analysis

seasonality
Sales show strong seasonal patterns with peaks in December and lows in January. 
<img width="600" height="371" alt="SUM of Weekly_Sales vs  year_month" src="https://github.com/user-attachments/assets/086e84d6-f43f-4bbc-adcb-46eeb00271c9" />


Holiday Impact
Holiday weeks have higher average sales compared to non-holiday weeks.
<img width="600" height="371" alt="AVERAGE of Weekly_Sales vs  Holiday_Flag" src="https://github.com/user-attachments/assets/b12a1fc4-f976-401e-96d7-8e4b65756428" />


Store Analysis
Sales vary significantly across stores, indicating location-based performace differences.
<img width="600" height="371" alt="SUM of Weekly_Sales vs  Store" src="https://github.com/user-attachments/assets/6f0e0fd9-ecca-4a6f-8180-b064a63827d9" />


External Factors
1. Temperature - No clear relationship
2. Fuel Price - No clear relationship
3. CPI - Time-driven, no direct impact
4. Unemployment - Slight negative effect on peak sales.

Key Insights 
1. Seasonality is the strongest driver of sales
2. Holidays significantly increase demand
3. Store differences affect baseline sales
4. Economic factors have limited short-term impact

Recommendations
1. Increase inventory before peak seasons
2. Focus marketing during holidays
3. Priortize high-performing stores
