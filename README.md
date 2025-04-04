# Biomedical-Analytics-Project
1. Maternal Death Rate Analysis (2023)
Objective: Compare maternal death rates by registered live births between the eastern and western chiefdoms of Sierra Leone. Identify the chiefdom with the highest maternal death rate and its surrounding chiefdoms with lower rates.

Findings:

Highest Maternal Death Rate: Tainkatopa Makama Safrokoh (Western Chiefdom) with a rate of 2469.14 per 100,000 live births.

Surrounding chiefdoms with lower rates include Bureh Kasseh Maconteh (255.54), Maforki (496.28), Buya Romende (198.41), Dibia (193.05), and Marampa (247.93).

Visualization: Column graph comparing maternal death rates across chiefdoms.

2. Prediction of Maternal Death Rates (January 2025)
Objective: Use 3-month and 5-month moving averages to predict maternal death rates for January 2025 in Tainkatopa Makama Safrokoh.

Methodology:

Missing values were imputed using linear interpolation.

Moving averages were calculated, and models were evaluated using MAE and RMSE.

Results:

Predicted values:

3-Month Moving Average: 4316.347

5-Month Moving Average: 3856.864

The 3-month moving average model performed better based on lower MAE and RMSE values.

3. BCG Coverage for Children Under 1 Year
Objective: Analyze BCG vaccination coverage trends over the last 18 months for health centers near Freetown’s beaches.

Findings:

Coverage decreased from 2023 to 2024, with significant drops at Wilberforce CHC, Kissy Health Centre, and Rokupa Govt. Hospital.

Data quality improved in 2024 due to better categorization of coverage levels.

Visualization:

Two maps were created to compare coverage in April–December 2023 vs. January–September 2024.

Correlation Analysis:

Strong positive correlations were observed between health centers, indicating consistent vaccination trends across facilities.

4. Trends in Reporting Rates for EPI Stock and HIV Pediatric Data
Objective: Analyze monthly reporting rates for EPI Stock and HIV Pediatric datasets across Sierra Leone districts.

Findings:

EPI Stock Reporting Rates:

Increased steadily in early 2023, peaking at 100% mid-year before declining slightly in late 2023.

Seasonal patterns observed with higher reporting mid-year.

HIV Pediatric Reporting Rates:

Showed a similar upward trend, peaking at ~100% mid-year but declining toward year-end.

Time Series Modeling:

SARIMA outperformed Holt-Winters models for both datasets based on RMSE, MAE, and MAPE metrics.

5. Facility Infrastructure Comparison
Objective: Compare access to stable electricity, running water, and internet connectivity across chiefdoms in Bo District and Western Area Districts for the year 2023.

Findings:

Freetown had the highest infrastructure access levels across all three indicators.

Regions like Badjia, Selenga, Wonde, and Bargbo had minimal or no access to these facilities.

Visualization:

Area charts and thematic maps were used to illustrate disparities in infrastructure access.

6. Malaria Prediction Using ANOVA
Objective: Test whether malaria occurrence is predictable based on other vector-borne diseases (e.g., yellow fever, schistosomiasis).

Methodology:

Data was prepared using DHIS2 with missing values handled via interpolation.

ANOVA was conducted to test the hypothesis that malaria occurrence is influenced by other diseases.

Findings:

Statistically significant relationships were found between malaria cases and other vector-borne diseases.

7. Time Series Analysis for EPI Stock Reporting Rates and HIV Pediatric Data
Objective: Decompose time series data into trend, seasonality, cyclicity, and noise components.

Findings:

Both datasets exhibited strong upward trends with seasonal peaks mid-year and declines toward year-end.

Model Evaluation:

SARIMA models outperformed Holt-Winters models for forecasting due to better handling of seasonality.

8. Facility Infrastructure Comparison Between Bo District and Western Area Districts
Objective: Compare access to three key infrastructure indicators—stable electricity, running water, and internet connectivity—across chiefdoms in Bo District and Western Area Districts for 2023.

Findings:

Freetown: The most developed region with the highest access to all three indicators:

Internet connectivity: 28 facilities

Running water: 18 facilities

Stable electricity: 21 facilities

Moderate Access Regions:

Kakua showed significant internet connectivity (19 facilities) but limited access to running water and electricity.

Rural Western Area exhibited moderate access across all three indicators.

Limited Access Regions:

Chiefdoms like Badjia, Selenga, Wonde, and Bargbo had minimal or no access to these facilities.

Visualization:

An area chart was used to display infrastructure access across regions.

Thematic maps were created for each indicator to highlight regional disparities.

Alternative Visualization Suggestions:

Horizontal stacked bar charts were proposed for a clearer comparison of facility access levels.

9. Malaria Prediction Using ANOVA
Objective: Test whether malaria cases can be predicted based on the occurrence of other vector-borne diseases such as schistosomiasis, yellow fever, and onchocerciasis.

Methodology:

Data Preparation:

Monthly data for new cases of malaria and other vector-borne diseases in 2023 and 2024 was collected by district.

Missing values were handled through interpolation.

Hypothesis Testing:

ANOVA was conducted to test the relationship between malaria cases (dependent variable) and other diseases (independent variables).

Findings:

Statistically significant relationships were identified between malaria cases and other diseases, suggesting that malaria occurrence is influenced by trends in other vector-borne diseases.
