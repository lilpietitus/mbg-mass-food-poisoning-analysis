# Analysis of Mass Food Poisoning Cases Associated with the Free Nutritious Meals (MBG) Program

## Overview

This project presents a compilation and analysis of publicly documented mass food poisoning cases associated with the Free Nutritious Meals (MBG) Program in Indonesia.

The analysis aims to examine the **scale, temporal patterns, and geographical distribution** of documented cases from **September 2024 to September 2026**.

The collected data was compiled, cleaned, processed, and visualized to examine how the number of reported victims and the locations of documented cases changed throughout the observation period.

## Research Questions

This project seeks to answer the following questions:

* How did the number of reported victims change over time?
* When was the highest number of victims recorded?
* How were the documented cases geographically distributed?
* Which provinces recorded the highest numbers of victims?
* How many victims were documented in publicly available records during the observation period?

## Data Source

The primary data source is publicly available documentation from:

**Wikipedia Indonesia — Daftar kasus keracunan massal makan siang gratis**

https://id.wikipedia.org/wiki/Daftar_kasus_keracunan_massal_makan_siang_gratis

The data was independently compiled and processed for this project.

**Observation period:** September 2024 – September 2026

**Last data update:** September 12, 2026

## Data Cleaning

The collected data was cleaned and restructured to make it suitable for analysis.

The cleaning process included:

* Standardizing date formats
* Standardizing location names
* Checking and handling incomplete data
* Checking for potential duplicate records
* Converting victim counts into a consistent numerical format
* Structuring the data into a consistent tabular format
* Grouping records by time period and geographical area for analysis

## Analysis

The analysis examines the documented cases from several perspectives.

### Temporal Trends

The number of reported victims was analyzed by month to identify changes and patterns throughout the observation period.

Key findings include:

* The first recorded case in the dataset occurred in September 2024, involving 7 victims.
* In September 2025, 6,173 victims were recorded.
* In October 2025, the number increased to 7,036 victims, the highest monthly figure in the dataset.
* Reports continued to be documented through September 2026, with 3,644 victims recorded in that month.

### Geographical Distribution

The locations of individual incidents were analyzed to examine the geographical distribution of documented cases across Indonesia.

The documented cases were found across various regions, with the highest concentration of points appearing on Java, followed by Sumatra and Sulawesi.

Documented cases also occurred outside Indonesia's major population centers, including Maluku Barat Daya and Papua.

### Distribution by Province

Based on the compiled dataset, the provinces with the highest recorded numbers of victims were:

| Province                     | Recorded Victims |
| ---------------------------- | ---------------: |
| Central Java                 |           11,537 |
| West Java                    |            6,249 |
| East Java                    |            5,869 |
| Special Region of Yogyakarta |            4,304 |
| East Nusa Tenggara           |            1,806 |

These figures represent the number of victims recorded in the dataset during the observation period.

## Annual Summary

| Year  | Recorded Victims |
| ----- | ---------------: |
| 2024  |                7 |
| 2025  |           20,393 |
| 2026* |           19,951 |

*2026 data covers January through September only.

Overall, the dataset contains **40,351 reported victims** who experienced symptoms of food poisoning across various incidents associated with the MBG Program between September 2024 and September 2026.

## Visualization

The data was visualized using **Tableau**.

### Dashboard

[MBG Food Poisoning Cases in Indonesia — Data Visualization](https://public.tableau.com/shared/JBRQTM56K?:display_count=n&:origin=viz_share_link)

The visualization includes temporal trend analysis, geographical distribution, and comparisons of recorded victims across regions.

## Article

The findings were also developed into a data storytelling article on Medium:

**Behind Indonesia's Free Nutritious Meals Program: More Than 40,000 Reported Food Poisoning Victims in Two Years**

https://medium.com/@razahra

The article discusses the temporal patterns, geographical distribution, and overall scale of the documented cases.

## Limitations

This dataset has several limitations that should be considered when interpreting the results.

First, the data was compiled from publicly available documentation on Wikipedia Indonesia. Therefore, the dataset depends on the completeness and accuracy of the available documentation and its subsequent updates.

Second, the figure of **40,351 victims** represents the number of victims identified and compiled from publicly available documentation in this dataset. It should not be interpreted as an estimate of the total number of victims that occurred in Indonesia.

Third, differences in the number of recorded victims between provinces cannot be directly interpreted as differences in risk levels. A risk assessment would require additional comparison data, such as the number of MBG recipients or the number of meal portions distributed in each province.

Fourth, the dataset may change if new reports are published or if existing information is corrected or updated.

## Project Structure

```text
mbg-mass-food-poisoning-analysis/
│
├── README.md
│
├── data/
│   ├── raw_data.xlsx
│   └── cleaned_data.xlsx
│
└── visualization/
    └── tableau/
```

## Tools

* **Microsoft Excel** — data collection, cleaning, and data processing
* **Tableau** — data visualization

## Key Takeaway

This project demonstrates a data analysis workflow that transforms publicly available documentation into a structured dataset, followed by data cleaning, analysis, and visualization to identify temporal and geographical patterns.

The findings were then communicated through data visualization and data storytelling.
