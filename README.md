# Zomato Restaurant Intelligence Dashboard

A data analytics and visualization platform built to generate actionable insights on restaurant performance and customer experience using Zomato restaurant data.

This project integrates raw data with interactive visual reporting to help analysts and business users evaluate metrics like ratings, cuisine trends, delivery options, and geography-based patterns.

## Table of Contents

- **Project Overview**
- **Key Features**
- **Repository Structure**
- **Getting Started**
- **Data Requirements**
- **Report Overview**
- **How to Use**
- **Contributing**
- **License**

## Project Overview

The goal of this dashboard is to convert unstructured or semi-structured Zomato restaurant data into business intelligence that supports decision-making in restaurant management, market research, and customer engagement. It focuses on:

- Restaurant ratings and trends
- Distribution of cuisines and service attributes
- Geographic performance of restaurant listings
- Customer behavior signals through ratings and reviews

This dashboard aligns with analytics practices seen in similar interactive dashboards built with Power BI and related BI tools.

## Key Features

- Interactive visual analytics of restaurant performance
- Metrics for ratings distribution, cuisine popularity, and location segmentation
- Filterable visuals for region or attribute focused exploration
- Exportable reports in PDF and Power BI formats

## Repository Structure
Zomato-Restaurant-Intelligence-Dashboard/
├─ Report_Zomato.pbix # Power BI dashboard file
├─ Zomato Restaurant Intelligence Dashboard.pdf # PDF version of the report
├─ Zomato Bangalore Restarunts Data/ # Source dataset folder
├─ .gitattributes # Git attributes
└─ README.md # This documentation


## Getting Started

### Prerequisites

To explore and modify the dashboard locally you will need:

- **Power BI Desktop** (latest version recommended)
- Optional: Any BI viewer that supports `.pbix` format

### Setup

1. Clone the repository  
   ```bash
   git clone https://github.com/Vishalkompalli/Zomato-Restaurant-Intelligence-Dashboard.git
2. Open Power BI Desktop
3. Load Report_Zomato.pbix
4. Update the data source references to point at your local dataset files
5. Interact with the visuals and filters

## Data Requirements
Place your dataset files (e.g., restaurant listings, ratings, location metadata) inside the dataset folder. 

Typical attributes expected by the dashboard include:
- Restaurant Name
- Cuisines
- Aggregate Ratings
- Delivery/Booking options
- Votes or Reviews

Datasets like this are commonly used in Zomato analytics dashboards to drive interactive reports. 

## Report Overview

The dashboard delivers insights across multiple analytical dimensions:

- Overall Metrics – Total restaurants, average ratings, service availability
- Cuisine Trends – Popularity and distribution of food types
- Rating Distribution – Breakdown of restaurant ratings
- Geography – City or region level segmentation

Visualizations help identify performance patterns, outliers, and opportunities for service improvement.

## How to Use

- Use slicers to filter by city, cuisine, or rating range
- Drill down into visuals to explore sub-segments
- Export pages to PDF for reporting or executive summaries

## Contributing

Improvements are welcome:
- Add detailed data schema documentation
- Provide sample datasets for easier replication
- Enhance visuals or introduce predictive analytics measures
- Submit issues and pull requests using standard GitHub workflows.

## License

This repository does not currently include an open source license. To facilitate reuse, consider adding a license such as MIT, Apache-2.0, or Creative Commons.
