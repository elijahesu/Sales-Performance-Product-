Welcome to the sample GitHub ReadME! Use this template as an outline for your data analytics projects. Include one ReadME per repository, with each repository storing one project. Remember, it's better to have quality over quantity - having 2 stellar business-relevant projects stands out much more than 3+ mediocre projects. Feel free to make a copy of this or fork this repository and make it your own. Happy portfolio-ing :) 




# Project Background

GameZone operates in gaming/consumer-electronics e-commerce. The catalog in the data includes consoles, monitors, headsets, gaming mice, and gaming laptops — e.g. Nintendo Switch, Sony PlayStation 5 Bundle, 27in 4K gaming monitor, JBL Quantum 100 Gaming Headset, Dell Gaming Mouse, Lenovo IdeaPad Gaming 3, Acer Nitro V Gaming Laptop, and Razer Pro Gaming Headset.

* **Active years in this dataset:.**
Purchase activity runs from roughly January 2019 through December 2020, with PURCHASE_MONTH giving a monthly grain. Some SHIP_TS values are earlier than purchase dates, and REFUND_TS values extend later — up to 2025 — so the dataset captures the sales window 2019–2020 plus a longer operational/refund tail. It does not show purchases after 2020.

* **Business model:.**
GameZone is a direct-to-consumer online retailer. Orders come through website and mobile app. Sales are in USD, shipped internationally to many COUNTRY_CODE values such as US, DE, AU, FR, GB, IN, BR, etc. Marketing/acquisition is tracked through channels like direct, affiliate, email, social media, and account creation methods include desktop, mobile, tablet, tv, unknown. Refunds are tracked via REFUNDED and REFUND_TS.

What the data suggests operationally:
* Website is the dominant purchase platform; mobile app is a smaller but real channel.
* Direct marketing is the most common channel, followed by email/affiliate/social.
* The US is the largest market, with strong international presence.
* Product mix spans low-ticket accessories like JBL headsets around $24 and Dell mice around $50, mid-ticket monitors around $300–$500, and high-ticket consoles/laptops from roughly $800 to $2,200+.
* Refunds are material enough to be a first-class metric, not an edge case.


| Metric | What it tells us |
|---|---|
| **Revenue** | Total sales before refunds |
| **Net Revenue** | Sales after refunds are subtracted |
| **Orders** | How many purchases were made |
| **Average Order Value** | How much customers spend per order |
| **Refund Rate** | How often orders are refunded |
| **Top Products** | Which items sell best |
| **Top Regions** | Where our customers are located |
| **Top Marketing Channels** | Which channels bring in the most sales |
| **Sales Trend** | How revenue and orders change over time |

Backround about the company, including the industry, active years, business model, and key business metrics. Explain this from the POV of a data analyst who is working at the company.

Insights and recommendations are provided on the following key areas:

- **Products Performance:** 
- **Category 2:** 
- **Category 3:** 
- **Category 4:** 

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targed SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

The companies main database structure as seen below consists of four tables: table1, table2, table3, table4, with a total row count of X records. A description of each table is as follows:
- **Table 2:**
- **Table 3:**
- **Table 4:**
- **Table 5:**

[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings

After peaking in late 2020, company sales continued to decline, with significant drops in 2021. Key performance indicators—total sales by product, average order value (AOV), and total orders—show that the main drivers were the Sony PlayStation 5, Nintendo Switch, and gaming monitors, with North America leading regional sales for most. The refund rate was 19.36%. Although this decline can be partly attributed to a return to pre-pandemic normalcy, the following sections will examine contributing factors and explain how these findings will inform our monthly product and regional stocking decisions.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### Sales Trends:

* The company’s sales more than doubled in early 2020, reaching an all-time high in September with 1,496 orders totaling $456,871 in monthly revenue, and again in December with 1,671 orders totaling $549,435 in monthly revenue. This corresponds with the economy-wide spending boom caused by pandemic-induced changes in consumer behavior.
  
* Sales dropped significantly in February 2021, almost nearing pre-COVID levels. The main drivers of this dip were the gaming monitor, Nintendo Switch, and Sony PlayStation 5—all three of which exhibit the same plateauing behavior in 2020 and 2021.


[Visualization specific to Sales Trend]


### Product (Regional and Marketing) Performance:

* Eighty-eight percent of the company’s orders come from just three products: the gaming monitor, Nintendo Switch, and JBL gaming headset. These three products accounted for $3.7M in overall revenue, or 60% of the company’s total.

* Direct is the main driver of sales; all other channels pale in comparison.

* While all three top products exhibited dips in 2021, the Sony PlayStation 5 had a major dip in direct traffic in 2021 compared with other products and marketing channels. Since then, that product has seen a consistent decline in direct-channel sales.

* For the Sony PS5, the drop is mostly contained to the NA region and direct traffic, which may indicate a shift in trends or competitors there.

[Visualization specific to Product (Regional and Marketing) Performance]






# Recommendations:

Based on the insights and findings above, we would recommend the [Sales and Marketing team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
