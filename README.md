# 🏅 Olympic Medalist Dataset (1896–2024)

This repository contains structured data on Olympic Games medalists — both **Summer and Winter Olympics** — spanning over a century, from the first modern Olympics in **1896** to the latest games in **2024**.

## 📁 Repository Structure

- `all_olympic_medalists.csv`  
  → Combined data from all Olympic Games (Summer and Winter)

- `by_year/`  
  → Contains individual CSV files for each Olympic edition named using the format:  
  `<year>_<host_city>.csv` (e.g., `2012_London.csv`)

## 📑 Column Descriptions

Each file contains the following columns:

| Column         | Description                                                           |
| -------------- | --------------------------------------------------------------------- |
| `season`       | The Olympic season: `"Summer"` or `"Winter"`                          |
| `year`         | The year the Olympics took place                                      |
| `medal`        | The medal awarded: `"Gold"`, `"Silver"`, or `"Bronze"`                |
| `country_code` | The 3-letter IOC country code (e.g., `USA`, `JPN`, `FRA`)             |
| `country`      | Country name as written in the official records                       |
| `athletes`     | Names of athlete(s) who won the medal, separated by comma if multiple |
| `games`        | Full official name of the Olympics edition (e.g., `2024 Paris`)       |
| `sport`        | Sport category (e.g., Athletics, Swimming, Figure Skating)            |
| `event_gender` | Gender category of the event (e.g., `Men`, `Women`, `Mixed`)          |
| `event_name`   | Specific name of the event (e.g., `100m`, `Ice Hockey`)               |

## 📦 Data Source

All data was extracted from:

**📍 OlympAnalyt Portal**  
🔗 http://www.olympanalyt.com/OlympAnalytics.php

Please note this dataset is intended **for educational and research purposes only**.

## 📊 Potential Use Cases

- Medal trend analysis by country
- Gender distribution across sports
- Historical athlete achievements
- Visual storytelling or infographics

## ✍️ Attribution

If you use this dataset in publications, visualizations, or derivative datasets, please credit:

> "Data retrieved from [OlympAnalyt.com](http://www.olympanalyt.com) and compiled by the Olympics Medalist Dataset project."

---

📬 For questions or suggestions, feel free to open an issue or contribute via pull requests.
