# Indian Political Meta Ads Analysis

> A Power BI dashboard companion for exploring political advertising activity on Meta platforms in India.

This repository contains the project dataset, exploratory notebooks, and dashboard previews. The descriptions below cover only the two pages shown in the supplied dashboard screenshots.

## Dashboard

The dashboard screenshots are collected in the [Dashboard](Dashboard) folder.

### Overview

![Overview dashboard page](Dashboard/Overview.png)

The **Overview** page provides a high-level view of campaign scale, spend, and reach.

- KPI cards show **Avg Spend (2.48K)**, **Total Reach (729M)**, **Total Ads (10K)**, **Max Spend (1.00M)**, **Total Politicians (2K)**, **CPM (33.41)**, and total **Spend (24M)**.
- A bar chart ranks **Total Financial Spend by page_name**.
- A line chart tracks **Total Financial Spend by Year**.
- A donut chart breaks down **Total Financial Spend by Platform**.
- Date and page-name slicers support exploration. The captured view spans **10 November 2024 to 26 March 2026**.

### Objective: audience targeting and efficiency

![Objective dashboard page](Dashboard/Objective.png)

The **Objective** page focuses on targeting patterns and the relationship between spend and reach.

- Gender, age-group, and delivery-date slicers provide audience and period filtering.
- A donut chart shows **Total Financial Spend by top_targeted_age**.
- A scatter chart, **Spend vs. Reach Efficiency by Target Age**, compares total financial spend with total reach and includes a time playback control.
- The page notes describe comparing age-segment targeting and identifying campaigns that achieve high reach relative to spend.

## Repository contents

- `Dashboard/` — Power BI dashboard screenshots.
- `data/` — the Meta political ads dataset and data dictionary.
- `notebooks/` — cleaning, EDA, objectives, and conclusion notebooks.
- `images/` — existing notebook-output images.
- `docs/` — methodology and limitations placeholders.

## Power BI report file

The Power BI report source (`.pbix`) should be stored in the `Dashboard/` folder when it is available for upload. It is not represented by a substitute file in this repository.

## License

This project is distributed under the [MIT License](LICENSE).
