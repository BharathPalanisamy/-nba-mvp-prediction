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

## Requirements

```bash
pandas
numpy
scikit-learn
plotly
openpyxl
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

Open and run the Jupyter notebook `which_nba_team_wins.ipynb` to:
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

## Business Intelligence Integration

The notebook exports data in multiple formats for BI tools:
- CSV format for Tableau
- JSON format for Power BI

## License

This project is released under the MIT License. See the LICENSE file for details.

## Contributing

Feel free to fork the project and submit pull requests with improvements.
