# VCT-Champions-2023-Data-Visualization
This repository contains the analysis and visualization of data from the Valorant Champions Tour (VCT) 2023, focusing on player performance, agent selection, team compositions, and map strategies. The project uses basic data visualization techniques to derive insights for competitive gameplay optimization.  

## Contents
- **`Analysis.pdf`**: Project documentation, including theoretical considerations, analysis, and conclusions.
- **`VALO_Yr_2023.xlsx`**: Dataset containing match and player performance data.
- **`Valo_DV_Final.ipynb`**: Jupyter Notebook with the complete analysis and visualizations.

## Key Features
- **Player Performance Metrics**: Radial graphs and histograms to evaluate individual player performance (kills, deaths, assists, ratings).
- **Agent Usage**: Bar charts for agent pick rates and meta-defining strategies.
- **Team Analysis**: Tree maps and pie charts to analyze team compositions and ratings.
- **Map Trends**: Bar plots showing map pick rates and map-specific optimizations.
- **Interactive Visualizations**: Dynamic charts and graphs built with Plotly for enhanced exploration.

## Setup and Usage
1. Clone the repository.
2. Install dependencies.
3. Open the notebook.
4. Update dataset paths as necessary and run the cells to generate visualizations.

## Datasets
The dataset includes fields like:
- `match_id`, `player`, `agent`, `rating`, `kill`, `death`, and `assist`.

Original data source: [Kaggle - VCT 2023 Dataset](https://www.kaggle.com/).

## Future Directions
- Develop an interactive team builder for optimized compositions.
- Incorporate patch notes to analyze meta shifts.
- Explore larger datasets for longitudinal insights.
- More Tweaks can be done to get much better Ideal team composition, as the current one is much basic.
- Agent kills and hotspot could be done with more indept datasets.