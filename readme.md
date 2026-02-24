# Task 1: Data Collection and Web Scraping

## **Level 1** — Collect data from a website using web scraping techniques.

---

## 📋 Description

This task focuses on building a web scraper to collect data from a target website, process it, and store it in a structured format. You'll handle real-world challenges like pagination and dynamic content using Python's most popular scraping libraries.

---

## 🎯 Objectives

- Identify a target website and inspect its HTML structure
- Use **BeautifulSoup** and **requests** libraries to scrape data from web pages
- Store the scraped data in a structured format (e.g., CSV, JSON)
- Handle common challenges such as pagination and dynamic content

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| `requests` | Sending HTTP requests to web pages |
| `BeautifulSoup` | Parsing and extracting HTML content |
| `pandas` | Structuring and saving scraped data |

---

## 📁 Project Structure

```
task1-web-scraping/
│
├── scraper.py          # Main scraping script
├── data/
│   ├── output.csv      # Scraped data in CSV format
│   └── output.json     # Scraped data in JSON format
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone scraping-with-beautifulsoup
   cd task1-web-scraping
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   `requirements.txt`:
   ```
   requests
   beautifulsoup4
   pandas
   lxml
   ```

---

## 🚀 Usage

Run the scraper:
```bash
python scraper.py
```

The scraped data will be saved to the `data/` directory in both CSV and JSON formats.
```
## 📌 Notes

- For websites with dynamic content (JavaScript-rendered), consider using `selenium` or `playwright` in addition to `requests`
- Use proper headers (e.g., `User-Agent`) to mimic a real browser request

---

## 📄 License

This project is part of an internship/learning task. For educational use only.