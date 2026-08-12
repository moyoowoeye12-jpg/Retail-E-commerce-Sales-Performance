# Retail-E-commerce-Sales-Performance
The retail and e-commerce sales analysis demonstrates a revenue base of $2,452,084.30 across 2,000 orders and 5,552 units during 2026. Performance is concentrated around the North and Central regions, the Computers category, Online sales and a small group of high-revenue products.


<img width="1592" height="873" alt="Screenshot (541)" src="https://github.com/user-attachments/assets/813a3b69-5776-4d90-bfa4-69e1fe06535e" />



𝐄𝐱𝐞𝐜𝐮𝐭𝐢𝐯𝐞 𝐒𝐮𝐦𝐦𝐚𝐫𝐲

 

This technical report documents the analysis of the supplied retail and e-commerce sales dataset and the resulting Sales Performance Dashboard. The transaction-level source contains 2,000 records covering the full 2026 calendar year. Total recorded revenue is $2,452,084.30, total quantity sold is 5,552 units, and average revenue per order is $1,226.04.

Revenue performance is led by the North region at $561,753.72, followed closely by Central at $556,705.18. At product-category level, Computers is the dominant category with $1,346,491.26, representing 54.9% of total revenue. Online is the leading sales channel at $791,536.99, while Returning customers generate $1,683,325.30.

Monthly revenue reaches its highest level in November at $274,368.31, while July records the lowest monthly revenue at $150,713.14. The final quarter contributes $650,608.89, equivalent to 26.5% of annual revenue. Among individual products, Gaming Laptop is the highest-revenue product at $432,576.06.

The dashboard is therefore technically effective as a descriptive management-reporting tool because it combines KPI cards, time-series analysis, regional comparison, product-category performance, sales-channel contribution and top-product ranking with interactive filters. The analysis also identifies areas for management attention, particularly product concentration, regional performance differences, channel mix, and the need to monitor discounting and customer retention.

 

𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐁𝐮𝐬𝐢𝐧𝐞𝐬𝐬 𝐂𝐨𝐧𝐭𝐞𝐱𝐭

The project converts transaction-level retail and e-commerce sales records into a structured analytical dashboard for performance monitoring and decision support. The supplied workbook separates the raw transactional dataset from supporting pivot calculations and the final dashboard presentation layer.

The dashboard is designed to answer practical business questions: how much revenue has been generated, how many orders were processed, how many units were sold, what the average order value is, how revenue changes over time, which regions and product categories perform best, which sales channels contribute most, and which individual products generate the highest revenue.

 

𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞𝐬


 

The technical analysis was structured around the following objectives:

Validate the transaction-level dataset before analytical aggregation.

Calculate total revenue, total orders, total quantity sold and average order value.

Analyse revenue by month to identify seasonality, peaks and troughs.

Measure revenue contribution by geographic region.

Evaluate product-category revenue performance.

Measure sales-channel contribution to total revenue.

Identify the top five products by revenue.

Assess customer-type contribution between new and returning customers.

Provide an interactive management reporting structure through dashboard filters.

Translate descriptive patterns into evidence-based business recommendations.

 

𝐃𝐚𝐭𝐚 𝐒𝐨𝐮𝐫𝐜𝐞 𝐚𝐧𝐝 𝐃𝐚𝐭𝐚𝐬𝐞𝐭 𝐒𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞


 

The primary source is the Sales_Data worksheet. It contains 12 fields covering order identification, transaction date, geography, sales channel, customer type, product classification, individual product, salesperson, quantity, unit price, discount and revenue.

The transaction population contains 2,000 records. Order IDs are populated across the dataset and the source contains 2,000 unique orders. The Date field spans 1 January 2026 through 31 December 2026, with 363 distinct dates represented.

The Dashboard_Plan worksheet defines the intended analytical requirements and maps each dashboard element to its source field. The Supporting_Pivots worksheet contains the KPI calculations and chart-supporting aggregations used by the dashboard.

The Sales_Dashboard worksheet provides the presentation layer. The supplied dashboard image shows filters for Region, Years, Quarters, Months, Days, Product Category, Sales Channel and Customer Type, enabling users to dynamically restrict the displayed analytical results.

 

𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐌𝐞𝐭𝐡𝐨𝐝𝐨𝐥𝐨𝐠𝐲



 

The project follows a descriptive analytics workflow:

Source inspection and field interpretation.

Data completeness and consistency checks.

Metric definition and KPI calculation.

Aggregation of revenue across time, geography, category, channel and product.

Ranking of dimensions by revenue contribution.

Trend analysis using monthly revenue.

Dashboard construction from supporting pivot-style calculations.

Cross-checking displayed KPI values against the transaction-level dataset.

