# DATA-ANALYTICS

Working notebooks from a graduate data-analytics course: the full path from
getting data out of a website to fitting, validating and explaining a model.

This is coursework and practice, not a library or an application. It is
published as a record of the ground covered, and the notebooks are readable
end to end — each one carries its data, its output, and the reasoning between.

## What is here

### Getting data

| notebook | what it covers |
|---|---|
| `Basic Web Scraping Lecture Code` · `Web Scraping Lecture Part 2` | requests + BeautifulSoup fundamentals |
| `Selenium Intro - Web Scraping Using Selenium` | Driving a real browser for pages that need one |
| `Scrape LinkedIn Using Selenium And Beautiful Soup in Python` | Combining both against a JS-heavy site |
| `Selenium Project - Scraping Top Grossing Movies Data` | End-to-end scrape to dataset |
| `WebScrapingExample_KeepingTabsonCongress` | Scraping legislative records |
| `Getting Data with the Last.fm API` | The other route — a documented API instead of a scrape |
| `Text Wrangling and Regex` | Cleaning what comes back |

### Preparing it

`Data Preprocessing` · `05-Feature Engineering` · `02-Random Variable`

### Modelling

| notebook | method |
|---|---|
| `02-ConstantModel` | The baseline every other model has to beat |
| `Regression for House Price Prediction` | Linear regression, applied |
| `01-Cross-Validation and Regularization` | Model selection; where overfitting shows up |
| `ML_Algorithms_Decision_Tree` · `ML_Algorithms_KNN` · `ML_Algorithms_Random_Forest` | Classifiers, compared |
| `03-Clustering` | Unsupervised |

### Optimization

`Optimization Modelling in Python - SciPy, PuLP, and Pyomo` — the same problem
posed three ways, which is the useful part: the modelling language is a choice,
not a given.
`Balanced_Diet_Problem` — the classic LP formulation.
`Case Study - WCR Prescriptive Analysis (Optimization)`

### Case studies and EDA

`Case Study - LEGO` · `EDA Example 2 - WCR_case` ·
`EDA Example 3 - Call Center Case` · `visualization1` · `visualization2`

### Data

`adult` · `artists` · `inspections` · `world_bank` · `utilities` · `dugongs` ·
`edInc` · `stint_data` · `tinydata` · `call center data set` · `diet`

## Running

```bash
pip install pandas numpy scikit-learn matplotlib seaborn statsmodels \
            beautifulsoup4 requests selenium scipy pulp pyomo
jupyter notebook
```

Selenium notebooks need a matching browser driver on PATH. Everything else runs
against the CSV and Excel files committed alongside.

## A note on the filenames

Several files carry ` (1)` / ` (2)` suffixes — download artifacts from when they
were saved, not versions. `Scrape LinkedIn Using Selenium And Beautiful Soup in
Python (1)` and `(2)` are byte-identical duplicates and one can be deleted.
