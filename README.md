# Superman IMDb Reviews: Web Scraping & Summarization

## This Project
This project scrapes *Superman* IMDb reviews using **Selenium** and generates concise summaries with **transformer-based NLP models** (T5, BART, PEGASUS, and LED). It includes custom text preprocessing such as contraction expansion and lemmatization, producing a clean, summarized dataset ready for analysis.

---

## Folder Structure

### 1_WebScraping
- **1.1_DataOutput** : Contains raw and cleaned review datasets (CSV).  
- **1.2_Notebook** : Jupyter notebooks for scraping, cleaning, and exploring the data from the imdb website.

### 2_Summarizing
- **2.1_DataOutput** : Contains summarized review datasets.  
- **2.2_Notebook** : Jupyter notebooks for generating summaries using transformer models.
- 
---

## Key Features

### Web Scraping
- Scrapes IMDb reviews for *Superman* using **Selenium**.
- Handles dynamic content, "See more" buttons, and spoilers.
- Exports cleaned review data for summarization.

### Summarization
- Implements four transformer models: **T5, BART, PEGASUS, LED**.
- Custom preprocessing: contraction expansion, lemmatization, and whitespace cleanup.
- Generates concise, abstractive summaries of reviews.
- Comparative analysis of model outputs.
