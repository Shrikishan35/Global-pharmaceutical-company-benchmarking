# Global Pharmaceutical Company Benchmarking

### Eli Lilly and Company vs Pfizer Inc. | FY2021–FY2025

A comparative pharmaceutical industry analysis examining financial performance, product revenue, portfolio composition, growth trends and business positioning using Python, Pandas and Power BI.

---

## Project Overview

This project analyses two global pharmaceutical companies, **Eli Lilly and Company** and **Pfizer Inc.**, over the five-year period FY2021–FY2025.

The objective is to evaluate their financial performance, product portfolios, revenue growth and product revenue concentration using company-reported data from SEC filings and annual reports.

Python and Pandas were used for data extraction, cleaning, transformation and analysis. Power BI was used to develop interactive dashboards and communicate business insights.

## Project Objectives

- Compare five-year financial performance and revenue growth.
- Analyse profitability, R&D expenditure and operating cash flow.
- Examine product-level revenue trends and portfolio composition.
- Evaluate product revenue concentration and major growth contributors.
- Identify competitive positioning, business risks and strategic considerations.

## Tools & Technologies

| Tool | Application |
|---|---|
| Python | Data extraction and analysis |
| Pandas | Data cleaning and transformation |
| Jupyter Notebook | Analytical workflow |
| SEC Filings & Annual Reports | Financial and product revenue data |
| Power BI | Interactive dashboards and visualisation |
| Microsoft PowerPoint | Business insights and recommendations |

## Project Structure

```text
Global-Pharmaceutical-Company-Benchmarking/
│
├── README.md
│
└── US_Healthcare_Benchmarking/
    ├── data/
    │   ├── Eli_Lilly/
    │   └── Pfizer/
    │
    ├── notebooks/
    │   ├── 01_SEC_Data_Extraction.ipynb
    │   └── 02_Pfizer_Data_Extraction.ipynb
    │
    ├── power bi/
    │   └── US_Healthcare_project.pbix
    │
    ├── presentations/
    │   └── Pharma_Benchmarking_Presentation_Layout_v2.pptx
    │
    └── Screenshot/
        ├── Financial dashboard.png
        ├── Portfolio_Mix.png
        └── Top10_Products_FY2025.png
```

## Dashboard Analysis

### Dashboard 1 – Financial Performance

- Five-year revenue comparison.
- Revenue CAGR analysis.
- Net profit margin comparison.
- R&D expenditure trends.
- Operating cash flow comparison.

### Dashboard 2 – Product & Portfolio Analysis

- Eli Lilly therapeutic-area revenue mix.
- Pfizer commercial portfolio revenue mix.
- Top 10 revenue-generating products.
- Top product revenue share.
- Top five product revenue concentration.

## Key Findings

### Eli Lilly

- Revenue increased from approximately **$28.32 billion in FY2021 to $65.18 billion in FY2025**.
- Five-year revenue CAGR was approximately **23.17%**.
- FY2025 net profit margin was approximately **31.67%**.
- Mounjaro and Zepbound together contributed approximately **56.01% of FY2025 total revenue**.
- Cardiometabolic products accounted for approximately **73.98% of FY2025 revenue**.

### Pfizer

- Revenue decreased from approximately **$81.29 billion in FY2021 to $62.58 billion in FY2025**.
- Five-year revenue CAGR was approximately **-6.33%**.
- FY2025 net profit margin was approximately **12.42%**.
- COVID-related product sales significantly influenced revenue during FY2021–FY2022.
- Oncology and Specialty Care increased their shares of the commercial portfolio between FY2021 and FY2025.

## Product Revenue Concentration – FY2025

| Metric | Eli Lilly | Pfizer |
|---|---:|---:|
| Top product revenue share | 35.24% | 13.01% |
| Top five revenue concentration | 77.50% | 47.92% |

These indicators highlight differences in product revenue concentration and portfolio diversification.

## Methodology

1. Extracted financial and product revenue information from SEC filings and company annual reports.
2. Cleaned and transformed the extracted datasets using Python and Pandas.
3. Validated extracted revenue totals against company-reported figures.
4. Calculated revenue growth, financial indicators and product concentration.
5. Imported prepared datasets into Power BI.
6. Developed comparative dashboards and interpreted the results.
7. Summarised business implications and strategic recommendations in a presentation.

## Data Sources

- U.S. Securities and Exchange Commission (SEC) – Company filings and XBRL data.
- Eli Lilly annual reports and financial disclosures.
- Pfizer annual reports and financial disclosures.

## Limitations & Considerations

- Product disclosures and classifications may change across reporting years.
- Missing product disclosures are not automatically treated as zero.
- Eli Lilly therapeutic-area categories and Pfizer commercial portfolio categories are different classification systems and are not directly equivalent.
- Pfizer R&D expenditure excludes acquired in-process research and development (IPR&D) in this analysis.
- Small differences between extracted and reported revenue totals may arise from rounding.
- Historical financial performance does not guarantee future results.

## Project Deliverables

- Python data extraction and analysis notebooks.
- Company-level CSV datasets.
- Two Power BI dashboards.
- Five-slide comparative business presentation.

## Author

**Shrikishan B**  
M.Pharm – Pharmaceutics  
Area of Interest: Pharmaceutical & Healthcare Analytics

*Independent portfolio project | FY2021–FY2025*
