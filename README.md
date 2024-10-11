# Geographic Market Segmentation Analysis for Electric Vehicles (EVs) 🚗⚡

## Objective
The goal of this report is to analyze the geographic distribution of electric vehicle (EV) sales across various states in India. By examining the sales data, this study identifies key regions with high EV adoption and provides insights into geographic trends that influence EV sales. The analysis aims to support targeted EV promotion and infrastructure development efforts in high-adoption regions.

---

## Steps and Methodology

### 1. Data Collection 📊
The dataset, sourced from [Clean Mobility Shift](https://cleanmobilityshift.com), contains information on EV sales across multiple states in India. It includes columns such as:
- `State`
- `Vehicle Type`
- `Vehicle Category`
- `Electric_Vehicle_Sales_Quantity`

This dataset provides a comprehensive view of the geographic distribution of EV sales.

### 2. Preprocessing 🔍
The dataset was cleaned to ensure accuracy and relevance:
- **Missing Values**: Imputed any missing sales quantities using mean values.
- **Encoding**: Categorical variables like `State`, `Vehicle_Category`, and `Vehicle_Type` were encoded to facilitate clustering analysis.

### 3. Geographic Segmentation and Clustering 📍
- **K-means Clustering**: States were segmented into four clusters based on EV sales quantity. This allowed grouping of states with similar EV sales patterns, identifying regions with high or low adoption rates.
- **Visualization**: The clustered states were visualized using bar plots (to show EV sales across states) and mosaic plots (to illustrate state distributions within clusters).

---

## Exploratory Data Analysis (EDA) 🔬
- **Top States by EV Sales**: The top three states with the highest EV sales were identified. These states represent major markets for EV adoption and are key to understanding geographic preferences for EVs.
- **Cluster Summary**: Each cluster's characteristics were analyzed, highlighting regions with similar adoption trends and identifying areas that may benefit from additional EV infrastructure.

## Key Insights 💡
1. **High-Adoption States**: The top states in terms of EV sales, such as *Maharashtra*, *Karnataka*, and *Uttar Pradesh*, indicate significant market potential. Targeting these states for further promotion and development can maximize EV adoption.
2. **Regional Variations**: Different clusters exhibited varying EV adoption rates, likely influenced by factors like urbanization, income levels, and access to EV infrastructure.
3. **Urbanization and Economic Factors**: States with higher urban population densities and stronger economic conditions generally showed higher EV sales.

---

## Visualizations 📈
- **Bar Plot**: This plot displays the EV sales quantities across states, sorted in descending order, with each bar representing a state and colored by cluster. This visualization helps to compare sales figures directly.
- **Mosaic Plot**: The mosaic plot visualizes the distribution of states across clusters, providing a comprehensive view of the segmentation.

## Conclusion ✅
The analysis reveals that EV adoption in India is concentrated in specific states, with geographic and economic factors playing a critical role. This understanding can guide EV manufacturers and policymakers in targeting high-adoption areas for infrastructure investments and promotional efforts.

## Future Work 🚀
Further analysis could examine the influence of EV infrastructure availability, state-specific incentives, and consumer awareness on EV adoption. Exploring these factors could provide a more detailed understanding of the market dynamics and support the development of targeted strategies to promote EVs in regions with lower adoption rates.

---

### License
[MIT License](LICENSE)

---

### Acknowledgments
Thanks to [Clean Mobility Shift](https://cleanmobilityshift.com) for providing the dataset.

---

### Contact
For more information, please contact: [Your Name] - [Your Email]
