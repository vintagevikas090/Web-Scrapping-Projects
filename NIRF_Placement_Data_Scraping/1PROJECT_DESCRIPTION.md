# 📊 NIRF Placement Data Scraper (2017–2023)

This project automates the extraction of placement data from the **NIRF (National Institutional Ranking Framework)** website for use in a larger **placement analysis project**.

Using **Python (Selenium, Requests, pdfplumber)**, the script downloads and parses college-level placement PDFs from the **2021 and 2024 NIRF rankings**, covering academic years **2017–18 to 2022–23**. The extracted data is cleaned and saved as a single CSV file for further use in Power BI or other analysis tools.

---
🚀 Project Overview 

| Step            | Task                                                                                                     |
| --------------- | -------------------------------------------------------------------------------------------------------- |
| 🌐 Scraping     | Automated download of placement PDFs from NIRF ranking pages (2021 & 2024) using `Selenium` & `requests` |
| 📄 Extraction   | Parsed "Placement & Higher Studies" tables from each PDF using `pdfplumber`                              |
| 🧹 Cleaning     | Standardized year-wise placement data and merged entries for overlapping colleges                        |

---

## 🔧 Tools & Libraries

* `Selenium` – dynamic scraping of NIRF ranking pages
* `requests` – fetching college PDF links
* `pdfplumber` – extracting tabular data from PDFs
* `pandas` – data cleaning and transformation

---

## 📁 Output

A structured dataset that will be used as the core input for:

* 📊 Placement trend analysis
* 📈 College-wise and year-wise comparisons (in Power BI)

---
