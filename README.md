
# Nairobi Real Estate Market Analysis: Findings and Insights

## Executive Overview
This report presents the core findings from analyzing housing data across various neighborhoods in Nairobi. The goal of this study is to understand what features drive property prices, how different locations compare in value per square meter, and how property layouts impact overall pricing.

---

## 1. What Drives Property Prices in Nairobi?

### Location and Land Value vs. Building Size
* **Prime Locations Command a Massive Premium:** In neighborhoods like Rosslyn, Runda, Muthaiga, and Thigiri, property values are driven primarily by location and land positioning rather than the physical size of the house. In these areas, land value per square meter ranges from KES 650,000 to over KES 2,000,000.
* **Density versus Plot Size:** High-density areas like Kilimani and Kileleshwa have lower price-per-square-meter values (around KES 115,000 to KES 125,000 per m²). Their prices depend on floor area and building volume. In contrast, areas like Karen have high total prices (median around KES 90,000,000) largely because properties sit on very large land plots, even though their price per square meter is lower (around KES 370,000 per m²).

---

## 2. Property Features and Layout Trends

### Bathroom-to-Bedroom Ratio
* **En-suite Bathrooms in High-End Neighborhoods:** In top-tier neighborhoods, properties average a bathroom-to-bedroom ratio of 1.0 or higher. This means buyers in these areas expect every bedroom to have its own private bathroom.
* **Shared Facilities in Suburban/Mid-Density Areas:** In mid-density neighborhoods and outer suburbs, the ratio drops to between 0.4 and 0.7, reflecting traditional layouts with shared bathrooms.
* **Overall Market Patterns:** Across the entire dataset, the bathroom-to-bedroom ratio shows a slight negative correlation (-0.16) with total price. This occurs because the market contains different property categories:
  * High-value vacant land and commercial plots have zero bathrooms.
  * Multi-bedroom apartments pack several rooms into smaller spaces.

---

## 3. Price Distributions and Data Characteristics

### Skewed Pricing Data
* **Extreme High-End Outliers:** Raw property prices in Nairobi are heavily right-skewed. A small number of multi-acre estates and commercial properties command prices far above the average residential home.
* **Log Transformation:** Converting raw prices using a log scale creates a balanced distribution. This adjustment makes linear relationships clearer between house size, room count, and market value.

---

## 4. Practical Recommendations

### For Property Developers
* **Design En-suite Bedrooms:** When building homes aimed at mid-to-high-income buyers, ensure each bedroom includes an attached bathroom, as this layout matches buyer expectations in prime zones.

