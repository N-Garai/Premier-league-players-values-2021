# Premier League Players Values 2021

This repository contains a Jupyter Notebook analyzing Premier League football players' market values for the 2021 season using a dataset sourced from Kaggle.

## Dataset Overview

The dataset includes comprehensive player and performance statistics for the 2020-2021 English Premier League season.

### Typical Columns

While exact columns may vary, common fields include:
- **Player**: Full name of the football player
- **Club**: Club/team (2021)
- **Position**: Playing position (e.g. Midfielder, Forward, etc.)
- **Market Value**: Estimated market value (typically in millions GBP or EUR)
- **Date of Birth / Age**
- **Nationality**
- **Appearances / Starts**
- **Minutes Played**
- **Goals**
- **Assists**
- **Passes Attempted** and **Pass Accuracy (%)**
- **Expected Goals (xG)** and **Expected Assists (xA)**
- **Yellow Cards / Red Cards**
- **Height** (sometimes included)

See the Kaggle dataset and notebook for the full set of columns.

## Analysis and Insights

The notebook (`Players'_value_2021.ipynb`) performs:
- Data cleaning and exploratory data analysis
- Market value distributions and ranking
- Top valued players and clubs
- Relationship between player performance and market value
- Demographic analysis (age, nationality, position)
- Correlation studies (e.g. do goals or minutes played affect market value?)

## Getting Started

To run this project:
1. Download the dataset from [Kaggle](https://www.kaggle.com/code/ngarai/players-value-2021-premier-league) (or your preferred data source)
2. Open `Players'_value_2021.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells to reproduce the analysis and visualizations.

## License

This project is licensed under the [Apache License 2.0](LICENSE).

---

*Data source: Kaggle, various Premier League stats datasets.*

```
References:
- Data and column exploration: [Kaggle Players' Value 2021](https://www.kaggle.com/code/ngarai/players-value-2021-premier-league), [EPL player value analysis](https://gist.github.com/Hasban-Fardani/0919466284260d0371d43fc7dd435f83)