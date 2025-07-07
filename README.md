# 🎬 IMDb SQL Mini Project

This project analyzes an IMDb-style movie database using SQL concepts in a Kaggle Notebook.

## 📌 Project Overview
Using a mock SQLite `.db` file uploaded to Kaggle, I performed SQL queries to uncover insights from three interconnected tables:
- `movies`
- `ratings`
- `genres`
The goal was to practice:
- SQL `JOIN` operations
- Window functions like `RANK()`
- Aggregations (`AVG`, `COUNT`, `GROUP BY`)
- Subqueries and filtering

---

## 🔍 Key Analyses Performed
- 🎖️ Top 3 rated movies per genre (`RANK()` + `PARTITION BY`)
- 🧮 Average movie rating per decade
- 🗳️ Most voted movie each year
- 🔗 Merging movie details with ratings and genres using `JOIN`s
- 🏷️ Most common and highest-rated genres

---

## 🛠️ Tech Used
- SQL (SQLite syntax)
- Python (Pandas, SQLite3)
- Kaggle Notebooks

---

## 📁 Dataset
- Format: `.db` SQLite file (uploaded to Kaggle)
- ⚠️ This is a mock dataset created purely for learning and practice.
- Not affiliated with or sourced directly from IMDb.

---

## 📎 Links
- 🔗 [View Notebook on Kaggle](# *(https://www.kaggle.com/code/tanishthaghosh365/analyzing-imdb-movie-data-with-sql)*
- 🔗 [View Dataset on Kaggle](#) *(https://www.kaggle.com/datasets/tanishthaghosh365/imdb-sql-project/settings?inquiry-id=inq_aa7maMw2Wr7MoYfZkcyPANH4rTVS&reference-id=27690116&subject=27690116&status=approved&fields%5Bname-first%5D%5Btype%5D=string&fields%5Bname-first%5D%5Bvalue%5D=&fields%5Bname-middle%5D%5Btype%5D=string&fields%5Bname-middle%5D%5Bvalue%5D=&fields%5Bname-last%5D%5Btype%5D=string&fields%5Bname-last%5D%5Bvalue%5D=&fields%5Baddress-street-1%5D%5Btype%5D=string&fields%5Baddress-street-1%5D%5Bvalue%5D=&fields%5Baddress-street-2%5D%5Btype%5D=string&fields%5Baddress-street-2%5D%5Bvalue%5D=&fields%5Baddress-city%5D%5Btype%5D=string&fields%5Baddress-city%5D%5Bvalue%5D=&fields%5Baddress-subdivision%5D%5Btype%5D=string&fields%5Baddress-subdivision%5D%5Bvalue%5D=&fields%5Baddress-postal-code%5D%5Btype%5D=string&fields%5Baddress-postal-code%5D%5Bvalue%5D=&fields%5Baddress-country-code%5D%5Btype%5D=string&fields%5Baddress-country-code%5D%5Bvalue%5D=&fields%5Bbirthdate%5D%5Btype%5D=date&fields%5Bbirthdate%5D%5Bvalue%5D=&fields%5Bemail-address%5D%5Btype%5D=string&fields%5Bemail-address%5D%5Bvalue%5D=&fields%5Bphone-number%5D%5Btype%5D=string&fields%5Bphone-number%5D%5Bvalue%5D=%2B916380889262&fields%5Bidentification-number%5D%5Btype%5D=string&fields%5Bidentification-number%5D%5Bvalue%5D=&fields%5Bidentification-class%5D%5Btype%5D=string&fields%5Bidentification-class%5D%5Bvalue%5D=&fields%5Bselected-country-code%5D%5Btype%5D=string&fields%5Bselected-country-code%5D%5Bvalue%5D=IN&fields%5Bphone%5D%5Btype%5D=string&fields%5Bphone%5D%5Bvalue%5D=)*

---

## 🧠 Learnings
This project helped me strengthen my skills with:
- Window functions like `RANK()`
- Writing clean, efficient SQL queries
- Structuring SQL projects for sharing

---

> 💬 Feel free to fork the notebook or suggest improvements!
