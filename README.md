
# 📊 Data Analysis Projects

This repository contains two Python projects focused on data extraction and analysis:

1. **Weather Data Extraction Tool** - Fetches real-time weather data using APIs
2. **Demand Inventory Analysis** - Analyzes product demand and inventory trends

---

## 🌦️ Weather Data Extraction Tool

A Python script that fetches real-time weather data for any city or your current location using public APIs.

### Features
- City-based weather lookup
- Auto-location detection
- Multi-day forecast display
- Clean text and JSON output formats

### Technologies
- Python 3
- `requests` library
- wttr.in API
- ipinfo.io API

[View Weather Extraction Code](/weather_extractor.py)

---

## 📈 Demand Inventory Analysis

Analysis of product demand and inventory data over time (June-August 2023).

### Dataset Overview
- **File**: `demand_inventory.csv`
- **Time Period**: 2023-06-01 to 2023-08-01
- **Variables**:
  - Date
  - Product_ID
  - Daily Demand
  - Inventory Level

### Key Insights
- Tracks inventory depletion of product P1 over 2 months
- Shows daily demand fluctuations
- Identifies stockout occurrences (inventory = 0)

### Sample Data

| Date       | Product_ID | Demand | Inventory |
|------------|------------|--------|-----------|
| 2023-06-01 | P1         | 51     | 5500      |
| 2023-06-02 | P1         | 141    | 5449      |
| ...        | ...        | ...    | ...       |
| 2023-07-17 | P1         | 100    | 0         |

[View Full Dataset](/demand_inventory.csv)

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/data-analysis-projects.git
   cd data-analysis-projects
Install dependencies:


pip install requests pandas matplotlib
📊 How to Run
Weather Tool

python weather_extractor.py
Inventory Analysis

import pandas as pd

df = pd.read_csv('demand_inventory.csv')
print(df.describe())
📂 Project Structure
data-analysis-projects/
├── weather_extractor.py       # Weather data script
├── demand_inventory.csv       # Inventory dataset
├── inventory_analysis.py      # Analysis script (optional)
├── README.md                  # This file
└── requirements.txt           # Dependencies
🤝 Contributing
Suggestions for additional analyses welcome

Report issues with the datasets

Ideas for visualization improvements

📌 Note: Replace your-username with your actual GitHub username in the clone URL.

This README:
1. Clearly separates both projects
2. Includes proper Markdown formatting for tables and code blocks
3. Provides direct links to files
4. Shows sample data from the CSV
5. Includes setup and usage instructions
6. Maintains a professional yet approachable tone

You can copy-paste this directly into your GitHub repository's README.md file. The formatting will render perfectly on GitHub.
