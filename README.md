
# Hacker News Scraper

Welcome to the Hacker News Scraper! This Python script is designed to fetch and display the top stories from Hacker News based on the number of votes. The script scrapes data from the Hacker News website and generates a list of the most popular stories.

## 🛠️ Features

- Scrapes the latest stories from Hacker News.
- Combines data from multiple pages for a comprehensive list.
- Filters stories with more than 99 votes.
- Displays the top stories sorted by vote count.

## 📦 Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library

You can install the required libraries using pip:

```bash
pip install requests beautifulsoup4
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Run the Script

Execute the Python script to fetch and display the top Hacker News stories:

```bash
python scraper.py
```

### 3. Output

The script will print the top Hacker News stories to the console. Each story includes a title, link, and the number of votes.

## 📜 Code Overview

- **Imports**:
  - `requests` for making HTTP requests.
  - `BeautifulSoup` from `bs4` for parsing HTML.
  - `pprint` for pretty-printing the output.

- **Fetching Data**:
  - The script retrieves data from two pages of Hacker News using `requests.get`.

- **Parsing HTML**:
  - `BeautifulSoup` is used to parse the HTML and extract story links and votes.

- **Processing Data**:
  - Stories are filtered and sorted based on the number of votes.

- **Output**:
  - The top stories are printed in a readable format.

## 🧩 Example Output

```plaintext
{'title': 'Top Story Title',
 'link': 'https://news.ycombinator.com/item?id=12345',
 'votes': 150}
```

## 📚 Additional Information

- **Hacker News**: A social news website focusing on computer science and entrepreneurship.
- **BeautifulSoup**: A Python library for parsing HTML and XML documents.

## 👨‍💻 Contributing

Feel free to contribute to this project by submitting issues, creating pull requests, or suggesting new features. Your contributions are always welcome!


---

Enjoy exploring the top Hacker News stories! 🚀

