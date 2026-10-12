# Call Center Sentiment & Customer Satisfaction Analysis — Excel Project

## Project Overview

This project is a **Call Center Sentiment & Customer Satisfaction Analysis Dashboard** built using Microsoft Excel. The purpose of this project is to transform raw call center data into meaningful business insights through data cleaning, data preparation, PivotTables, KPI development, data visualization, interactive slicers, and dashboard reporting.

The project focuses on understanding customer sentiment, evaluating customer satisfaction, monitoring Service Level Agreement (SLA) performance, analyzing call reasons, comparing support channels and call centers, and exploring call activity across states and dates.

The final dashboard combines important performance indicators, charts, interactive filters, and business recommendations into a consolidated reporting interface.

This project demonstrates practical Excel Data Analytics skills and follows an end-to-end data analysis workflow:

**Raw Data → Data Cleaning → Data Preparation → Analysis → KPI Development → Visualization → Interactive Dashboard → Business Insights**

## Project Objectives

The main objectives of this project are to:

- Inspect and prepare raw call center data for analysis.
- Organize the dataset into a clean, structured format.
- Analyze customer sentiment and identify potential customer experience issues.
- Calculate key performance indicators such as Total Calls, Average CSAT, Negative Sentiment, Within SLA, and Average Call Duration.
- Analyze call volumes by reason and state.
- Compare customer satisfaction across different support channels.
- Evaluate average customer satisfaction by call center.
- Compare SLA status with average customer satisfaction.
- Analyze call activity over time.
- Create PivotTables and charts for business reporting.
- Develop an interactive dashboard using Excel slicers.
- Present actionable findings and recommendations in a professional format.

## Dataset Description

The project uses call center data containing information about customer interactions and operational performance.

The analysis covers the following data dimensions:

| Data Dimension | Purpose |
|---|---|
| Call Timestamp | Analyze call activity over time |
| Sentiment Group | Understand customer sentiment distribution |
| Channel | Compare customer support channels |
| SLA Status | Evaluate calls against SLA categories |
| Reason | Identify the main reasons customers contact support |
| Call Center | Compare performance across call center locations |
| State | Explore the geographic distribution of calls |
| CSAT | Evaluate customer satisfaction |
| Call Duration | Analyze call handling time |

The exact source column names and calculated fields are maintained in the Excel workbook.

## Project Structure

The Excel workbook is organized into five worksheets.

### 1. Call Center Data

Contains the original call center dataset.

This sheet serves as the starting point of the analysis and preserves the source information before cleaning and preparation.

The data provides the foundation for customer sentiment analysis, satisfaction measurement, SLA reporting, call reason analysis, and operational comparisons.

### 2. Clean_Data

Contains the cleaned and prepared dataset used for the analysis.

The purpose of this sheet is to provide a consistent data source for PivotTables, charts, KPI calculations, and the interactive dashboard.

Data preparation supports reliable analysis by ensuring that the relevant fields are structured appropriately for filtering, grouping, aggregation, and visualization.

### 3. Analysis

Contains the main PivotTable-based analysis and KPI calculations.

The analysis includes:

- Call volume by reason
- Average CSAT by channel
- Customer sentiment distribution
- SLA status versus average CSAT
- Average CSAT by call center
- Daily call trends
- Call volume by state
- Overall KPI summary
- Supporting figures used to develop business insights

This sheet acts as the analytical foundation for the visualizations and dashboard.

### 4. Visualization

Contains the charts and visual elements created from the analyzed data.

The visualizations make it easier to compare categories, identify patterns, and understand call center performance without manually reviewing individual records.

The sheet supports the transition from numerical analysis to visual interpretation.

### 5. Dashboard

Contains the final interactive Call Center Sentiment & Customer Satisfaction Dashboard.

The dashboard brings together five KPI cards, seven charts, interactive slicers, and a business insights and recommendations section.

It is designed to provide a consolidated overview of call center performance while allowing users to investigate selected segments of the data.

## Key Performance Indicators (KPIs)

The dashboard includes the following overall performance indicators:

| KPI | Result |
|---|---:|
| Total Calls | 70 |
| Average CSAT | 5.33 |
| Negative Sentiment | 62.9% |
| Calls Within SLA | 75.71% |
| Average Call Duration | 26.3 minutes |

These indicators provide a quick overview of call volume, customer satisfaction, sentiment, SLA performance, and average call duration.

The KPI cards are connected to the dashboard's interactive filtering setup, allowing users to explore the metrics alongside the filtered charts.

## Analysis Performed

### 1. Call Volume by Reason

Call volume was analyzed across the main reasons customers contacted the call center.

The analysis covers:

