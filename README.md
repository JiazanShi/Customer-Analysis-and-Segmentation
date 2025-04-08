# Customer-Analysis-and-Segmentation
Side project for customer data analysis

**Project Summary:**

This project focuses on analyzing customer data to support strategic decision-making and identify profitable customer segments. The goal is to uncover data-driven insights that can inform and refine customer targeting strategies.

This project was built up on offline retail customer dataset and purchase behavior dataset for energy bar. For this analysis, I treated *Brand 5* as the client and considered the remaining brands as competitors.

**Customer Segmentation:**

I performed customer segmentation using key demographic features from the dataset, including age, education, income, and occupation. To enhance clustering performance and interpretability, I applied Principal Component Analysis (PCA) for dimensionality reduction before fitting a KMeans clustering model. This process identified four distinct customer segments:

1. **Well-Off** – Middle-aged individuals who are well-educated and have high incomes.
2. **Career-Focused** – Young, well-paid professionals who are typically single.
3. **Fewer Opportunities** – Lower-income individuals living in rural areas with limited access to resources.
4. **Standard Group** – Customers with average demographic and income levels.

These segments offer valuable insights to help Brand 5 tailor its marketing and engagement strategies more effectively.

**Purchase Analysis:**

Next, I analyzed offline customer purchase data, which included transaction details, pricing, and customer information. By applying the previously developed segmentation model, I assigned each customer to a segment to explore segment-specific behaviors. The analysis revealed clear differences in purchase patterns and brand preferences. Notably, the Career-Focused segment showed strong loyalty to *Brand 5* and contributed the highest share of its revenue, indicating this group as high-value and brand-loyal.

**Predictive Modeling:**

I developed logistic regression models to predict purchase likelihood based on changes in price and customer segments. This enabled the estimation of price elasticity across segments. The results showed that the Career-Focused segment is less price-sensitive compared to the Well-Off segment. These insights can guide pricing strategies—helping the client respond effectively to competitor pricing moves and optimize revenue across segments.
