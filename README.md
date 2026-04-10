# R Data Visualization Reports

This repository contains two **RStudio data analysis reports** created using **R Markdown**. The reports analyze trends in **data science salaries** and **consumer shopping behavior** through exploratory data analysis and visualizations.

## Repository Structure

```
├── reports
| ├── DataVizProject250389.Rproj
| ├── ds_salaries.csv
| ├── ds_salaries_report.Rmd
| ├── ds_salaries_report.html
| ├── shopping_trends.csv
| ├── shopping_trends_report.Rmd
| └── shopping_trends_report.html
└── README.md
```

## Reports

### Data Science Salaries

Analyzes salary distributions and employment characteristics in the data science job market.

Key insights include:

* Median salary around **$135k**
* Strong salary progression by **experience level**
* **Remote work increases with seniority**
* Geographic location (especially **US/CA**) significantly affects compensation

### Shopping Trends

Explores consumer purchasing behavior across demographics, promotions, and payment methods.

Key insights include:

* **Clothing** is the most purchased category
* Typical transactions range **$20–$90**
* Balanced usage of payment methods and promo codes
* Broad customer age range (**18–70**)

## Data

Both datasets are included in the repository because they are **small (<0.5 MB)** and have become difficult to locate online due to changes in the original Kaggle sources.

## Usage

1. Open `DataVizProject250389.Rproj` in **RStudio**
2. Open either `.Rmd` file
3. Click **Knit → HTML** to regenerate the reports

## Tools

* R
* RStudio
* R Markdown
* tidyverse / ggplot2
