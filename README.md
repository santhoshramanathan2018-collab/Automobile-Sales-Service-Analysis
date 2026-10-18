# Automobile Sales and Service Analysis

A data analytics project focused on Indian automobile sales and after-sales service records. The project combines data preparation and analysis with an interactive Power BI report to help explore sales performance, service demand, and customer billing patterns.

## Project Information

- **Project title:** Automobile Sales and Services Analysis
- **Student:** Santhosh R
- **Register number:** 44111004
- **Department:** Computer Science and Engineering
- **Training:** Professional Training I
- **Guide:** Ms. Sandhiya S
- **Project presentation date:** 14 September 2026
- **Tools:** Microsoft Power BI, Python, Pandas, Google Colab, Excel

## Repository Structure

```text
Automobile-Sales-Service-Analysis/
├── 01_Dataset/
│   └── India_Automobile_Sales_Service_Analysis_Dataset.xlsx
├── 02_Data_Cleaning/
│   └── README.md
├── 03_PowerBI/
│   └── Automobile_Sales_Service_Analysis.pbix
├── 04_Project_Report/
│   └── Automobile_Sales_Service_Analysis_Presentation.pptx
├── 05_Certificate/
│   └── Data_Analytics_Certificate_Santhosh_R.jpg
└── README.md
```

## Abstract

The project analyzes Indian automobile sales and service records. It aims to turn operational data into useful business insights, including high-performing regions, service-cost averages, and frequent vehicle maintenance needs.

## Problem Statement

Automotive businesses generate substantial data from vehicle sales and after-sales services. Manually reviewing raw records can make it difficult for dealerships to identify sales patterns, monitor customer billing, and understand service-center workload.

## Objectives

1. Identify Indian states and vehicle categories with high sales revenue.
2. Determine frequent service requests and calculate average customer billing.
3. Present the results in an interactive Power BI dashboard.
4. Support exploration using filters such as year, state, and fuel type where available in the report.

## Workflow

1. **Dataset:** Start with the Excel dataset in `01_Dataset/`.
2. **Preparation:** Review missing values, data types, duplicates, and inconsistent categories before analysis. Record any changes in `02_Data_Cleaning/`.
3. **Analysis:** Use Python/Pandas or Power BI measures to aggregate sales and service metrics.
4. **Visualization:** Open the `.pbix` file in Power BI Desktop to inspect or continue editing the dashboard.
5. **Reporting:** Refer to the project presentation in `04_Project_Report/`.

## Results Reported in the Project Presentation

The accompanying presentation reports the following findings:

- **Sales leaders:** Karnataka, West Bengal, and Kerala were reported as generating the highest estimated sales value.
- **Service trend:** “Accident Repair” was reported as the most frequent service type.
- **Average service bill:** Approximately ₹9,204.

These figures are reproduced from the project presentation and should be validated against the final dataset and dashboard before being treated as definitive results.

## Future Scope

- Add forecasting for sales trends.
- Explore predictive maintenance and service scheduling.
- Expand the dashboard with additional time, region, vehicle-category, and customer-service comparisons where the data supports them.

## How to Use

1. Download or clone this repository.
2. Open the Excel dataset to review the available columns and records.
3. Open `03_PowerBI/Automobile_Sales_Service_Analysis.pbix` in Power BI Desktop.
4. If prompted, update the data-source path to the local Excel file in `01_Dataset/`.
5. Refresh the report and verify measures, visuals, and filters.

> **Compatibility note:** Power BI Desktop is primarily a Windows application. On macOS, use an available Windows environment or Power BI Service in a browser where the required editing features are supported. A `.pbix` file may not be fully editable directly in a Mac browser.

## Data and Privacy Note

Check the dataset's source, license, and attribution requirements before redistributing it publicly. Do not commit passwords, access tokens, private customer information, or other confidential data.

## References

- Microsoft Power BI documentation and DAX reference
- Python and Pandas documentation
- Dataset source details should be added here after verifying the original source and license
