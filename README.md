# 🏠 Austin Housing Market Analysis | Power BI

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

## 🏘️ 4.1 Single-Family Homes Dominate the Dataset

**14,241 of the 15,171 properties are single-family homes**, representing approximately **94% of all properties**.

The next most common property type is condominium, with **470 properties**, followed by townhouses with **174 properties**.

| Property Type | Number of Properties |
|---|---:|
| Single Family | **14,241** |
| Condo | **470** |
| Townhouse | **174** |
| Multiple Occupancy | **96** |
| Vacant Land | **83** |
| Residential | **37** |
| Apartment | **37** |
| Mobile / Manufactured | **17** |
| MultiFamily | **10** |
| Other | **6** |

**Business takeaway:**  
The dataset primarily represents the single-family housing market. Conclusions about less common property types should therefore be treated cautiously because their sample sizes are considerably smaller.

---

## 💰 4.2 The Median Gives a Better Picture of the Typical Property Price

The **median property price is $405K**, compared with an **average price of approximately $512.8K**.

That is a difference of approximately **$108K**.

The dataset also contains properties ranging from approximately **$5.5K to $13.5M**, demonstrating the wide range of prices represented.

**Business takeaway:**  
A relatively small number of expensive properties pull the average upward. For understanding the price of a typical property in this dataset, the **median is therefore more informative than the mean**.

---

## 📈 4.3 Property Prices Increased Across the Main Observation Period

The median property price increased from approximately:

**$385K in 2018 → $395K in 2019 → $434.9K in 2020**

This represents an increase of approximately **13% between 2018 and 2020**.

The dataset shows a further increase to approximately **$520K in 2021**, although the 2021 sample contains only 83 records.

**Business takeaway:**  
The data indicates upward price movement during the main 2018–2020 observation period. The apparent 2021 increase should not be directly compared with previous years without accounting for the much smaller sample.

---

## 🛁 4.4 Spa Availability Shows One of the Largest Price Differences

Properties with a spa have a median price of approximately **$575K**, compared with approximately **$399K** for properties without one.

That represents a difference of roughly **$176K**, or about **44%** relative to the median for homes without a spa.

**Business takeaway:**  
Spa availability is associated with substantially higher-priced properties in this dataset. However, this should be interpreted as an **association rather than proof that adding a spa causes a property to increase in value**.

---

## 🌄 4.5 Properties With Views Are Associated With Higher Prices

Properties recorded as having a view have a median price of approximately **$475K**, compared with approximately **$395K** for properties without a view.

This represents a difference of approximately **$80K**, or roughly **20%**.

**Business takeaway:**  
Properties with views tend to sit in a higher price range, suggesting that location and surrounding environment may contribute to the premium associated with these properties.

---

## 🚗 4.6 Garage Availability Is Associated With a Price Premium

Properties with garages have a median price of approximately **$425K**, compared with approximately **$385K** for properties without garages.

This represents a difference of approximately **$40K**.

**Business takeaway:**  
Garage availability is associated with higher-priced properties, although other factors such as property size, location and property type may also contribute to this difference.

---

## ❄️ 4.7 Cooling and Heating Are Common Across the Housing Stock

Approximately **98% of properties have cooling**, while around **99% have heating**.

The median price for properties with cooling is approximately **$405K**, compared with approximately **$360K** for properties without cooling.

Properties with heating have a median price of approximately **$405K**, compared with approximately **$329K** among properties without heating.

**Business takeaway:**  
Cooling and heating are close to standard features in this dataset. Because properties without these features are relatively uncommon, comparisons between the two groups should be interpreted carefully.

---

## 📐 4.8 Property Size Is a Major Indicator of Higher Listing Prices

The Power BI Key Influencers analysis identifies property size as one of the strongest characteristics associated with higher listing prices.

When the **median lot size exceeds approximately 21,780 sq ft**, the analysis associates this condition with an average listed-price increase of approximately **$720.1K**.

Similarly, when **median living area exceeds approximately 3,392 sq ft**, the analysis associates it with an average listed-price increase of approximately **$655.9K**.

Other characteristics highlighted by the model include:

- **2–3 stories:** +$455.4K
- **2–3 parking spaces:** +$310.1K
- **Year built after 2017:** +$308.8K
- **Higher bathroom count:** +$179.1K

**Business takeaway:**  
Larger homes and larger lots are strongly associated with the higher end of the market. Property capacity and newer construction also appear frequently among higher-priced listings.

> **Note:** Power BI Key Influencers identifies statistical relationships within the dataset. These values should not be interpreted as causal effects.

---

## 📍 4.9 Location Plays an Important Role in Market Exploration

The geographical analysis shows that properties are distributed across Austin and surrounding areas rather than being evenly concentrated.

The interactive location dashboard allows users to filter the market by:

- Home price
- Living area
- Lot size
- Year built

This makes it possible to isolate specific housing segments and immediately see where those properties are concentrated geographically.

**Business takeaway:**  
Housing analysis should consider location together with price and property characteristics rather than treating Austin as a single uniform housing market.

---

## 🎓 4.10 School Characteristics Vary Across Locations

The properties in the dataset are linked with information about nearby schools.

Across the dataset:

- **Average School Rating:** 5.85
- **Average School Size:** approximately 1.24K students
- **Median Students per Teacher:** 14.8

The dashboard allows school characteristics to be analysed geographically using school rating, school size and students-per-teacher measures.

**Business takeaway:**  
The school dashboard provides additional neighbourhood context that can be considered alongside property price and location when comparing areas.

---

# 5. Recommendations

Based on the analysis, the following considerations may be useful for housing-market exploration and decision-making:

### 1. Use Median Price as the Primary Market Benchmark

Because the dataset contains several extremely expensive properties, the average price is noticeably higher than the median.

For general market comparisons, **median price should therefore be prioritised over average price**.

### 2. Evaluate Property Size Alongside Price

Living area and lot size show strong relationships with higher listing prices.

Buyers, analysts and investors should therefore compare properties using measures such as **price per square foot and property size**, rather than relying on total price alone.

### 3. Consider Property Features as Part of Market Segmentation

Properties with features such as **spas, views and garages** show higher median prices in this dataset.

These characteristics can be used to segment the market into more comparable groups when evaluating properties.

### 4. Combine Location and Property Characteristics

Location should not be evaluated independently.

Filtering simultaneously by **price, living area, lot size and construction year** can provide a more useful picture of where particular property segments are concentrated.

### 5. Treat School Information as Additional Location Context

School ratings, school size and student-to-teacher measures can provide additional context when comparing geographical areas.

They should be considered alongside other neighbourhood and property characteristics rather than as standalone indicators of property value.

---
