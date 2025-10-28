**Books to Scrape – Web Scraper**
This project is a Python web scraper that extracts book information such as title, price, availability, rating, and full product link from the demo website https://books.toscrape.com/
It uses Requests and BeautifulSoup for web scraping and Pandas for data storage.

**Features**

Scrapes all pages of the Books to Scrape website.
Extracts the following details for each book:
📖 Title
💰 Price
✅ Availability
⭐ Rating
🔗 Full product link (absolute URL)
Stores the extracted data in a CSV file (products.csv).

**Technologies Used**

**Python 3.x**
**Requests** – For fetching web pages
**BeautifulSoup (bs4)** – For parsing HTML content
**Pandas** – For saving data in CSV format
**urllib.parse** – For joining relative URLs with base URLs

**Example Output**

| Title                | Price  | Availability | Rating | Full_Link                                                                                                                                              |
| -------------------- | ------ | ------------ | ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| A Light in the Attic | £51.77 | In stock     | Three  | (https://books.toscrape.com/catalogue/a-light-in-the-attic_1000/index.html) |
| Tipping the Velvet   | £53.74 | In stock     | One    | (https://books.toscrape.com/catalogue/tipping-the-velvet_999/index.html)    |