Interpretation of findings and formulation of recommendations.

 

𝐊𝐏𝐈 𝐃𝐞𝐟𝐢𝐧𝐢𝐭𝐢𝐨𝐧𝐬




 

Total Revenue is the sum of the Revenue field: $2,452,084.30.

Total Orders is the count of unique Order IDs: 2,000.

Quantity Sold is the sum of Quantity: 5,552 units.

Average Order Value is calculated as total revenue divided by total orders: $1,226.04.

Revenue by Month is the aggregation of Revenue by calendar month derived from Date.

Revenue by Region is the aggregation of Revenue by Region.

Revenue by Product Category is the aggregation of Revenue by Product Category.

Revenue by Sales Channel is the aggregation of Revenue by Sales Channel.

Top 5 Products by Revenue is the descending ranking of Product based on total Revenue.

 

𝐃𝐚𝐭𝐚 𝐏𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐐𝐮𝐚𝐥𝐢𝐭𝐲 𝐀𝐬𝐬𝐞𝐬𝐬𝐦𝐞𝐧𝐭





 

𝐂𝐨𝐦𝐩𝐥𝐞𝐭𝐞𝐧𝐞𝐬𝐬




 

The supplied Sales_Data worksheet is complete across all 12 fields for the 2,000 records analysed. No missing values were detected in Order ID, Date, Region, Sales Channel, Customer Type, Product Category, Product, Salesperson, Quantity, Unit Price, Discount or Revenue.

 

𝐃𝐮𝐩𝐥𝐢𝐜𝐚𝐭𝐞 𝐎𝐫𝐝𝐞𝐫 𝐕𝐚𝐥𝐢𝐝𝐚𝐭𝐢𝐨𝐧

 

Order ID contains 0 duplicated values when checked at the transaction-record level. The source therefore supports the dashboard's use of Order ID as an order-counting field without evidence of duplicate order identifiers in the supplied dataset.

 

𝐍𝐮𝐦𝐞𝐫𝐢𝐜 𝐕𝐚𝐥𝐢𝐝𝐚𝐭𝐢𝐨𝐧

 

Quantity contains no non-positive values, Unit Price contains no negative values, and Discount contains no values outside the 0-to-1 range. A recalculation of revenue using Unit Price × Quantity × (1 − Discount) produced a maximum absolute difference of $0.0000000000 from the supplied Revenue field, which is effectively a rounding-level reconciliation.

 

𝐃𝐚𝐭𝐞 𝐕𝐚𝐥𝐢𝐝𝐚𝐭𝐢𝐨𝐧


 

The Date field is recognised as a valid date field and covers 01 January 2026 through 31 December 2026. This supports time grouping into years, quarters, months and days as implemented in the dashboard.

 

𝐃𝐚𝐬𝐡𝐛𝐨𝐚𝐫𝐝 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞 𝐚𝐧𝐝 𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐈𝐦𝐩𝐥𝐞𝐦𝐞𝐧𝐭𝐚𝐭𝐢𝐨𝐧



 

The dashboard uses a layered design. The top layer presents four management KPIs: Total Revenue, Total Orders, Quantity Sold and Average Order Value. The middle and lower analytical layers provide time, geographic, category, channel and product perspectives.

Interactive slicer/filter controls are positioned around the dashboard. Region and Product Category filters support geographic and portfolio analysis, while Sales Channel and Customer Type filters support commercial segmentation. Date controls for Years, Quarters, Months and Days provide temporal drill-down.

The supporting pivot architecture separates KPI calculations from chart-supporting aggregations. This approach improves maintainability because the dashboard visuals can be refreshed from a consistent analytical layer rather than requiring separate calculations inside each visual.

 

𝐃𝐞𝐭𝐚𝐢𝐥𝐞𝐝 𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐅𝐢𝐧𝐝𝐢𝐧𝐠𝐬



 
𝐎𝐯𝐞𝐫𝐚𝐥𝐥 𝐑𝐞𝐯𝐞𝐧𝐮𝐞 𝐚𝐧𝐝 𝐎𝐫𝐝𝐞𝐫 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞





The business generated $2,452,084.30 from 2,000 orders and sold 5,552 units during 2026. The resulting average order value is $1,226.04. These values reconcile with the KPI calculations in the Supporting_Pivots worksheet and the dashboard.

 

𝐌𝐨𝐧𝐭𝐡𝐥𝐲 𝐑𝐞𝐯𝐞𝐧𝐮𝐞 𝐓𝐫𝐞𝐧𝐝





 

Revenue shows substantial month-to-month movement. November is the strongest month at $274,368.31, followed by March at $236,738.70 and April at $241,034.34. The lowest month is July at $150,713.14, followed by May at $153,642.43.

