# oncology-research-landscape
Exploratory analysis of 36,214 oncology-related publications (2015–2025) using OpenAlex, Python, and Tableau to explore publication trends, citations, open access, cancer types, and institutional participation.

# Oncology Research Landscape | 2015–2025

## Project Overview

This project explores the global landscape of cancer research publications from 2015 to 2025 using OpenAlex data.

The analysis examines publication patterns across cancer types and research topics, citation impact, and the relationship between open access status and citation counts. An interactive Tableau dashboard was developed to communicate key findings through data visualization.

## Research Questions

- Which cancer types receive the greatest research attention?
- What are the most frequently studied topics in oncology?
- How are citation counts distributed across publications?
- How do citation counts differ between open-access and non-open-access publications?

## Dataset

- **Source:** OpenAlex
- **Time period:** 2015–2025
- **Number of records:** 36,250
- **Key variables:** Publication title, publication year, citation count, and open access status

## Methodology

1. Data collection and preparation
2. Exploratory data analysis using Python in Google Colab
3. Analysis of publication patterns by cancer type and research topic
4. Comparison of citation counts by open access status
5. Statistical testing using the Mann–Whitney U test
6. Interactive dashboard development using Tableau

## Key Findings

- **36,250** cancer-related research records were analyzed.
- **26,842 publications (74.0%)** were open access, compared with 9,408 non-open-access publications (26.0%).
- Breast cancer had the highest publication count among the cancer categories examined, with 2,954 records, followed by lung cancer (2,271) and colorectal cancer (1,287).
- Prognosis and survival was the most frequent research topic identified, followed by metastasis and chemotherapy.
- Citation counts differed statistically between open-access and non-open-access publications (Mann–Whitney U test, p < 0.001).

These results describe patterns in the analyzed dataset and do not establish that open access status causes higher citation counts.

## Tools & Technologies

- Python
- Pandas
- Statistical analysis
- Google Colab
- Tableau
- OpenAlex

## Dashboard

![Oncology Research Dashboard](Oncology%20research%20landscape.png)
*Dashboard link and screenshots to be added.*

## Repository Structure

```text
oncology-research-landscape/
├── README.md
├── notebooks/
│   └── oncology_analysis.ipynb
├── dashboard/
│   └── dashboard_screenshot.png
└── data/
    └── README.md
```

## Author

**Afsaneh Sadat Makeh**

Health Data Analyst | Oncology Research & Bibliometrics
