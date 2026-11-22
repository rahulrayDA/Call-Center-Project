# PwC Call Centre Data Analysis — Power BI Dashboard

A comprehensive interactive Power BI dashboard built to monitor call centre operations, track agent efficiency, evaluate customer satisfaction, and identify peak call traffic patterns across **5,000 customer calls**.


## Project Overview

This project analyzes operational performance for a customer support centre (based on the PwC Call Centre Trends dataset). The dashboard transforms raw call logs into actionable executive KPIs, agent-level scorecards, and time-series traffic distributions to help operations managers optimize staffing, reduce call abandonment, and improve Customer Satisfaction (CSAT).


## Key Performance Indicators (Executive Summary)

* **Total Call Volume:** 5,000 incoming calls recorded up to `31-03-2021 17:39:50`
* **Customer Satisfaction (CSAT):** 68.07% overall satisfaction rating
* **Call Resolved Rate:** 72.92% of calls successfully resolved
* **Call Abandoned Rate:** 18.92% of calls dropped before reaching an agent
* **Average Speed of Answer (ASA):** 67.52 seconds
* **Average Call Handling Time (AHT):** 224.92 seconds (~3.75 minutes)



## Dashboard Breakdown & Analytical Insights

### 1. Agent Performance Scorecard

A granular matrix evaluating all **8 support agents** across volume, speed, resolution, and satisfaction metrics:

* **Top Call Volume:** Jim handled the highest volume (666 calls), followed by Martha (638), Dan (633), and Diane (633)
* **Highest Resolution Rate:** Dan achieved the top resolution rate at **74.41%** alongside the lowest abandonment rate (**17.38%**)
* **Highest CSAT:** Martha led customer satisfaction at **69.42%**, closely followed by Dan (**68.95%**)
* **Fastest Answer Speed:** Stewart recorded the lowest Speed of Answer at **66.18 seconds**, while Joe averaged **70.99 seconds**
* **Abandonment Alert:** Diane experienced the highest call abandonment rate at **20.85%**



### 2. Calls by Satisfaction Levels

A categorical distribution breaking down customer feedback ratings across the 5,000 calls:

* **Normal & Satisfied:** ~1.2K calls each (forming the largest share of rated interactions)
* **Very Satisfied:** ~0.8K calls
* **Not Served (Unanswered/Abandoned):** ~0.9K calls
* **Dissatisfied & Very Dissatisfied:** ~0.4K calls each



### 3. Call Volume by Hour (Intraday Traffic)

An area chart tracking hourly call distribution from **09:00 to 18:00**:

* Call traffic remains consistently high (>500 calls/hour) between **09:00 and 17:00**, peaking around **11:00** and **13:00**
* Volume drops sharply at **18:00** as support operations wind down



### 4. Call Volume by Day of Week

An area chart identifying weekly demand patterns from **Monday to Sunday**:

* **Peak Days:** **Monday** and **Saturday** experience the highest call surges (~770 calls each)
* **Mid-Week Dip:** **Tuesday**, **Wednesday**, and **Friday** see lower call volumes (~670–680 calls), with a slight mid-week bump on **Thursday** (~710 calls)


## Interactive Features & Navigation

* **Dynamic Slicers:** Filter the entire report seamlessly by **Agent**, **Topic**, **Month**, and **Weekday**
* **Clear Filters Button:** One-click reset bookmark to restore the default view
* **Multi-Page Navigation:** Dedicated **Agent Analysis** drill-through/page button for deeper individual agent diagnostics
* **Data Freshness Indicator:** Live card displaying the timestamp of the last recorded call (`31-03-21 17:39:50`)



## Tools & Skills Demonstrated

* **Business Intelligence:** Power BI Desktop (Data Modeling, DAX Measures, Custom Visuals, Bookmarks & Navigation)
* **Data Analysis:** KPI Benchmarking, Time-Series Trend Analysis, Agent Scorecarding, Operational Bottleneck Identification


## Business Recommendations

1. **Staffing Optimization:** Increase agent shift coverage on **Mondays and Saturdays** and during the **11:00–13:00** lunch-hour peak to bring down the **18.92% abandonment rate**.


2. **Targeted Coaching:** Pair agents with higher abandonment/lower resolution metrics (e.g., Diane, Joe) with top performers like **Dan** and **Martha** to standardize call-handling workflows.


3. **Unserved Call Recovery:** Investigate the **~0.9K "Not Served"** calls to determine whether queue routing rules or callback automation can recapture lost customer interactions.