The difference between the highest and lowest months is $123,655.17. The final quarter contributes 26.5% of annual revenue, with November representing the annual peak. This pattern indicates that sales planning should account for meaningful seasonal variation rather than assume a uniform monthly revenue profile.

 

𝐑𝐞𝐠𝐢𝐨𝐧𝐚𝐥 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞






 

North: $561,753.72, representing 22.9% of total revenue.

Central: $556,705.18, representing 22.7% of total revenue.

East: $467,808.85, representing 19.1% of total revenue.

South: $444,494.30, representing 18.1% of total revenue.

West: $421,322.25, representing 17.2% of total revenue.

North is the highest-performing region at $561,753.72, marginally ahead of Central at $556,705.18. East, South and West contribute progressively lower revenue. The relatively close performance of North and Central suggests that the business has two major geographic revenue centres, while the gap between the highest and lowest regions provides an opportunity for targeted regional improvement.

 

𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞







 

Computers: $1,346,491.26, representing 54.9% of total revenue.

Monitors: $526,744.59, representing 21.5% of total revenue.

Networking: $259,475.31, representing 10.6% of total revenue.

Storage: $229,837.63, representing 9.4% of total revenue.

Accessories: $72,895.26, representing 3.0% of total revenue.

Office Supplies: $16,640.26, representing 0.7% of total revenue.

Computers is the dominant category at $1,346,491.26, accounting for 54.9% of total revenue. Monitors is second at $526,744.59, while Networking and Storage contribute $259,475.31 and $229,837.63 respectively.

The three largest categories collectively generate $2,132,711.16, equivalent to 87.0% of annual revenue. This concentration means category strategy, inventory planning and promotional decisions should pay particular attention to the leading technology categories.

 

𝐒𝐚𝐥𝐞𝐬 𝐂𝐡𝐚𝐧𝐧𝐞𝐥 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞







 

Online: $791,536.99, representing 32.3% of total revenue.

Corporate Sales: $718,745.01, representing 29.3% of total revenue.

Retail Store: $631,399.37, representing 25.7% of total revenue.

Marketplace: $310,402.93, representing 12.7% of total revenue.

Online is the leading channel, followed by Corporate Sales and Retail Store. Marketplace is the smallest of the four channels. The channel distribution indicates that digital and direct commercial channels are central to revenue generation, while Marketplace remains a smaller but measurable contribution.

 

𝐓𝐨𝐩 𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞
 

Gaming Laptop: $432,576.06.

Laptop Air 13: $273,532.50.

Laptop Pro 14: $263,486.40.

All-in-One PC: $254,994.00.

Ultrawide Monitor: $190,959.45.

The top five products generate $1,415,548.41, representing 57.7% of total revenue. Gaming Laptop is the clear leading product, generating materially more revenue than the second-ranked Laptop Air 13. This indicates meaningful product-level concentration and suggests that availability and demand planning for high-value products should be closely monitored.

 

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫-𝐓𝐲𝐩𝐞 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞
 

Returning customers: $1,683,325.30, representing 68.6% of total revenue.

New customers: $768,759.00, representing 31.4% of total revenue.

Returning customers contribute substantially more revenue than new customers. This indicates that retention and repeat purchasing are important drivers of the observed sales base and should be incorporated into commercial planning.

 

𝐊𝐏𝐈 𝐚𝐧𝐝 𝐕𝐢𝐬𝐮𝐚𝐥 𝐈𝐧𝐭𝐞𝐫𝐩𝐫𝐞𝐭𝐚𝐭𝐢𝐨𝐧

 

The Total Revenue KPI communicates the overall financial scale of the analysed sales population. The Total Orders KPI measures transaction volume, while Quantity Sold measures physical unit movement. Average Order Value provides a complementary measure of revenue generated per order and helps distinguish changes in revenue caused by order volume from changes caused by order size.

The Revenue by Month visual is appropriate for identifying seasonality and short-term changes. The Revenue by Region visual provides direct comparison across the five geographic regions. The Product Category chart exposes portfolio concentration, while the Sales Channel chart shows the contribution of each route to market. The Top 5 Products visual is particularly useful for identifying high-value products requiring commercial and inventory attention.

The dashboard's filters add an interactive analytical layer. For example, users can isolate a region, category or sales channel and then observe how the selected segment changes the KPI and chart outputs. This supports drill-down analysis, but filtered values should always be interpreted as subset results rather than company-wide totals.

 

𝐊𝐞𝐲 𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐎𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧𝐬


 

Total revenue is $2,452,084.30 across 2,000 orders.

Average order value is $1,226.04, while 5,552 units were sold.

North is the highest-revenue region at $561,753.72.

Computers is the largest product category and contributes 54.9% of revenue.

Online is the leading sales channel with $791,536.99.

