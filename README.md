# NBA MVP Prediction Analysis

This project analyzes NBA player statistics to predict potential MVP candidates for future seasons. It uses machine learning techniques to analyze both regular season and playoff performance data.

## Features

- MVP candidate prediction using Random Forest model
- Analysis of key performance metrics
- Interactive visualizations using Plotly
- Integration with Business Intelligence tools (Power BI, Tableau)
- 5-year future predictions

## Dataset

The analysis uses two main datasets:
- `Regular_Season.csv`: Regular season statistics
- `Playoffs.csv`: Playoff performance data

### Data Processing
The data goes through several preprocessing steps:
1. Initial cleaning (handling missing values, removing duplicates)
2. Feature engineering:
   - Per game statistics calculation
   - Advanced metrics (TS%, eFG%, etc.)
   - Player efficiency ratings
3. Integration of regular season and playoff data
4. Normalization of statistics within each season

### Model Features
Key statistics used in the prediction:
- Traditional stats (points, rebounds, assists per game)
- Advanced metrics (true shooting %, effective field goal %)
- Playoff performance indicators
- Year-over-year improvements
- Team success metrics

## Requirements

```bash
pandas>=2.3.2
numpy>=2.3.2
scikit-learn>=1.7.1
matplotlib>=3.7.1
seaborn>=0.12.2
plotly>=5.18.0
xgboost>=1.7.6
openpyxl>=3.1.2
jupyter>=1.0.0
```

## Installation

1. Clone the repository
```bash
git clone https://github.com/[your-username]/nba-which-team-wins-prediction.git
cd nba-which-team-wins-prediction
```

2. Create and activate a virtual environment
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

3. Install required packages
```bash
pip install pandas numpy scikit-learn plotly openpyxl
```

## Usage

Open and run the Jupyter notebook `nba_mvp_analysis.ipynb` to:
- Load and process NBA statistics
- Train the prediction model
- Generate MVP predictions
- Create interactive visualizations
- Export data for BI tools

## Visualizations

The project includes several interactive visualizations:
1. MVP Score Timeline
2. Player Statistics Comparison
3. Feature Importance Analysis


## License

This project is released under the MIT License. See the LICENSE file for details.

## Contributing

Feel free to fork the project and submit pull requests with improvements.
