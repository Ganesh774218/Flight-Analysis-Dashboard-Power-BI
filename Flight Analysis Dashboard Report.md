### **Flight Analysis Dashboard Report**





#### **1. Project Overview**



This project analyzes 10,636 Indian domestic flights to understand:

* Why flights are delayed
* Which airlines, routes, and months contribute the most to delays
* How factors like halt time, total stops, route complexity, and seasonality impact delays



The dashboard integrates KPIs, route-level analysis, airline performance, monthly trends, and delay correlations to deliver actionable insights.







#### **2. KPIs Summary**

| KPI                  | Value  | Insight                                  |

| -------------------- | ------ | ---------------------------------------- |

| \*\*Total Flights\*\*    | 10,636 | Strong dataset coverage                  |

| \*\*Total Revenue\*\*    | ₹96M   | High economic impact of delays           |

| \*\*Avg Ticket Price\*\* | ₹9.07K | Delays affect mid-to-high priced tickets |

| \*\*Late Flights\*\*     | 5,609  | ~53% flights delayed                     |

| \*\*On-Time Flights\*\*  | 5,027  | Almost equal split                       |

| \*\*Non-stop Flights\*\* | 32.82% | Majority flights involve stops           |





**✅ Insights-**  Over half of the flights are delayed, indicating systemic operational challenges.

&nbsp;           -  More than 52% of flights are delayed, indicating systemic operational issues across airlines or routes.







#### **3. Airline-Level Delay Insights**

**🔴 Average Delayed Time by Airline**

* Air India: ~482 minutes (highest)
* Jet Airways: ~416 minutes
* Vistara: ~297 minutes
* IndiGo \& GoAir: Lowest delays



**📌 Insight:**

Legacy and full-service carriers experience longer delays compared to low-cost airlines, likely due to:

* More connecting flights
* Complex scheduling
* Higher dependence on hub operations
* Air India \& Jet Airways show extreme delays, likely due to multi-stop southern routes and monsoon impact.
* IndiGo \& GoAir maintain low delays, suggesting efficient direct routing and better scheduling.





#### **4. Route Complexity \& Stops Analysis**

**✈️ Average Stops by Airline**

* Jet Airways Business \& Air India have highest average stops
* IndiGo and Air Asia mostly operate simpler routes



🚦 Stops Distribution

1-stop routes: 52.89%

Non-stop routes: 32.82%

2-stop routes: ~14%



**📌 Insight:**

* More stops = higher halt time = higher risk of cascading delays.







#### **5. Busiest Route Analysis**

**🏆 Busiest Route**



DEL → BOM → COK

2,376 flights



⏱ Stops \& Delay on Busiest Route

Stops: 1

Late flights: 1,806

On-time flights: 570



**📌 Insight:**

* Even a single-stop high-traffic route can generate massive delays due to congestion at transit airports (especially BOM).





#### 

#### **6. Maximum \& Minimum Extremes**

| Metric               | Value     | Route / Airline           |

| -------------------- | --------- | ------------------------- |

| \*\*Max Travel Time\*\*  | 47 hours  | Jet Airways               |

| \*\*Min Travel Time\*\*  | 5 minutes | Air India                 |

| \*\*Max Ticket Price\*\* | ₹80K      | Premium multi-stop routes |

| \*\*Min Ticket Price\*\* | ₹2K       | Short-haul routes         |



**📌 Insight:** Long-haul, multi-leg routes dramatically increase both cost and delay exposure.









#### **7. Monthly Delay Trends (Critical Insight)**

**📅 Average Delayed Time by Month**

March: ~5 hrs

April: ~2 hrs (dip)

May: ~5 hrs

June: ~4.4 hrs



**🔥 Count of Delayed Flights**

May \& June show peak delays



**🌧️ Seasonal Reason (Key Finding)**

Flights experience higher delays from April to June, especially on southern routes, due to:

Heavy monsoon onset

Reduced visibility

Runway congestion

Air Traffic Control restrictions



**✅ Conclusion:**

* Seasonality is a major external delay driver, particularly impacting south India routes like DEL → BOM → COK and MAA → CCU.









#### **8. Route-Level Delay Analysis**

**⏳ Average Delay by Route**



Most delayed routes:

DEL – TRV – COK

DEL – UDR – BOM – COK

DEL – MAA – BOM – COK



**📌 Insight:**

Routes involving southern airports + multiple stops suffer from:

* Weather disruptions
* Ground congestion
* Extended halt times









#### **9. Halt Time vs Delay Correlation (Root Cause)**

**📊 Scatter Plot Analysis**

X-axis: Avg Halt Time

Y-axis: Avg Delay Time



High-risk airlines cluster:

Air India

Jet Airways

Vistara



**📌 Final Root Cause Identified:**

* Long halt time during layovers strongly correlates with higher delays.
* This confirms that ground operations and turnaround inefficiencies play a major role.









#### **10. Key Reasons Why Flights Are Late (Final Summary)**



✅ Top delay drivers identified:

* Seasonal Monsoon (April–June) – southern India weather
* High halt time at stops
* Multi-stop route complexity
* Airport congestion on busy routes
* Legacy airline operational structures









#### **11. Business Impact \& Recommendations**



Impact:

* Increased passenger dissatisfaction
* Revenue loss due to compensation and rebooking
* Operational inefficiencies



#### 

#### **Recommendations:**



* Optimize scheduling during monsoon months
* Reduce halt time on high-traffic routes
* Improve turnaround efficiency at hub airports
* Prefer non-stop or fewer-stop routing where possible





#### 

#### **Conclusion-**

* The Power BI analysis shows that flight delays are largely systematic rather than random—driven by a mix of operational bottlenecks, route- and network-level complexity, and pronounced seasonal effects.
* In particular, monsoon-related disruptions in southern India (peaking between April and June) emerge as a consistent contributor to delay incidence and severity.
