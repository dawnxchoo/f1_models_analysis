# F1 Winners Analysis (1950-2025)

A data analysis project exploring Formula 1 race winners from 1950 to 2025, focusing on team dominance patterns and historical trends.

## Overview

This project analyzes historical F1 race winners data to understand:
- Which teams have been most dominant in F1 history
- How team dominance has evolved over time
- Patterns in race wins across different eras

## Dataset

The analysis uses the [Winners Formula 1 1950 to 2025](https://www.kaggle.com/datasets/julianbloise/winners-formula-1-1950-to-2025?resource=download) dataset from Kaggle, which includes:
- Race dates and locations
- Grand Prix names and circuits
- Winner names and teams
- Race times and laps
- Data spanning from 1950 to 2025

## Analysis Features

### 1. Team Dominance Analysis
- Top 10 most successful F1 teams by total race wins
- Simplified team naming for consistent tracking across engine/sponsor changes

### 2. Historical Trends
- 5-year rolling average of team performance
- Visualization of how dominance has shifted between teams over time

## Key Findings

- **Ferrari** leads with 249 race wins
- **McLaren** follows with 200 wins
- **Mercedes** has 130 wins (modern era dominance)
- **Red Bull** has 124 wins (recent dominance)

## Requirements

```python
pandas
numpy
seaborn
matplotlib
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/f1_models_analysis.git
cd f1_models_analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/julianbloise/winners-formula-1-1950-to-2025?resource=download) and place the CSV file in the project directory

4. Open and run the Jupyter notebook:
```bash
jupyter notebook data_analysis_winners_f1.ipynb
```

## Usage

The notebook is structured in clear sections:
1. Data loading and exploration
2. Team name standardization
3. Dominance analysis with visualizations
4. Time-series analysis with rolling averages

Simply run the cells sequentially to reproduce the analysis.

## Visualizations

The project includes:
- Bar charts showing top teams by total wins
- Line plots showing team dominance evolution over time
- Custom color palette matching actual F1 team colors

## Data Note

You'll need to download the dataset separately from Kaggle (see link above) as it's not included in this repository.

## License

This project is open source and available for educational purposes.

## Acknowledgments

- Data source: [Kaggle - Winners Formula 1 1950 to 2025](https://www.kaggle.com/datasets/julianbloise/winners-formula-1-1950-to-2025?resource=download)
- Analysis focuses on understanding historical patterns in Formula 1 racing