Gaming Laptop is the highest-revenue individual product at $432,576.06.

November is the strongest month at $274,368.31; July is the weakest at $150,713.14.

Returning customers generate 68.6% of revenue, materially exceeding the contribution from new customers.

The source data is complete for all required fields and passes the principal numeric and date validation checks.

The dashboard architecture aligns with the analytical requirements documented in the Dashboard_Plan worksheet.

 

𝐑𝐞𝐜𝐨𝐦𝐦𝐞𝐧𝐝𝐚𝐭𝐢𝐨𝐧𝐬



 

𝐏𝐫𝐨𝐭𝐞𝐜𝐭 𝐚𝐧𝐝 𝐒𝐜𝐚𝐥𝐞 𝐇𝐢𝐠𝐡-𝐕𝐚𝐥𝐮𝐞 𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐋𝐢𝐧𝐞𝐬


 

Prioritise Gaming Laptop and the other leading products in demand forecasting, inventory availability and promotional planning. Because the top products account for a substantial share of revenue, stock-outs or pricing issues in these products could have disproportionate revenue effects.

 

𝐒𝐭𝐫𝐞𝐧𝐠𝐭𝐡𝐞𝐧 𝐭𝐡𝐞 𝐋𝐨𝐰𝐞𝐫-𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐢𝐧𝐠 𝐑𝐞𝐠𝐢𝐨𝐧𝐬



 

North and Central are the strongest regions, while West is the lowest. Management should assess customer coverage, sales activity, product availability and channel effectiveness in West and South to identify practical growth constraints.

 

𝐎𝐩𝐭𝐢𝐦𝐢𝐬𝐞 𝐂𝐡𝐚𝐧𝐧𝐞𝐥 𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐲




 

Online is the leading channel and should continue to receive strategic attention. At the same time, Marketplace has the smallest contribution and should be assessed for conversion, product assortment, pricing competitiveness and customer acquisition efficiency before additional investment is made.

 

𝐔𝐬𝐞 𝐒𝐞𝐚𝐬𝐨𝐧𝐚𝐥 𝐏𝐥𝐚𝐧𝐧𝐢𝐧𝐠






 

The strong November and June performance and the weaker May and July results indicate seasonality. Sales forecasts, inventory procurement and campaign calendars should therefore incorporate month-specific expectations rather than relying only on annual targets.

 

𝐒𝐭𝐫𝐞𝐧𝐠𝐭𝐡𝐞𝐧 𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐑𝐞𝐭𝐞𝐧𝐭𝐢𝐨𝐧







 

Returning customers generate the majority of revenue. The business should therefore maintain structured retention initiatives, repeat-purchase campaigns and customer-value monitoring to protect the existing revenue base while continuing to acquire new customers.

 

𝐌𝐨𝐧𝐢𝐭𝐨𝐫 𝐃𝐢𝐬𝐜𝐨𝐮𝐧𝐭 𝐈𝐦𝐩𝐚𝐜𝐭








 

Discount is a core source field and is already incorporated into the Revenue calculation. Future dashboard iterations should consider adding a discount-performance view that evaluates whether higher discount levels generate sufficient incremental revenue or volume to justify margin sacrifice.

 

𝐌𝐚𝐢𝐧𝐭𝐚𝐢𝐧 𝐃𝐚𝐬𝐡𝐛𝐨𝐚𝐫𝐝 𝐆𝐨𝐯𝐞𝐫𝐧𝐚𝐧𝐜𝐞








 

The dashboard should be refreshed from the transaction source and supporting pivot calculations using a controlled refresh process. KPI definitions should remain documented, and any changes to source fields, filter logic or aggregation rules should be version-controlled.

 

𝐋𝐢𝐦𝐢𝐭𝐚𝐭𝐢𝐨𝐧𝐬 𝐚𝐧𝐝 𝐃𝐚𝐭𝐚 𝐆𝐨𝐯𝐞𝐫𝐧𝐚𝐧𝐜𝐞
 

The analysis is descriptive and is based exclusively on the supplied workbook and dashboard. It identifies observed patterns but does not establish causal relationships. For example, the report cannot determine from the dataset alone why November is the strongest month.

The Revenue field is treated as the final sales amount supplied by the workbook. The report does not estimate profit, gross margin, customer acquisition cost, fulfilment cost or channel profitability because those measures are not provided.

Salesperson performance is present in the source data but is not included as a dedicated visual in the supplied dashboard. It can therefore support additional analysis, but it should not be interpreted as a current dashboard KPI unless explicitly added to the dashboard.

The dashboard date indicator states that the data is updated through 12/31/2026, which aligns with the maximum Date value in the transaction data. This provides consistency between the displayed update date and the underlying reporting period.

 
