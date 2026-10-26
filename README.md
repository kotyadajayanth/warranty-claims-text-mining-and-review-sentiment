# HanuAi ML Assessment

Two tasks, one folder each. Open this folder in VS Code, install the requirements, and open the notebooks.

```
pip install -r requirements.txt
playwright install chromium
```

## Task 2: Advanced EDA and Text Mining (finished and run)
`task2_eda_text_mining/`
- `Task2_EDA_Text_Mining.ipynb`: EDA, cleaning, text mining, issue classification, trends, clustering. Run All from inside that folder.
- `outputs/task2_tagged_dataset.csv` and `.xlsx`: the data with extracted tags, issue category and clusters.
- `outputs/figures/`: all charts.
- `Task2_Stakeholder_Report.docx` and `.pdf`: report for stakeholders.

## Task 1: Web Scraping and Sentiment Analysis (you must run the scraper)
`task1_scraping_sentiment/`
- `Task1_Scraping_Sentiment.ipynb`: scraper (Playwright), sentiment (VADER) and aspect tagging.
- `Task1_Report_TEMPLATE.docx`: anti-scraping section is written; the results sections are orange placeholders to fill from your run.

Steps: choose a bestbuy.ca product with 50 or more reviews, paste its URL into `PRODUCT_URL`, run the self-test cells, run `inspect_page(PRODUCT_URL)` if needed, set `RUN_SCRAPER = True`, then run the rest. Outputs appear in `task1_scraping_sentiment/outputs/`.

## Honest notes
- The Task 1 scraper could not be tested on the live site; its parsing and sentiment code was tested on invented text only.
- Task 2 tags come from transparent rules, with limits listed in the notebook and report.
