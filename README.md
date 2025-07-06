# Capstone-IBM-Hacktiv8-Ivan

# Title Project:
Capstone project - Data-Driven Insights on Smartphone Market Trends in India Based on Specifications and Ratings

# Project Overview:
- The goal of this project is to analyze a smartphone dataset to understand how technical specifications affect product prices and ratings.
- Analyze features like brand, model, RAM, processor, price, and rating
- Identify trends in specifications and pricing

  Expected View:
  - Market and technical insights
  - Actionable recommendations

# Raw Dataset Link:
https://www.kaggle.com/datasets/chaudharisanika/smartphones-dataset

# Insight & Findings
# A. Barchart of Number of Smartphones per Brand
1. Dominance of Specific Brands:
Xiaomi and Samsung are the top two brands with the largest number of smartphone variants (over 130 models), indicating their dominance in terms of product diversity in the market. Other brands that also have a large number of models are Vivo, Realme, and Oppo, each with over 90 units.

2. Differentiated Product Strategy:
Brands like Apple and OnePlus, though well-known, have fewer models (~40 models).

3. Niche and Rare Brands:
Many brands like Blackview, Sharp, TCL, Vertu, and Tesla are at the bottom with very few models (less than 5).

4. Product Distribution Pattern:
The graph shows an uneven distribution, with most smartphones coming from only a handful of big brands.

# B. Scatter Plot features RAM vs Price with Brand Name
1. General Positive Correlation
In general, there is a positive correlation between RAM capacity and price. The larger the RAM (eg 12GB, 16GB), the higher the price of the smartphone.

2. Popular RAM Distribution
The most commonly used RAM capacities are 4GB, 6GB, and 8GB, reflecting that most smartphones are in the middle segment.

3. Price Variants in RAM are the Same
In 6GB and 8GB RAM, there is a very wide price variation, starting from tens of thousands to above 60 thousand. This shows that the price is not only determined by RAM, but also other specifications such as the processor, brand, or premium features.

4. Premium & Expensive Brands
Brands such as Apple, Samsung, and OnePlus appear to have higher prices than other brands even with the same RAM capacity, reflecting a premium brand strategy.

# C. Bar chart to see the highest to lowest smartphone prices
1. Most Expensive Premium Brands:
Brands like Royole, Vertu, Apple, and LG top the charts with the highest average smartphone prices (above 60,000). This shows that they focus on the premium or niche segment with advanced features and exclusive designs.

2. Mid-range Brands:
Brands like Samsung, Huawei, ZTE, and Nubia fall in the mid-range price range, showing a combination of quality and availability of models in various classes.

3. Economy Brands:
At the bottom of the chart, brands like Micromax, Lyf, Letv, iKall, and TCL have the lowest average prices (below 10,000), indicating a focus on the entry-level or emerging markets.

# D. Pie Chart to see the distribution of Operating Systems (OS) for each Smartphone brand
1. Android Dominance:
Android OS dominates the smartphone market with a share of 94.2%, indicating that almost all manufacturers (apart from Apple) use Android as their operating system.

2. Limited iOS Share:
iOS is only used by 4.69% of all smartphones in the dataset, indicating iOS's exclusivity on Apple devices only.

3. Other OS are a Very Minority:
The “other” category OS (apart from Android & iOS) only covers 1.12%, which can include legacy systems such as KaiOS, HarmonyOS, or special systems from certain brands—but their use is very limited.

# E. Linechart to see the price trend of each smartphone processor brand
1. Most Expensive Bionic Processors:
Bionic (used by Apple) tops the chart with the highest average smartphone price, reflecting Apple’s consistent premium segment.

2. Mid-range Processors:
Brands like Snapdragon, Exynos, and Dimensity show mid to high average prices, consistent with their use in flagship to mid-range smartphones.

3. Budget Processors:
Processors like Mediatek, Spreadtrum, and SC9863A are at the bottom of the chart with low average prices, commonly found in low-end smartphones.

4. Market Class Differences:
There is a significant jump in prices from processors like Helio → Dimensity and Exynos → Google, indicating a fairly sharp product class difference based on the chipset used.

# AI Support Explanation
1) AI helps in automating processes:
- Data cleansing and anomaly detection
- Interactive visualization using Plotly
- Insight generation through correlation and distribution analysis
2) Using Large Language Model (LLM) models such as IBM Granite 3.3-8b-Instruct to construct insight interpretation and data narratives.
4) Potential further application: smartphone recommendations based on user preferences with the help of AI/ML.
