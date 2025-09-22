# Predictive NBA Contract Valuation Model 🏀💰

This project explores the use of data-driven models to evaluate NBA player contracts.  
By combining advanced stats, player performance, injuries, salaries, team valuations, and jersey sales, we aim to build a holistic framework for identifying undervalued and overvalued contracts.

---

## 📂 Repository Structure

- **Data Sources**
  - `NBA Advanced Stats(2019 - 2024).csv` – Advanced efficiency metrics
  - `NBA Per Game Stats(2019 - 2024).csv` – Regular season per-game data
  - `NBA Per Game PLAYOFF Stats(2019 - 2024).csv` – Playoff performance
  - `NBA Player Injury Stats(2019 - 2024).csv` – Injury history
  - `NBA Salaries(2019-2024).csv` – Salary data
  - `NBA_Team_Valuations_2024.csv` – Market values of NBA teams
  - `Top_NBA_Jersey_Sales.csv` – Popularity & brand value proxy
  - `nba_players.db` / `yourfile.db` – Database files for structured access

- **Notebooks**
  - `nba_database.ipynb` – Database creation & integration
  - `player_data.ipynb` – Player statistics preprocessing
  - `player_injury.ipynb` – Injury analysis
  - `player_salaries.ipynb` – Salary and contract modeling
  - `jersey_sales.ipynb` – Impact of popularity on valuation
  - `team_market_values.ipynb` – Team financial metrics

- **Other Files**
  - `requirements.txt` – Python dependencies
  - `README.md` – Project documentation

---

## ⚙️ Tech Stack

- **Python 3.9+**
- **Pandas, NumPy, Scikit-learn** – Data wrangling & modeling
- **Matplotlib, Seaborn** – Data visualization
- **SQLite** – Player and contract database
- **Jupyter Notebook** – Analysis and prototyping

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/SarthakJain2/PredictiveNBAContractValuationModel.git
   cd PredictiveNBAContractValuationModel
2. Install Dependencies
    ```bash
    pip install -r requirements.txt
3. Open and Run the Notebooks
Example:  
    - Run `nba_database.ipynb` to build the database  
    - Explore `player_salaries.ipynb` for contract valuation analysis  

---

## 📊 Insights

- Relationship between player stats and contract size  
- Effects of injuries on player valuation  
- Influence of team financial health and market value  
- Popularity factors (jersey sales) on contract negotiations  

---

## 🌟 Future Work

- Deploy an interactive dashboard (Streamlit or Flask)  
- Add predictive deep learning models for player valuation  
- Automate data refresh with current NBA seasons  
