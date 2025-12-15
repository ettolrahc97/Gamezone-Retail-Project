# Gamezone Retail Project
## Project Background
Gamezone founded in 2018. Sell new and refurbished gaming products all around the world. They use online website, mobile app, and variety of marketing channels.

This project thoroughly analyzes and synthesizes the data to uncover critical insights such as the overall sales trends across a variety of different regions within the organization.

Insights and recommendations are provided on the following key areas:

- **Overall Sales Performance:** Analysis of total sales, identifying revenue growth trends and monthly fluctuations.
- **Seasonal Demand Patterns:** Assessment of monthly sales trends, highlighting strong performance with specific seasons.
- **Product Performance:** Evaluation of top and low performers with leading and underperforming sales.
- **Channel Performance & Marketing Effectiveness:** Analyzes sales contribution by marketing and purchase channels.
- **Regional Performance & Market Shifts:** Evaluates sales behavior across geographic regions.

The Excel File used to inspect and clean the data for this analysis can be found [here](gamezone-orders-data.xlsx).

## Data Structure & Initial Checks

The Gamezone database structure as below consist of two tables: order and region with a total row of 21,865 records. A description of each table is as follows:

- **order:** Stores individual customer orders, including who made the purchase, what was bought, when it was purchased and shipped, how and where the order was made.

- **region:** Stores a mapping between each country code and its assigned geographic region.![](order.png)
## Executive Summary 
## Overview Of Findings
Overall performance from 2019 to 2020 shows strong revenue growth driven by a surge in demand starting in early 2020, with clear signs of seasonality and concentration across products, channels, and regions.

Total revenue reached $6.15M, supported by an order volume of 21.68K and an Average Order Value (AOV) of $283.78, indicating that revenue growth was driven by both order activity and relatively high-value purchases.

Sales trends reveal a steady increase through 2019, followed by a significant acceleration in 2020, culminating in a peak during December 2020, which recorded the highest monthly sales at approximately $549K. This spike, along with stronger performance in fall and winter months, suggests a combination of seasonality, holiday demand, and potential promotional activity, amplified by broader market conditions during the COVID period. In contrast, February 2019 marked the lowest sales month, highlighting how much demand shifted over time.
Product performance is highly concentrated, with the 27-inch 4K gaming monitor emerging as the top revenue driver at nearly $2M, followed by the Nintendo Switch and Sony PlayStation 5 Bundle. Together, these top three products account for a substantial share of total revenue, indicating reliance on a small set of high-performing items.

Channel analysis shows that Direct traffic overwhelmingly dominates revenue, contributing 84.7% of total sales, while other channels such as email, affiliate, and social media play a much smaller role. This suggests strong brand-driven or repeat purchasing behavior but also highlights an opportunity to diversify and strengthen secondary marketing channels.

From a geographic perspective, North America (NA) is the primary revenue contributor at 52.1%, followed by EMEA (30.3%), with APAC (12.1%) and LATAM (5.5%) contributing smaller shares. This indicates a strong regional concentration in NA, with growth potential in underpenetrated regions.

Below is the overview page from the Tableau dashboard. The entire interactive dashboard can be downloaded [here](https://public.tableau.com/views/GameZoneRetailProject/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
![](https://github.com/ettolrahc97/Gamezone-Retail-Project/blob/6bb5356c070721add460892534c0b00191169239/Performance_Overview.png)
## Insights Deep Dive
**Product Performance:**
- The Top 3 products (27in 4K Gaming Monitor, Nintendo Switch, Sony PlayStation 5 Bundle) are clearly driving overall revenue and orders.
- AOV (Average Order Value) shows that Sony PlayStation 5 Bundle has the highest price per order, especially in December 2020, indicating it contributes disproportionately to total revenue.
- Order counts show that spikes in December 2020 across all top products drove the overall revenue peak.
- Overall, product-level performance explains why December 2020 was a peak: strong sales from high-value and popular products.
![](https://github.com/ettolrahc97/Gamezone-Retail-Project/blob/171f482e47bcbb7b1fdffec6f6e6e7331526d3a1/Product_Performance.png)


**Channel Performance & Marketing Effectiveness:**
- Direct channel dominates sales across all top products, especially during December 2020, making it the main driver of sales spikes.
Other channels (email, affiliate, social media) contribute minimally in comparison.
- Breakdown by product shows that Sony PlayStation 5 Bundle sales drop in early 2021 was mostly from a decline in direct channel, explaining part of the post-peak revenue decrease.
- Marketing effectiveness is heavily tied to direct channel campaigns, signaling a potential area to optimize or diversify.
![](https://github.com/ettolrahc97/Gamezone-Retail-Project/blob/171f482e47bcbb7b1fdffec6f6e6e7331526d3a1/Channel_Performance.png)

**Regional Performance & Market Shifts:**
- All regions show similar seasonal trends, confirming a macro/global impact, likely related to COVID-19 demand changes.
NA region leads in revenue, particularly for high-value products, but also shows a sharp dip in early 2021, mostly driven by direct channel sales.
- Other regions (EMEA, APAC, LATAM) follow the same pattern, indicating the revenue spike and dip was not localized, but a global trend.
Regional insights highlight market shifts and can guide decisions for regional promotions, inventory planning, and marketing focus.
![](https://github.com/ettolrahc97/Gamezone-Retail-Project/blob/171f482e47bcbb7b1fdffec6f6e6e7331526d3a1/Regional_Performance.png)


## Recommendations
Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following:


