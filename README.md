# Meta Ad Performance Dashboard

## Project Overview

This project is a Power BI dashboard developed to analyse Meta advertising performance across Facebook and Instagram.

The dashboard provides a clear view of campaign reach, engagement, conversions, audience behaviour, and marketing efficiency. It helps marketing teams understand how ads are performing across different platforms, audience segments, time periods, locations, and ad formats.

The main purpose of this project is to convert raw advertising data into meaningful business insights that can support campaign optimisation and better marketing decisions.

---

## Business Problem

Marketing teams often run multiple paid advertising campaigns across different platforms and audience groups. Without a centralised reporting dashboard, it becomes difficult to understand:

- Which platform is performing better
- Which audience segment is engaging more
- Which ad types are driving stronger results
- Whether users are moving from impressions to clicks and purchases
- Where advertising budget can be optimised

This dashboard solves that problem by combining campaign, ad, user, and event-level data into one interactive Power BI report.

---

## Dataset

The project uses four main CSV datasets:

| Table | Description |
|---|---|
| `ad_events.csv` | Event-level data such as impressions, clicks, shares, comments, likes, and purchases |
| `ads.csv` | Ad-level details including platform, ad type, target gender, target age group, and target interests |
| `campaigns.csv` | Campaign-level information such as campaign name, start date, end date, duration, and budget |
| `users.csv` | User demographic information such as gender, age, country, location, and interests |

The dataset used in this project is sample data created for learning and portfolio purposes.

---

## Tools Used

- Power BI
- Power Query
- DAX
- Data Modelling
- CSV Data Files
- Marketing Analytics
- Business Intelligence
- Data Visualisation

---

## Data Model

The dashboard uses a star schema style data model.

- `ad_events` is used as the main fact table.
- `ads`, `campaigns`, and `users` are used as dimension tables.
- A calendar/date table is used for time-based analysis.
- A dynamic measure table is used to switch metrics across dashboard visuals.

![Data Model](Images/Data%20Model.png)

---

## Key KPIs

The dashboard tracks the following KPIs:

- Impressions
- Clicks
- Shares
- Comments
- Purchases
- Engagements
- Click Through Rate
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Budget
- Average Budget per Campaign

---

## Dashboard Features

- Facebook and Instagram performance comparison
- Dynamic KPI selection
- Campaign filtering
- Gender-based performance analysis
- Age group performance analysis
- Country-level geographic analysis
- Monthly calendar heat map
- Weekly trend analysis by ad type
- Hourly trend analysis
- Ad type performance matrix

---

## Dashboard Preview

### Facebook Dashboard

![Facebook Dashboard](Images/Facebook%20Dashboard.png)

### Instagram Dashboard

![Instagram Dashboard](Images/Instagram%20Dashboard.png)

---

## Key Insights

- Facebook generated stronger overall reach with 216K impressions and 25.4K clicks.
- Instagram showed a slightly higher CTR at 11.86%, compared to Facebook at 11.76%.
- Both platforms achieved strong engagement rates above 13%.
- Purchase rate was low on both platforms, showing that the lower funnel needs improvement.
- Video and Stories ads performed strongly in terms of conversion and engagement efficiency.
- Audience engagement was stronger among younger users and female audience segments.
- Campaign activity showed stronger performance during afternoon and evening periods.

---

## Recommendations

- Improve landing pages to reduce drop-off after users click ads.
- Use retargeting campaigns for users who clicked or engaged but did not purchase.
- Shift more budget towards high-performing ad formats such as Video and Stories.
- Focus campaign targeting towards high-performing audience groups.
- Schedule campaigns during afternoon and evening time slots for stronger engagement.
- Monitor purchase rate and conversion rate regularly, not only impressions and clicks.

---

## Repository Structure

```text
Meta-Ad-Performance-Dashboard/

├── Dashboard pdf/
│   └── Meta Ad Performance Dashboard.pdf
│
├── Data/
│   ├── ad_events.csv
│   ├── ads.csv
│   ├── campaigns.csv
│   └── users.csv
│
├── Documents/
│   ├── Business Requirements Document.pdf
│   ├── Dashboard Insights.pdf
│   └── Domain Knowledge Document.pdf
│
├── Images/
│   ├── Data Model.png
│   ├── Facebook Dashboard.png
│   └── Instagram Dashboard.png
│
└── README.md
```

---

## How to Use

1. Open the `Dashboard pdf` folder.
2. View the exported Power BI dashboard PDF.
3. Explore the `Data` folder to review the source CSV files.
4. Open the `Documents` folder to understand the business requirements, domain knowledge, and dashboard insights.
5. Review the dashboard screenshots in the `Images` folder for a quick visual overview of the project.

---

## Skills Demonstrated

- Power BI dashboard development
- Data cleaning and transformation using Power Query
- Data modelling with related tables
- DAX measure creation
- KPI design
- Marketing analytics
- Business intelligence reporting
- Dashboard storytelling
- Business insight generation

---

## Project Learnings

This project helped me strengthen my understanding of Power BI reporting, marketing analytics, data modelling, and business-focused dashboard design.

It also improved my ability to translate raw advertising data into meaningful insights and practical recommendations for marketing decision-making.

---

## Future Improvements

- Add cost-based KPIs such as CPC, CPM, and ROAS.
- Add landing page performance data.
- Add campaign-level budget pacing analysis.
- Add month-over-month and week-over-week performance comparison.
- Add drill-through pages for campaign-level investigation.
- Add Power BI service publishing and interactive dashboard sharing.
