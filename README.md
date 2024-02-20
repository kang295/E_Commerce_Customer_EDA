# 🛒 Supermarket Customer EDA 📊

## 🎯 Objective
The objective of this project is to segment customers into different groups using 2 years of customer data and set the appropriate marketing strategy. The goal is to identify the primary group that brings the most profit to our business and understand their characteristics and preferences. For this process, we will utilize RFM (Recency, Frequency, and Monetary) analysis.

**RFM Components:**
- Recency: How recently did the customer make a purchase? 🕒
- Frequency: How often did the customer make a purchase? 🔄
- Monetary: How much did the customer spend on products? 💰

## 🛠️ Tools & Libraries
- Python 🐍
- Pandas 🐼
- Matplotlib 📊
- Seaborn 🌊

## 📊 Segmentation Grade Rule
- 3 -> Strong ✨
- 2 -> Medium 🟡
- 1 -> Weak ❌

## 📈 Insights
1. There is no significant difference in sales across Recency grades.
2. Customers with higher Frequency grades contributed more to net sales.
3. Customers with higher Monetary grades significantly contributed to net sales.

Based on this information, we have determined the RFM coefficients:
- Recency: 0.2
- Frequency: 0.4
- Monetary: 0.4

## 🔍 Key Findings
1. The RFM segment (3) accounts for about 70% of total sales. Focusing on managing this high-contribution segment can significantly boost future sales.
2. Targeting middle-aged and older demographics might be more effective than targeting younger generations within the high-contribution RFM segment.
3. While there's no significant difference in marital and child distribution across RFM segments, the high-contribution RFM segment has over 40% childless customers, suggesting potential marketing strategies tailored to this demographic.
4. Liquor and meat are the predominant categories driving sales within the high-contribution RFM segment (3), making them ideal focal points for marketing efforts.
5. Promotion participation rates notably increase from grade 1 to grade 3. This suggests that customers who spend more are likely to be more interested in promotions, indicating potential for targeted promotional strategies.

## 💡 Conclusion
Understanding customer segments through RFM analysis provides valuable insights for crafting effective marketing strategies, ultimately driving sales and enhancing customer satisfaction. 🚀
