# Optimizing Ride-Sharing Performance & Customer Experience

The goal is to enhance ride efficiency, optimize pricing strategies, and improve customer satisfaction. By analyzing **Ride Sharing Dataset**, I uncovered key insights into user behavior, driver performance, and operational bottlenecks. This will allow the ride share platform to make data-driven decisions that drive growth and efficiency.

## Exploratory Data Analysis

## 1. KPI Metrics

| KPI                       | Value         |
|---------------------------|---------------|
| **Total Revenue**         | $600,938.35   |
| **Average Customer Rating** | 3.73        |
| **Average Ride Duration** | 54.03 minutes |
| **No-Show Rate**          | 5%            |
| **Total Rides Completed** | 8,495         |

***

## 2. Customer Behavior & Preferences

**Popular Pickup and Drop-off Locations**  
Movement concentrates between Suburbs and the Financial District. Bidirectional commuter flow dominates, with intra-suburb travel forming a secondary cluster. Mall-related routes sit at the lower end of demand.

**Weekends vs. Weekdays Ride Demand**  
Demand is weekday-centric. The business week anchors ride volume, while weekends show a pronounced drop, exposing a structural dependence on commuter activity.

**Most Preferred Vehicle Types**  
Sedans and SUVs form the core fleet demand. All other vehicle categories contribute marginally and reflect niche usage rather than primary preference.

## 3. Driver Performance & Efficiency

**Highest and Lowest Rated Drivers**  
A narrow group of drivers sustains ratings above 4.4, indicating consistent service quality. The lowest tier sits below 3.0, marking clear performance gaps.

**Impact of Driver Experience on Outcomes**  
Lower-experience drivers show marginally higher completion rates and user scores. As ride volume grows, both metrics trend downward, reflecting operational strain rather than skill deficiency.

**Average Ride Duration by Traffic Conditions**  
Low-traffic periods correlate with the longest trips. High-traffic windows tilt toward shorter, utilitarian routes, reducing average duration despite congestion.

***

## 4. Operational & Financial Insights

**Average Fare per Ride Type**  
SUVs sit at the top of the pricing ladder, with Sedans and Electric rides forming the mid-tier. Shared and Motorcycle categories anchor the low-fare segment.

**Effect of Surge Pricing on Fares and Revenue**  
Surge periods lift average fares and generate disproportionate revenue despite lower ride volume, confirming strong yield leverage from dynamic pricing.

**Most Common Payment Methods**  
Credit cards dominate transactions. Cash remains materially present. Mobile wallets form the smallest but still meaningful share.

***

### 5. External Factors Impacting Rides

**Weather Impact on Duration and Ratings**  
Thunderstorms stretch trip times and depress ratings. Clear conditions carry the largest share of rides with steadier satisfaction. Fog, rain, and snow shift metrics only slightly from baseline.

**Traffic Level Impact on Duration and Fares**  
Low-traffic windows correspond to longer, higher-fare trips. High-traffic intervals skew shorter and cheaper, indicating route mix rather than congestion severity as the main driver of duration.

***

## Tools Used

* **Excel**: For the initial cleaning process.
* **Python**: For Exploratory Data Analysis (EDA).
