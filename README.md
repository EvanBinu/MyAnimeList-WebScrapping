# 🎌 Anime Ranking Scraper

This project is a **Python web scraping tool** that automatically collects **anime titles, scores, and links** from [MyAnimeList](https://myanimelist.net/) using **BeautifulSoup** and **Requests**. It helps users gather up-to-date anime ranking data for research, recommendation systems, or personal analysis.

---

## 🚀 Features

* 🔍 Scrapes **anime titles**, **ratings**, and **links** from ranking pages
* 🧠 Cleans and filters data (removes `N/A` values and empty fields)
* 📊 Stores extracted data into a **structured Pandas DataFrame**
* 💾 Exports results to **CSV** or **Excel** for easy analysis
* 🧱 Uses **modular functions** for title, score, and link extraction
* ⚡ Designed with **custom headers** to avoid request blocking

---

## 🧰 Tech Stack

* **Python 3.x**
* **BeautifulSoup4** – for parsing HTML
* **Requests** – for HTTP requests
* **Pandas** – for data manipulation

---

## ⚙️ How It Works

1. Sends an HTTP request to the target MyAnimeList ranking page
2. Parses the HTML to extract:

   * Anime **title**
   * Anime **rating/score**
   * Anime **detail page link**
3. Cleans and filters the extracted data
4. Saves it into a Pandas DataFrame
5. Optionally exports it to `.csv`

---


## ⚡ Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/anime-ranking-scraper.git

# Navigate into the project
cd anime-ranking-scraper



# Run the scraper
python myanimelist.ipynb
```

---

## ⚠️ Notes

* This scraper is for **educational purposes only**.
* Always respect website **robots.txt** and **rate limits**.
* MyAnimeList’s structure may change — update selectors accordingly.

---

## 🌟 Future Improvements

* Add **genre**, and **popularity** extraction
* Integrate with a **database (SQLite or MongoDB)**
* Build a **Flask dashboard** to visualize results
* Support for **pagination** across multiple pages

---

## 🤝 Contributing

Pull requests are welcome!
If you find a bug or want to add a new feature, open an issue first to discuss what you’d like to change.

---

