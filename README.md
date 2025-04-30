▶️ [Click here to view the full analysis in Google Colab](https://colab.research.google.com/drive/1U3TT8Uyg3qC72JvXWZh0-Ke7ihqUq3tE?usp=sharing)

**Problem Statement**
Yulu aims to uncover key factors driving demand for shared electric cycles in India to optimize operations and enhance business performance.

**Dataset Used**
https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089

**Tools/Libraries**
pandas, matplotlib, seaborn, scipy.stats

**Key Findings**
1. Complete Data: Dataset has 10,886 entries with no missing values—ideal for analysis.
2. Rental Pattern: Total bike rentals are right-skewed, indicating most users rent fewer bikes, with a few high-rental instances.
3. Seasonal Trend: Season 3 sees the highest rentals, while Season 1 has the lowest—demand varies significantly with season.
4. Workday Impact: Rentals are higher on working days than non-working days, though non-working days show more outliers.
5. Weather Influence: Most rentals occur under weather condition 1 (clear), while condition 4 (likely poor weather) has consistently low rentals.

**Recommendations**
1. Uniform Strategy Across Days: Demand is consistent across working and non-working days—Yulu can maintain similar operations throughout the week. Focus on optimizing fleet by time of day instead.
2. Adjust for Seasonal Demand: Rentals vary by season. Increase cycle availability during high-demand seasons and offer discounts or subscriptions during low-demand periods like monsoon.
3. Weather-Responsive Operations: Rentals drop in bad weather. Boost marketing in good weather, and provide safety gear or insurance to support moderate-weather usage.
4. Seasonal Planning for Weather: Since weather patterns align with seasons, Yulu can plan fleet adjustments in advance, reducing cycles during expected poor weather seasons.



