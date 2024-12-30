# FIFA Player Data Analysis and Clustering Project

## Project Overview
This project involves a comprehensive analysis of FIFA 20 player data to extract meaningful insights and group players based on their attributes. By leveraging various data analysis and clustering techniques, the project explores trends, relationships, and clusters in the player dataset.

### Dataset
The dataset used in this project contains:
- Information on **18,278 players**
- **104 attributes** per player, including personal details (age, nationality, club, etc.), football skills, physical characteristics, and contractual details

### Objectives
1. **Data Analysis:** Perform exploratory data analysis (EDA) to uncover trends and relationships between player attributes.
2. **Clustering Players:** Use clustering algorithms to group players based on their skills and attributes.
3. **Insight Extraction:** Generate actionable insights from the data for football strategies and player evaluations.

## Features of the Analysis
- Relationship exploration:
  - The correlation between **player age** and movement/reaction.
  - The influence of **height** on weight.
  - Trends between **overall score** and **potential score**.
  - The relationship between **player value** and **wages**.
  - Impact of **contract duration** on release clauses.
- Clustering techniques:
  - **K-Means Clustering**
  - **DBSCAN Clustering**
  - **Hierarchical Clustering**
- Performance evaluation using **Silhouette Scores** to determine the quality of clusters.

## Tools and Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas, NumPy: Data manipulation and analysis
  - Matplotlib, Seaborn: Data visualization
  - Scikit-learn: Clustering algorithms and metrics

## Key Results
- **K-Means Clustering:** Best performance with 4 clusters and a Silhouette Score of ~0.616.
- **DBSCAN Clustering:** Similar performance with a Silhouette Score of ~0.619. Effective for identifying irregularly shaped clusters.
- **Hierarchical Clustering:** Lower Silhouette Score (~0.51), indicating less compact clusters compared to K-Means and DBSCAN.
- Actionable trends and insights derived from EDA.
  
