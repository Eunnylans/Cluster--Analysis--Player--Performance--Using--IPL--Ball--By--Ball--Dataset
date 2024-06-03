# IPL Player Performance Analysis
Cluster Analysis of Player Performance using Ball-by-Ball Dataset

## Overview
This project aims to analyze player performance in the Indian Premier League (IPL) using ball-by-ball dataset. The dataset includes various features such as match ID, inning number, over number, ball number, batsman, bowler, runs scored, wickets taken, etc. The goal is to develop a data-driven solution to identify and categorize top-performing batsmen in the IPL.

## Data Description
- **id**: Unique Match ID as per ESPNCricinfo.
- **inning**: Inning Number.
- **over**: Over Number.
- **ball**: Ball Number.
- **batsman**: Batsman on strike.
- **non_striker**: Batsman at non-striker end.
- **bowler**: Bowler.
- **batsman_runs**: Runs scored off bat.
- **extra_runs**: Extra runs conceded.
- **total_runs**: Total runs scored in the ball.
- **non_boundary**: Indicates if runs were scored through boundaries.
- **is_wicket**: Indicates if the delivery resulted in a wicket.
- **dismissal_kind**: Type of dismissal.
- **player_dismissed**: Player who got dismissed.
- **fielder**: Fielder involved in the dismissal.
- **extras_type**: Type of extras.
- **batting_team**: Batting team.
- **bowling_team**: Bowling team.

## Objective
The primary objective of this project is to identify top-performing batsmen in the IPL based on their performance metrics. This is achieved through clustering algorithms such as k-means, hierarchical clustering, and DBSCAN.

## Methodology
1. **Data Preprocessing**: Cleaning and preprocessing the dataset to handle missing values, encoding categorical variables, etc.
2. **Feature Engineering**: Extracting relevant features that can be used to evaluate player performance.
3. **Clustering Algorithms**:
   - *K-means*: Partitioning the dataset into clusters based on similarity of player performance metrics.
   - *Hierarchical Clustering*: Agglomerative clustering to form a hierarchy of clusters.
   - *DBSCAN*: Density-based clustering to identify clusters of varying shapes and sizes.
4. **Evaluation**: Evaluating the clustering results to identify top-performing batsmen clusters.
5. **Visualization**: Visualizing the clusters and their characteristics to gain insights into player performance.

## Results
The clustering algorithms help in categorizing batsmen based on their performance metrics. This provides insights into which players exhibit similar patterns of performance, thus aiding in the identification of top-performing batsmen in the IPL.


## Usage
1. Clone the repository.
2. Run the Jupyter Notebook to execute the analysis.

## Future Work
- Incorporate additional features such as player form, match conditions, etc., for more robust analysis.
- Explore other clustering algorithms and techniques for better performance categorization.
- Extend the analysis to include bowler performance and team dynamics.

# Cluster--Analysis--Player--Performance--Using--IPL--Ball--By--Ball--Dataset