- Billing Question
- Payments
- Service Outage

The comparison identifies which reasons generate the greatest call volume.

**Business value:** Understanding the most frequent reasons for contact can help prioritize support resources, improve customer guidance, and identify opportunities to reduce avoidable calls.

Billing Questions were identified as the largest call category in the analyzed dataset.

### 2. Average CSAT by Channel

Customer satisfaction was compared across four support channels.

| Channel | Average CSAT |
|---|---:|
| Call-Center | 5.70 |
| Chatbot | 4.82 |
| Email | 5.50 |
| Web | 5.41 |

The Call-Center channel recorded the highest average CSAT, while Chatbot recorded the lowest.

**Business value:** Comparing CSAT across channels helps identify where the customer experience may need improvement and where existing support approaches appear to perform relatively well.

### 3. Customer Sentiment Distribution

The sentiment analysis examines the distribution of customer interactions across the sentiment categories represented in the dataset.

The dashboard highlights Negative, Neutral, and Positive sentiment.

Negative sentiment combines the Negative and Very Negative categories for the overall KPI and corresponding business insight.

| Metric | Result |
|---|---:|
| Total Calls | 70 |
| Negative or Very Negative Calls | 44 |
| Negative Sentiment | 62.9% |

The results indicate that a substantial proportion of calls were classified as Negative or Very Negative.

**Business value:** Sentiment analysis can help identify potential customer experience problems and prioritize investigations into recurring complaints, unresolved issues, and service friction.

### 4. SLA Status vs Average CSAT

Customer satisfaction was compared across the SLA status categories used in the workbook.

The dashboard displays average CSAT for the SLA categories:

- Within SLA
- Above SLA

The visualization focuses on average customer satisfaction rather than combining call counts and CSAT scores in the same chart.

The overall SLA KPI is:

| Metric | Result |
|---|---:|
| Total Calls | 70 |
| Calls Within SLA | 53 |
| Calls Outside the Within-SLA Category | 17 |
| Within SLA Percentage | 75.71% |

**Business value:** SLA analysis helps monitor operational performance and investigate calls that fall outside the target category.

The meaning of each SLA category should be interpreted according to the definitions used in the source dataset.

### 5. Average CSAT by Call Center

Customer satisfaction was compared across the call center locations represented in the dataset.

The chart includes:

- Denver/CO
- Chicago/IL
- Baltimore/MD
- Los Angeles/CA

The comparison supports location-level performance monitoring and helps identify differences in average customer satisfaction.

**Business value:** Call center comparisons can support further investigation into differences in service processes, customer issues, staffing, and resolution quality.

### 6. Daily Calls Trend

Call activity was analyzed using the call timestamp to understand how call volumes vary over time.

The daily trend visualization helps identify changes in activity and periods with higher call volumes.

**Business value:** Understanding call patterns can support operational planning, staffing decisions, and further investigation of unusual changes in demand.

The date axis was formatted to improve readability while retaining the chronological sequence.

### 7. Calls by State

Call volume was analyzed by state to explore geographic differences in customer support demand.

The visualization compares the number of calls associated with each state in the dataset.

**Business value:** Geographic call analysis can help identify areas with higher support demand and provide a starting point for reviewing resource allocation and regional customer needs.

## Business Insights & Recommendations

The analysis provides several useful observations from the dataset.

### 1. Customer sentiment needs attention

A total of 44 out of 70 calls (62.9%) were classified as Negative or Very Negative.

**Recommendation:** Investigate recurring complaints and common customer pain points. Review call reasons and customer feedback to identify potential causes of dissatisfaction.

### 2. Billing Questions are the largest call category

Billing Questions account for the largest call category in the analyzed dataset.

**Recommendation:** Review billing FAQs, agent scripts, and self-service guidance. Clearer explanations may help customers resolve common billing questions more efficiently.

### 3. SLA performance requires continued monitoring

A total of 53 calls (75.71%) were within SLA, while 17 calls (24.29%) were outside the Within-SLA category.

**Recommendation:** Investigate the reasons for calls falling outside the SLA target category and identify opportunities to improve handling processes and operational performance.

### 4. Customer satisfaction differs by channel

Call-Center recorded an average CSAT of 5.70, while Chatbot recorded an average CSAT of 4.82.

**Recommendation:** Review chatbot interactions to identify confusing responses, gaps in self-service guidance, and issues that require escalation to human support.

### 5. Call duration varies by issue

Service Outage calls had an average duration of approximately 31.6 minutes in the analysis.

**Recommendation:** Investigate long-duration service outage calls to understand whether resolution complexity, troubleshooting steps, or escalation processes contribute to longer handling times.

