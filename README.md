# NY-housing-analysis
New York Housing Market Analysis using Python and Seaborn
# 🏠 New York Housing Market Analysis

This project explores house listing data from New York to uncover valuable insights for brokers, buyers, investors, and analysts. It uses Python, Seaborn, and Matplotlib to visualize pricing trends, analyze broker performance, and evaluate the impact of property features on house values.

---

## 📦 Dataset Description

The dataset includes detailed information on New York residential properties:

| Column | Description |
|--------|-------------|
| `BROKERTITLE` | Title of the broker or agency |
| `TYPE` | Property type (e.g., Condo, House, Foreclosure) |
| `PRICE` | Listing price of the property |
| `BEDS` | Number of bedrooms |
| `BATH` | Number of bathrooms |
| `PROPERTYSQFT` | Property size in square feet |
| `ADDRESS`, `MAIN_ADDRESS`, `FORMATTED_ADDRESS` | Full address details |
| `STATE`, `ADMINISTRATIVE_AREA_LEVEL_2`, `LOCALITY`, `SUBLOCALITY` | Location-specific data |
| `STREET_NAME`, `LONG_NAME` | Street-level information |
| `LATITUDE`, `LONGITUDE` | Geographic coordinates for mapping |

---

## 🔍 Key Insights & Analysis

### 📉 Outlier Removal
- Removed top 1% of prices to reduce skewness and reveal meaningful market trends.

### 📊 Correlation Analysis
- Used a heatmap to reveal that **square footage (PROPERTYSQFT)** has the strongest positive correlation with price.

### 📈 Price Trends by Property Type & Size
- Grouped listings by house type and square footage bins.
- Created line charts to show how average price changes across size categories per property type.

### 🗺️ Street-Level Price Evaluation
- Identified **top 10 streets** with the highest average house prices.
- Visualized them via a pie chart to highlight premium areas.

### 📏 Price per Square Foot (PPSF)
- Introduced a `PricePerSqFt` metric.
- Ranked and visualized **top 10 localities** by PPSF to showcase investment potential.

### 🧑‍💼 Broker Performance
- Analyzed **top 10 brokers** by average selling price.
- Highlighted agencies handling higher-value properties.

---

## 📎 Files Included

- `NY_Housing.ipynb` — The complete Jupyter Notebook analysis.

---

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for data visualization
- Jupyter Notebook

---
