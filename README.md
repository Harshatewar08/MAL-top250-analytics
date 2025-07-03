# 🎌 MyAnimeList Top 250 Anime – Web Scraping & Dashboard 📊

This project extracts and analyzes the Top 250 anime from [MyAnimeList.net](https://myanimelist.net/topanime.php) using Python and BeautifulSoup, then visualizes the insights through an anime-themed Power BI dashboard.

---

## 🚀 Project Highlights

- 🔍 **Web Scraping** with `requests` and `BeautifulSoup`
- 📄 **Data Cleaning & Structuring** with `pandas`
- 🧠 **Type & Episode Parsing** via custom logic
- 📈 **Insightful Visualizations** (Top Scores, Type Distribution, Episode Bins)
- 🎨 **Power BI Dashboard** with anime-style aesthetic and slicer-driven interactivity

---

## 📦 Technologies Used

| Tool            | Purpose                     |
|-----------------|-----------------------------|
| Python          | Core scripting & scraping   |
| BeautifulSoup   | HTML parsing                |
| pandas          | Data structuring & export   |
| Power BI        | Interactive visualization   |

---

## 🗃️ Features

- ✅ Scrapes Top 250 anime titles from MAL across multiple pages
- ✅ Parses rank, title, score, type (TV/Movie/OVA), and episode count
- ✅ Groups anime into episode bins: Short, Medium, Long
- ✅ Power BI dashboard includes:
  - Top 10 Anime by Score
  - Score by Type
  - Scatterplot: Episodes vs Score
  - Donut Chart: Type Distribution
  - Slicer for Type

---

## 🧠 Key Insights

- 🎯 Short anime (< 12 episodes) often rank surprisingly high.
- 🎞️ Movies maintain consistent scores across fewer episodes.
- 🌀 TV shows dominate volume but vary more in score range.