### 6. Call volume varies by state

The geographic analysis shows differences in call volume across the states represented in the dataset.

**Recommendation:** Review regional call demand alongside staffing and service requirements to support more informed resource planning.

These findings describe patterns in the analyzed dataset. Further investigation would be required to establish the underlying causes of customer dissatisfaction, SLA outcomes, and differences in call duration.

## Excel Features & Techniques Used

This project demonstrates practical Excel techniques across the data analysis workflow.

### Data Cleaning and Preparation

- Inspection of raw data
- Preparation of a structured analysis dataset
- Review of relevant data fields
- Organization of source data for PivotTable analysis
- Consistency checks for analytical categories and metrics

### Data Analysis

- PivotTables
- Aggregation and summarization
- Category-based comparisons
- Channel-level analysis
- Call center comparisons
- Sentiment analysis
- SLA performance analysis
- Time-based analysis
- Geographic analysis

### KPI Development

- Total call count
- Average customer satisfaction
- Negative sentiment percentage
- Within-SLA percentage
- Average call duration

### Data Visualization

- Horizontal bar charts
- Column charts
- Doughnut chart
- Daily trend chart
- Data labels
- Axis formatting
- Chart titles and legends
- Consistent chart formatting

### Interactive Dashboard

- Five interactive slicers
- Five KPI cards
- Seven charts
- Slicer-connected PivotTables and visualizations
- Interactive filtering by sentiment, channel, SLA status, reason, and call center
- Dashboard layout and formatting
- Business insights and recommendations

The slicers and KPI cards were tested to confirm that the dashboard responds to filter selections.

## Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Excel data cleaning and preparation
- KPI development
- Interactive slicers
- Data visualization
- Dashboard design
- Business insight generation

## Project Workflow

The complete workflow followed in this project was:

```text
Raw Call Center Data
        ↓
Data Inspection and Cleaning
        ↓
Cleaned Data Preparation
        ↓
PivotTable Analysis
        ↓
KPI Development
        ↓
Charts and Visualizations
        ↓
Interactive Dashboard
        ↓
Business Insights
        ↓
Recommendations
```

This workflow demonstrates how raw operational data can be transformed into a structured reporting tool for customer experience and call center performance analysis.

## Dashboard Features

The final dashboard includes the following components.

### KPI Cards

- Total Calls
- Average CSAT
- Negative Sentiment
- Within SLA
- Average Call Duration

### Charts

- Calls by Reason
- Average CSAT by Channel
- Customer Sentiment Distribution
- SLA Status vs Average CSAT
- Average CSAT by Call Center
- Daily Calls Trend
- Calls by State

### Interactive Filters

The dashboard contains five slicers:

- Sentiment Group
- Channel
- SLA Status
- Reason
- Call Center

These filters allow users to explore the available data and investigate specific customer sentiment categories, support channels, SLA groups, call reasons, and call center locations.

## Project Screenshots

The repository includes screenshots of the final dashboard and selected analytical outputs.

### Dashboard

Add the screenshot of the completed interactive dashboard below.

![Call Center Sentiment and Customer Satisfaction Dashboard](dashboard.png)

## Skills Demonstrated

Through this project, I practiced and demonstrated:

- Excel Data Cleaning
- Data Preparation
- PivotTable Analysis
- KPI Development
- Customer Sentiment Analysis
- Customer Satisfaction Analysis
- Call Center Performance Analysis
- SLA Performance Monitoring
- Channel Analysis
- Call Reason Analysis
- Call Duration Analysis
- Geographic Analysis
- Data Visualization
- Interactive Dashboard Development
- Business Insight Generation
- Analytical Reporting

## Learning Outcomes

This project strengthened my practical understanding of how Microsoft Excel can be used for end-to-end data analytics.

Instead of focusing only on individual formulas or charts, I worked through the complete analytical workflow, from preparing the dataset to building PivotTable-based analysis, creating visualizations, developing an interactive dashboard, and presenting business findings.

The project also helped me practice connecting slicers to dashboard components, designing KPI cards, improving chart readability, and communicating analytical findings through actionable recommendations.

## Project Status

**Completed ✅**

The workbook includes:

- Raw call center data
- Cleaned data
- PivotTable-based analysis
- KPI calculations
- Charts and visualizations
- Five interactive slicers
- Seven dashboard charts
- Five interactive KPI cards
- Business insights and recommendations
- Final interactive dashboard

## Author

**Aleeza Habib**

This project is part of my practical journey in Data Analytics, with a focus on Excel-based data preparation, analysis, visualization, and dashboard development.

⭐ If you find this project useful, feel free to explore the workbook and its interactive dashboard.
