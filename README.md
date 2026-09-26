# 🏠 Austin Housing Market Analysis

An interactive Power BI dashboard exploring 15,171 Austin-area
properties to understand pricing, location, property characteristics,
school factors, and the features associated with higher listing prices.

### 🔗 Quick Links
📊 View Interactive Dashboard

https://app.powerbi.com/view?r=eyJrIjoiNDExOTE3ODEtMzZkMi00NWU2LWJlZDgtZTQ2YjE0ODNiMjJmIiwidCI6IjhkMzFkMTQ0LWI3ZjMtNDY2OC1iOGEwLTZhNzRmNWU0Y2Q4MSJ9

## 📌 Project Overview

This project analyses **15,171 residential property listings in the Austin, Texas area** to understand housing prices, property characteristics, geographical distribution, school-related factors, and the features associated with higher listing prices.

The Power BI dashboard transforms property-level housing data into an interactive analytical tool that allows users to explore the Austin housing market by **property type, location, price, living area, lot size, year built, property features, and nearby school characteristics**.

The goal of the project is to answer practical questions such as:

- What does a typical property in the dataset look like?
- How have listing prices changed over time?
- Which property types dominate the market?
- Which property characteristics are associated with higher prices?
- How are properties distributed geographically?
- How do school characteristics vary across different areas?

### 🛠️ Tools Used

- **Power BI** – Data modelling, DAX, dashboard development and interactive analysis
- **Power Query** – Data cleaning and transformation
- **Microsoft Excel** – Source dataset
- **Bing Maps** – Geographical visualisation

---

# 1. Background & Overview

The Austin housing market contains properties with considerable differences in price, size, location, property type and surrounding amenities. Looking only at individual listings makes it difficult to understand the broader patterns within the market.

This project was developed to provide a consolidated view of the housing data and make these patterns easier to identify.

The analysis focuses on four main areas:

1. **Market Overview** – Overall property prices, sizes, property types and features.
2. **Location Analysis** – Geographical distribution of properties and prices.
3. **School Analysis** – School ratings, school size and student-to-teacher characteristics by area.
4. **Property Feature Analysis** – Characteristics associated with differences in listing prices.

The resulting Power BI report consists of four interactive dashboard pages:

- **Summary**
- **Location**
- **Schools**
- **Features**

---

# 2. Data Structure & Overview

The dataset contains **15,171 property records** with **47 attributes** describing the properties, their locations, physical characteristics, prices and nearby schools.

### Key Data Fields

| Category | Example Fields |
|---|---|
| Property Identification | Property ID, Address, City, Zip Code |
| Location | Latitude, Longitude |
| Price | Latest Price, Price Changes, Sale Date |
| Property Characteristics | Home Type, Year Built, Bedrooms, Bathrooms, Stories |
| Property Size | Living Area, Lot Size |
| Parking | Garage Spaces, Parking Spaces, Has Garage |
| Property Features | Association, Cooling, Heating, Spa, View |
| Schools | School Rating, School Size, School Distance, Students per Teacher |
| Additional Features | Appliances, Security, Waterfront, Community and Accessibility Features |

### Dataset Snapshot

| Metric | Value |
|---|---:|
| Total Properties | **15,171** |
| Median Home Price | **$405,000** |
| Average Home Price | **$512,770** |
| Highest Listed Price | **$13.5M** |
| Lowest Listed Price | **$5.5K** |
| Median Living Area | **1,975 sq ft** |
| Average Living Area | **~2,210 sq ft** |
| Median Lot Size | **8,276 sq ft** |

The dataset covers recorded sale/listing years from **2018 to 2021**.

---

# 3. Executive Summary

## Overview of Findings

The analysis shows that the dataset is overwhelmingly dominated by **single-family homes**, which account for approximately **94% of all properties**.

The typical property has a **median price of $405K**, while the average price is considerably higher at approximately **$512.8K**. This difference indicates that higher-priced properties pull the average upward, making the median a more representative measure of the typical property in this dataset.

Property characteristics also show clear relationships with price. Larger living areas and lot sizes are strongly associated with higher listing prices, while features such as **spas, views, garages, cooling and heating** are also associated with higher median prices.

Geographically, properties are concentrated throughout the greater Austin area, with the interactive map allowing users to identify how prices and housing characteristics vary across locations.

---

## 📈 Market & Price Trends

Median property prices increased across the main years represented in the dataset:

| Year | Properties | Median Price |
|---|---:|---:|
| 2018 | 4,395 | **$385K** |
| 2019 | 5,277 | **$395K** |
| 2020 | 5,416 | **$434.9K** |
| 2021* | 83 | **$520K** |

Between **2018 and 2020**, the median property price increased from approximately **$385K to $434.9K**, representing an increase of roughly **13%**.

The 2021 records show a higher median price of approximately **$520K**, but this should be interpreted cautiously because only **83 properties** are represented for that year.

---

# 4. Insights Deep Dive

### 🏘️ Single-Family Homes Dominate the Market

**14,241 of 15,171 properties (94%)** are single-family homes, making them by far the largest property segment in the dataset.

**Takeaway:** The analysis primarily reflects Austin's single-family housing segment.

---

### 💰 Median Price Better Represents a Typical Property

The **median home price is $405K**, compared with an average of **$512.8K**.

**Takeaway:** High-value properties pull the average upward, making the median a more useful benchmark for the typical property.

---

### 📈 Property Prices Increased Over Time

Median prices increased from approximately **$385K in 2018 to $434.9K in 2020**, an increase of roughly **13%**.

**Takeaway:** The dataset shows an upward price trend across the main 2018–2020 observation period.

---

### 🏡 Property Features Are Associated With Higher Prices

Homes with certain features generally have higher median prices. The largest differences are visible for properties with **spas, views, and garages**.

For example, homes with a spa have a median price of approximately **$575K**, compared with around **$399K** for homes without one.

**Takeaway:** Amenities can help distinguish higher-priced segments of the housing market.

---

### 📐 Larger Properties Are Associated With Higher Prices

Power BI's Key Influencers analysis highlights **living area and lot size** among the strongest characteristics associated with higher listing prices.

Properties with living areas above approximately **3,392 sq ft** and lot sizes above approximately **21,780 sq ft** are associated with substantially higher listing prices.

**Takeaway:** Property size is an important factor when comparing different segments of the market.

---

### 📍 Location & Schools Add Market Context

Property distribution varies across the Austin area, while nearby school characteristics also differ between locations.

The dashboard allows users to explore properties by **price, size, location, school rating, school size, and students per teacher**.

**Takeaway:** Property characteristics should be considered together with geographical and neighbourhood context.

---

# 5. Recommendations

Based on the analysis:

- **Use median price as the main market benchmark** because extreme property values can distort averages.
- **Compare property size alongside price**, particularly living area and lot size.
- **Consider features such as spas, views, and garages** when comparing similar properties.
- **Combine location and property characteristics** rather than evaluating price in isolation.
- Use **school information as additional neighbourhood context** when comparing different areas.

