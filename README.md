# TATA Online Sales Analysis
This is Online Sales Analysis project for TATA group
## Introduction
The Tata Group and Quants, a leading online retail store, are currently experiencing robust performance across multiple regions and stores. They have engaged our team to deliver strategic insights for their leadership. The management is keen to dive deeper into the factors driving this success, with the objective of leveraging these insights for informed planning in the upcoming year, focusing on both operational efficiency and marketing effectiveness.

In addition to identifying the key drivers behind their current performance, they are particularly interested in exploring demographic trends to gain a deeper understanding of their customer base. The goal is to highlight what's working well while uncovering untapped growth opportunities. Our analysis will play a pivotal role in guiding the company’s expansion strategy, equipping leadership with data-driven insights to make well-informed decisions for future growth.

## Problem Statement
- Monthly Revenue : Identify peak months and reasons behind any trends.
- Product Demand by Region: Identify revenue, profit  with high demand for potential business expansion.
- Top Countries : Rank by revenue, compare with quantity sold, focus on high-revenue and high-quantity sold in each country.
- Top Customers: Rank by revenue, visualize in descending order, targeted for retention.

## Extraction, Transformation and Loading of Data
The datasets were extracted from an Excel file, and the following transformations were performed using the Power Query Editor:
Cleaning the data given in an Excel spreadsheet to ensure good quality data is retrieved by removing the null and empty spaces within data rows.
## Skills/concepts demonstrated:
The following Power Bi features were incorporated
-  Bookmarking and Filtering
-  DAX and Quick measures
-  Page Navigation
## The Logic
- A monthly target was fixed at 10% increase of the previous month for Order, Revenue and Profit
- A KPI visual is used to measure performance of the current month to the previous month
- Numeric Range and Field parameters were created for scenario analysis to examine impact on a given output like impact on REVENUE/PROFIT when the price of product is adjusted by a certain percentage
## Visualization
The report comprises of five(5) pages:
- Executive Brief
- Global Map
- Product's details
- Country's details
- Customer's details

You can interact with the report [here](https://app.powerbi.com/view?r=eyJrIjoiYTcyMjgyYWQtYjA0Mi00Y2EwLTlkN2EtYjUyY2Q1YjAzMDdiIiwidCI6ImYzMzNmMDE4LWE3OTYtNGQ5Yy1iNmM4LThmY2RmYzAyNzEwYiJ9)

### Executive Brief
The visuals provide a comprehensive overview of key business performance indicators, focusing on both monthly trends and product-level insights. They illustrate the monthly revenue trend, showing how income has fluctuated over time. Additionally, the dashboard highlights total orders, total revenue, and total profit, offering a clear snapshot of overall business performance.

One of the visualizations focuses on the top 100 products, ranked by the revenue generated. This helps identify which products are driving the most income, offering valuable insight for decision-making regarding inventory management, marketing strategies, and sales focus.

Furthermore, the visuals compare current month performance to the previous month across three critical metrics: revenue, orders, and profit. This comparison allows for quick identification of growth or decline, enabling swift responses to emerging trends, whether positive or negative.

This data-driven approach helps stakeholders monitor key performance areas, assess the impact of strategic changes, and optimize resource allocation for sustained growth.

![](Executive_overview.png)

### Global Map
This visual highlights the global reach of TATA Company, showcasing the different countries that patronize its products or services. The bubble chart effectively represents each country's level of engagement, where the size of each bubble corresponds to the volume of patronage or sales from that country.

Larger bubbles signify countries with higher volumes of business, indicating major markets for TATA, while smaller bubbles highlight regions with lower levels of engagement. This visual offers a clear and immediate understanding of the company’s global market distribution, helping to identify key markets where TATA enjoys significant patronage, as well as potential growth opportunities in less-engaged regions.

This insight is invaluable for strategic planning, allowing the company to optimize market efforts, allocate resources efficiently, and potentially explore areas for expansion.

![](global_view.png)

### Product's details
This visual provides a detailed performance overview of a specific product, offering a deep dive into its key metrics. By using the drillthrough feature from the Executive Brief, users can seamlessly transition to this detailed product view, where they can evaluate the performance of the selected product across multiple dimensions.

The visual compares the product’s current month performance to a predefined target—set at a 10% increase over the previous month for revenue, orders, and profit. This allows users to quickly assess whether the product is on track to meet growth objectives, helping them understand the effectiveness of pricing strategies, promotional efforts, or market demand.

Additionally, the visual presents a monthly breakdown of the product's revenue, orders, and profit, offering a granular look at how the product has performed over time. This helps identify seasonal patterns, sudden spikes, or declines in performance, providing valuable insights for future planning.

Furthermore, the visual includes a monthly profit trend that specifically tracks the impact of price adjustments on the product's profitability. This feature enables decision-makers to understand how changes in pricing strategy affect both margins and overall performance, giving them the tools to fine-tune pricing and maximize profit.

Overall, this visualization provides a powerful, data-driven perspective, allowing stakeholders to make informed decisions about product performance and strategies for growth

![](product_view.png)

### Country's details
This visual offers a detailed breakdown of the performance of each country in terms of revenue, orders, and patronage, providing a country-specific view of business activity. By showcasing the performance across various countries, stakeholders can identify key markets, emerging regions, and areas of opportunity or concern.

The visual also highlights the months with the highest and lowest patronage, allowing for the identification of peak seasons, off-peak periods, and potential seasonal trends that influence customer behavior in different regions. This insight is crucial for planning marketing campaigns, optimizing inventory, and aligning supply chains with demand fluctuations across countries.

Additionally, the visual incorporates a period trend that tracks revenue performance over time based on the selected criteria in the matrix. This trend analysis allows users to visualize how revenue has evolved over the chosen period, whether it’s month-over-month, quarter-over-quarter, or year-over-year. By adjusting the selection matrix, stakeholders can customize the view to focus on specific timeframes, helping them assess the impact of strategic initiatives, external factors, or market changes.

Together, these visuals provide a powerful, interactive way to monitor geographical performance trends, helping decision-makers tailor their strategies to maximize revenue, improve customer engagement, and drive growth in specific countries and regions

![](country_view.png)
### Customer's details
This visual provides a comprehensive look at the performance of the top 50 customers, represented by their unique Customer IDs. By focusing on this key group, the visual offers insights into the purchasing behavior of the company's most valuable customers, enabling targeted analysis of how these top clients contribute to overall revenue.

The visual highlights the months with the highest and lowest patronage, allowing users to quickly identify when each of these customers is most active and when engagement drops. This can be particularly useful for spotting seasonal trends, understanding customer purchasing cycles, and identifying opportunities to boost engagement during low-activity periods.

Additionally, the visual presents a revenue period trend, which dynamically adjusts based on the selection matrix. This trend line tracks how revenue from the top 50 customers evolves over a chosen period—whether it's month-to-month, quarter-to-quarter, or year-over-year. By allowing users to filter and analyze specific timeframes, the visual helps assess the impact of sales campaigns, product launches, or other initiatives on customer purchasing behavior.

This analysis provides valuable insights into customer loyalty, purchasing patterns, and revenue contribution, offering a data-driven foundation for customer retention strategies, personalized marketing efforts, and growth initiatives aimed at the company’s most critical clients

![](customer_view.png)
