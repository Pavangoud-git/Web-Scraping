# 📚 Books Web Scraping Project

## 📌 Project Overview

This project uses **Python, Requests, BeautifulSoup, and Pandas** to scrape detailed book information from the *Books to Scrape* website. The scraper collects data from all 50 pages, extracts product details, and stores the results in a structured CSV dataset for further analysis.

## 🎯 Objectives

* Scrape book information from multiple pages.
* Extract product details such as title, price, rating, category, and availability.
* Create a structured dataset for analysis.
* Demonstrate real-world web scraping and data collection skills.

## 🛠️ Technologies Used

* Python
* Requests
* BeautifulSoup4
* Pandas
* LXML
* Google Colab / Jupyter Notebook

## 📂 Data Collected

The scraper extracts:

* Book ID
* Title
* UPC
* Product Type
* Price (Excluding Tax)
* Price (Including Tax)
* Tax
* Availability
* Number of Reviews
* Rating
* Category
* Description
* Product URL

## 🔄 Project Workflow

### 1. Collect Product URLs

* Crawl all 50 catalog pages.
* Extract links for every book.

### 2. Scrape Detailed Information

* Visit each product page.
* Extract product metadata.
* Capture ratings, prices, descriptions, and categories.

### 3. Store Data

* Create a Pandas DataFrame.
* Export the dataset to CSV format.

## 📊 Output

The script generates:

```text
books_complete_dataset.csv
```

Containing detailed information for approximately **1,000 books**.

## 📁 Project Structure

```text
Books-Web-Scraping/
│
├── web_scraping.py
├── books_complete_dataset.csv
├── README.md
└── requirements.txt
```

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Books-Web-Scraping.git
cd Books-Web-Scraping
```

Install dependencies:

```bash
pip install requests beautifulsoup4 pandas lxml
```

## ▶️ Run the Project

```bash
python web_scraping.py
```

The script will:

1. Scrape all book URLs.
2. Extract detailed product information.
3. Generate the CSV dataset.

## 📈 Skills Demonstrated

* Web Scraping
* Data Collection
* HTML Parsing
* Data Cleaning
* Data Storage
* Automation
* Python Programming

## 🚀 Future Improvements

* Add multithreading for faster scraping.
* Export data to SQL databases.
* Schedule automated scraping.
* Build dashboards using Power BI or Tableau.
* Perform EDA on the scraped dataset.

## 👤 Author

**Pavan Goud**

⭐ If you found this project useful, consider starring the repository and connecting with me on LinkedIn.
