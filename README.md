# How to use this repo:
## Part 1: Data Extraction and Exploration
### Objective
Using the World Bank Documents & Reports API, produce an animated chart showing the evolution of the number and the percentage of documents by country and year for documents on “Implementation Completion Report Review”, published from January 1st, 2019 to April 15th, 2025
### Instructions
For Part 1, refer to the notebook 03_notebooks/plot_part_1.ipynb and run all. 
## Part 2: Natural Language Processing and Text Analysis
### Objective
Produce an analysis of your choice linking the M&E rating to text features from the document section (“M&E Design, Implementation, & Utilization”). The analysis attempts to identify key textual patterns, sentiment/topic indicators, or technical terminology that correlate with specific ratings. 
### Instructions
1. Refer to the notebook 03_notebooks/etl_txt.ipynb to download all documnents and generate the csv containing all data for the analysis on 2 and 3
2. For Tf-idf analysis for key textual patterns linked to specific ratings, run notebook 03_notebooks/nlp_patterns.ipynb
3. For sentiment analysis, run 03_notebooks/nlp_s_analysis.ipynb
