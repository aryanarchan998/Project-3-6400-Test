# Project 3: Exploring Keyword Co-occurrence Networks in Scientific Publications

## Overview
This project analyzes keyword co-occurrence patterns in scientific publications using Python. The dataset contains article titles and up to 12 keywords per article. A weighted adjacency matrix was created to measure how often keywords appear together in the same article, and this matrix was converted into a weighted network using NetworkX.

## Files in this Repository
- `notebook.ipynb` - Jupyter/Colab notebook with all code, outputs, and explanations
- `report.md` - short written report interpreting the results
- `data/keywords_data.csv` - dataset used for the project

## Main Tasks Completed
1. Loaded and previewed the dataset
2. Extracted keyword data and built a symmetric weighted adjacency matrix
3. Converted the adjacency matrix into a weighted network
4. Computed node degree and node strength
5. Identified the top 10 nodes by degree and strength
6. Identified the top 10 node pairs by edge weight
7. Created a scatter plot of degree vs strength

## Tools Used
- Python
- pandas
- networkx
- matplotlib
- Google Colab

## Notes
The dataset file is stored in the `data` folder, and the notebook uses a relative file path.