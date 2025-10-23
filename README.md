

---

# News Headlines Web Scraper

## **Objective**

Scrape top headlines from a news website and save them to a text file. This automates the collection of current news headlines for analysis, monitoring, or personal use.

---

## **Tools & Libraries**

* **Python 3.x**
* **requests** – to fetch HTML content via HTTP GET requests
* **BeautifulSoup (bs4)** – to parse and extract data from HTML

---

## **Installation**

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Navigate to the project folder:

```bash
cd news-scraper
```

3. Install dependencies:

```bash
pip install requests beautifulsoup4
```

---

## **Usage**

1. Open `news_scraper.py` in your editor.
2. Update the URL variable if you want to scrape a different news website:

```python
url = "https://www.bbc.com/news"
```

3. Run the script:

```bash
python news_scraper.py
```

4. Check the generated `headlines.txt` file in the project folder. It will contain all the extracted headlines, numbered sequentially.

---

## **How It Works**

1. Sends an HTTP GET request to the news website.
2. Parses the HTML content using BeautifulSoup.
3. Finds all headline elements (e.g., `<h3>` tags).
4. Extracts the text and cleans it.
5. Saves all headlines into a text file (`headlines.txt`).

---

## **Key Concepts Learned**

* HTTP GET requests
* Handling HTTP headers and User-Agent
* HTML parsing and data extraction
* File handling in Python
* Exception handling with `try-except`

---

## **Interview Questions Covered**

1. What is a GET request?
2. How do you install external packages in Python?
3. What is a User-Agent in HTTP?
4. What is `soup.find_all()` used for?
5. What are the risks of web scraping?
6. Difference between `id` and `class` in HTML
7. What is an HTML tag?
8. What does `.text` return in BeautifulSoup?
9. What is a try-except block?
10. What are HTTP status codes?

---

## **Output Example**

`headlines.txt`:

```
1. UK government announces new climate plan
2. Stock markets soar amid tech rally
3. Scientists discover new exoplanet
...
```

---
