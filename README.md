# E-commerce Sales Analysis & Forecast

## Table of Contents

-  [Project Overview](#project-overview)
-  [Data Source](#data-source)
-  [Tools](#tools)
-  [Data Cleaning](#data-cleaning)
-  [Exploratory Data analysis](#exploratory-data-analysis)
-  [Data Analysis](#data-analysis)
-  [Dashboard](#dashboard)
-  [Insights](#insights)
-  [Recommendations](#recommendations)
-  [Projections](#projections)
-  [Sales Forecast](#sales-forecast)
-  [Limitations](#limitations)
-  [Conclusion](#conclusion)
-  [Forecast vs Outcome **(UPDATE)**](#forecast-vs-outcome)


----------------
### Project Overview

This Data Analysis Project covers the performance of an E-commerce business in Nigeria in the 2nd & 3rd quarters of the year 2021. By analysing various aspects of the sales data, we seek to identify trends, gain a deeper understanding of the company's performance, make data-driven recommendations towards increasing revenue & overall performance and make forecasts for the final quarter of the year.

----------------
### Data Source
The Dataset used for this analysis is the "**Blutech Sales Records Apr-Sep_2021.xlsx**" file    
[Download spreadsheet here](https://github.com/user-attachments/files/18268722/Blutech.Sales.Records.Apr-Sep_2021.xlsx)

----------------
### Tools
The tool used for this analysis was Microsoft Excel
  - [Download MS Excel](https://microsoft.com)

----------------
### Data Cleaning
In the preparation of the dataset for analysis, we performed the following tasks:
1. Removal of Duplicates
2. Handling of missing values with LOOKUP functions
3. Data Cleaning & Formatting

----------------
### Exploratory Data Analysis
The dataset was explored to answer key questions such as:

1. What is the monthly sales trend at the organisation?
2. How much sales were made by each payment type and what was their percentage contribution to total revenue?
3. What was the sales trend of payment types per month?
3. How was the performance of the service providers in terms of sales and number of purchases?
4. What is the forecast for the final quarter of the year? Is performance expected to climb or drop? Are there factors such as locality seasonal trend which are expected to affect sales?
5. Are there opportunities for growth in any payment category?
6. Should a customer loyalty program be initiated, are there customers with a record of repeated purchases?
7. What are the limitations to the analysis of this data?


----------------
### Data Analysis
In the analysis of the data, Descriptive Statistics was carried out on the transaction amounts. Furthermore, Pivot Tables were adopted in summarising the data.

#### SUMMARY STATISTICS
**MEASURE** | **VALUE**
--------|-------
Mean | **₦9,207**
Median | **₦4,615**
Mode | **₦1,000**
Range | **₦567,344**
Minimum | **₦7**
Maximum | **₦567,351**
Sum | **₦28,798,516**
Count | **3,128**

#### PIVOT TABLE

![pivot table sample](https://github.com/user-attachments/assets/4e628a7a-c48e-4837-8d19-2af09e46fcb6)


---------------
### Dashboard

![Blutech Dashboard](https://github.com/user-attachments/assets/e356b1d2-7bb4-4af4-a0ed-bee98335e955)

---------------

### Insights

1. **TOTAL REVENUE**: In general, revenue and order volume saw a generally positive trend, with fluctuations in specific months.

2. **MONTHLY SALES TREND**: **May** and **September** experienced the highest sales while the lowest sales were made in **July**.
The fluctuations in monthly sales performance were possibly due to seasonal factors. **Betting** which accounted for **39%** of sales in **May** & **Airline (31%)** in **September** were the major contributors to revenue in the peak performing months. A key reason for peak sales in **May** brought about by **Betting** was the round-up of major European football leagues, while **Airline** sales experienced a rise in **September** largely due to the relaxation of the COVID-19 Pandemic travel rules in Nigeria.
On the other hand, the sales dip in **July** could possibly be due to the post-holiday slowdown, which is typical in many businesses during mid-year periods.

3. **PAYMENT TYPE PERFORMANCE**: **Betting (23% of total sales)** & **Cable TV (22%)** were the top performing payment types while **Airline (17%)** generated the lowest sales largely due to the pandemic travel restrictions and the lack of options for customers, as **ARIK Air** which is the only airline ticket purchase service provided by the business is not recognised as the first choice carrier for most Nigerians.
**Utility Bills (19%)** and **Internet Providers (18%)** showed steady sales but lower growth compared to **Betting** and **Cable TV**, with **Internet Providers** having a slightly weaker performance in the later months (especially June and July).

4. **SERVICE PROVIDER PERFORMANCE**: **MERRYBET (Betting)** with **23%** of total sales dominated the revenue with a strong share of sales, reflecting a consistent demand for betting services.
**DSTV (Cable TV)** with **22%** of total sales was the second-best performing service provider, reflecting Nigeria's continued demand for cable TV services, especially during sporting seasons.
**ARIK (Airline)** with **17%** of total sales performed relatively well, possibly benefiting from increased travel demand post-pandemic.
**Utility providers (IKEDC, EKEDC, EEDC, IBEDC, BEDC)** performed poorly, with **BEDC** showing particularly low sales. This could be largely due to the low population density and a lack of awareness in some rural areas covered by the distribution company on modern payment methods of electricity bills, as well as limited customer engagement by the business.

----------

### Recommendations
1. **Focus on High-Performing Categories**: Prioritize marketing and customer engagement efforts in the **Betting** and **Cable TV** sectors. Consider special promotions or collaborations during high-demand periods, such as sporting events and holidays.

2. **Increase Engagement with Underperforming Service Providers**:  For **BEDC** and **IBEDC**, consider improving customer service for a more seamless experience. Engaging with local communities and leveraging social media could boost brand loyalty and sales.

3. **Diversification**: Availing additional service providers in the **Betting**, **Airline** & **Cable TV** categories provides more options for customers and prospective customers and expands opportunities for  growth, especially as the current providers in  the **Betting** & **Airline** categories (**MERRYBET** & **ARIK Air**) are not the most popular in their industry among Nigerians. More popular options in the **Betting** industry include **SportyBet**, **Bet9ja**, & **1XBet**, while the top-choice **Airline** amongst Nigerians is **AIR PEACE**.

---------

### Projections
1. **General Sales Outlook**:
**Q4 2021 (October - December)** is likely to experience a rise in demand, particularly for **Betting**, **Cable TV**, and **Airline**, due to the holiday season and end-of-year promotions. Historically, E-commerce businesses in Nigeria experience an uptick in sales during festive seasons, and betting interest tends to rise with popular sporting events.

2. **Potential Challenges**:
**Utility Providers** might continue to face challenges unless there are structural improvements or enhanced customer awareness plans.
**Internet Providers** might face stiff competition and could experience slower growth without differentiation strategies such as exclusive content, cheaper subscription plans or faster speeds.

3. **Growth in the Airline Industry**:
**ARIK Air** and the general **Airline** industry could see a recovery as travel demand is expected to sky-rocket post-pandemic.

---------

### Sales Forecast
In forecasting sales for the final quarter of the year, the Excel forecast tool was used in deriving the preliminary values for the forecast and the following was the result:

![default blutech forecast](https://github.com/user-attachments/assets/5f84a644-db4f-4859-b633-7e4bf0700fab)

#### Final Sales Forecast
The Upper Confidence Bound Sales Forecast was adopted due to the upward sales trend experienced by most E-commerce firms in Nigeria, in the final quarter of the year. 
The business is expected to add at least another betting company, airline & cable TV provider to the service provider roll if recommendations are adhered to. However, sales are not expected to experience enormous growth in **October** because of the period of awareness for customers on the addition of new service providers, although sales are still expected to climb slightly. 
The business is expected to experience massive sales in **November** and peak sales in **December**. Therefore, the analysis further adopts a multiplier of 75%, 100% & 125% for the respective months, on the default Upper Confidence Bound Sales Forecast which does not take into recognition, the projected additional service providers.

![final blutech forecast](https://github.com/user-attachments/assets/d21951f8-224b-45c0-943b-c88cb5b48356)


------------

### Limitations
The dataset covers only the 2nd & 3rd quarters of a single calendar year, thereby, making it nearly impossible to monitor past seasonal trends, especially year-end sales patterns. This limitation is likely to affect the accuracy of forecasts. 

-------------
### Conclusion
The E-commerce business showed strong performance in certain payment categories like **Betting** & **Cable TV**, driven by seasonal events and consumer demand. However, most of the payment types exhibited room for growth. By strategically improving customer engagement, offering promotions, and expanding customer options with the inclusion of more popular or preferred service providers, the business can sustain growth and perform better in the coming months, particularly during the festive period.

-----------
## UPDATE (End of year 2021)


![forecast blutech](https://github.com/user-attachments/assets/72534381-5091-4891-b9f6-73e3e56e09f2)

### Forecast vs Outcome

Comparing the sales forecast to the final outcome, the forecast exhibited a high degree of accuracy.
The forecast for the months of October and November witnessed an accurancy of 95% & 92% respectively, while an 87% accuracy was exhibited by the December forecast.
However, in general terms, the forecast is deemed to be accurate as the business experiences a slight revenue increase in October and achieves peak sales for the year 2021 in December, just as was forecasted.






