# Web-Scraping-Using-BeautifulSoup-
This project is a Python-based web scraping tool that extracts quotes, authors, and tags from the Quotes to Scrape website.It demonstrates the power of web scraping using BeautifulSoup and Requests to gather data from multiple pages, process it, and store it in a CSV file.

## 🚀 Features
-Scrapes Quotes: Extracts quotes from the site.
-Author Extraction: Retrieves the author's name for each quote.
-Tag Extraction: Collects tags associated with each quote.
-Multi-page Scraping: Scrapes data from the first 10 pages of the site.
-CSV Output: Saves the data into a well-structured CSV file for further analysis.

## 🛠️ Requirements
Before running this project, make sure you have the following installed:
-Python 3.x: The latest version of Python.
-Libraries:
requests
beautifulsoup4
-You can install the required libraries using pip.

## 📥 Installation
1. Clone the repository to your local machine.
   - git clone https://github.com/Ankita780/Web-Scraping-Using-BeautifulSoup-.git
   - cd quote-scraper
2. Install the required Python libraries.
   - pip install -r requirements.txt

## ⚙️ How to Use
1. Run the scraper script by executing the following command in the terminal.
   python quote_scraper.py
2. The scraper will:
- Visit each of the first 10 pages of quotes.
- Extract the quotes, authors, and tags from each page.
- Save the data in a file named quotes_data.csv.

## 📄 Output Format
The script will generate a CSV file quotes_data.csv with the following columns:
- Quote: The actual text of the quote.
- Author: The author of the quote.
- Tags: A list of tags related to the quote.

## 🌱 Contribution
Contributions are always welcome! Feel free to submit a pull request or open an issue.

How to Contribute:
- Fork the repository.
- Clone your fork to your local machine.
- Create a new branch (git checkout -b feature-xyz).
- Make your changes and commit them (git commit -am 'Add new feature').
- Push your branch to your fork (git push origin feature-xyz).
- Create a pull request.

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
