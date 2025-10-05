 Objective

To determine how discounts impact sales performance and identify the conditions under which they help or hurt business outcomes.

Specifically:

How different discount levels affect sales volume.

Whether discounting cheaper vs. premium products yields different results.

How seasonality (e.g., Christmas, Black Friday) drives spikes in sales.

📊 Dataset Description

The dataset includes transaction-level data such as:

Product ID / Category

Original Price & Discount (%)

Units Sold / Sales Volume

Revenue

Date of Transaction

🧹 Data Cleaning

Removed missing or invalid discount entries.

Standardized numeric columns (price, discount, revenue).

Formatted dates for time-series analysis.

Filtered out incomplete or duplicate records.

🧠 Analysis & Insights
1. Discount Distribution

Most products were sold with discounts below 25% — indicating customers are highly responsive even to modest price reductions.

2. Product Tier Impact

Discounts significantly boost sales of cheaper products, showing high price sensitivity in that segment.
Premium products, however, saw limited reaction to discounts — suggesting an opportunity to test new pricing tactics.

3. Seasonality

Black Friday and Christmas periods showed massive sales spikes, confirming that timing is a crucial factor in the effectiveness of discounts.

4. Data Quality

Consistent data cleaning and structuring improved the clarity of insights, demonstrating the importance of robust data collection systems.

📈 Key Takeaways

✅ Most products sell under 25% discount levels.
✅ Discounts boost sales — especially for lower-priced items.
✅ Seasonal promotions outperform general discounts.
✅ Clean, structured data leads to more reliable insights.

💡 Business Recommendations

Focus discount strategies on low- to mid-tier products to maximize sales.

Introduce targeted discount pilots for premium products to test elasticity.

Align discount campaigns with seasonal high-traffic periods.

Continue to improve data collection and quality assurance.

🧭 Action Plan

STANDARDIZE database & CAPTURE missing fields.

Track DISCOUNTS and CAMPAIGNS explicitly.

Pilot targeted DISCOUNT campaigns on premium products.

PREPARE specific SEASONAL strategies to maximize timing effects.

🧰 Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Google Colab

 CSV Files for dataset management
│
├── Data
     brands.csv
     orderlines.csv
     orders.csv
     products.csv
├── notebooks/
[Colab Notebook]( https://colab.research.google.com/drive/1LV0ivep1PsK7-cOxGFKY2maCWs5eBBbq?usp=sharing "Colab Notebook")

  VISUALISATION
[Visualisation/Slide](https://docs.google.com/presentation/d/1iTJx_3e7lEE64SNmQz-1Wi6asperRanoy5YXYFCSv9Y/edit?slide=id.g38098043384_0_317#slide=id.g38098043384_0_317 "Visualisation/Slide")
