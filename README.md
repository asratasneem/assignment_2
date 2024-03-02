# Assignment_2
Assignment 2: Gene Half-Life Analysis
Author:
Asra Tasneem Shaik

# Date:
03-01-2024

# Programming Language & Version:
Python [3.8]

# Dependencies:
pandas 
numpy 
scipy 

# Input:
CSV file: DecayTimecourse.csv containing gene expression time course data.

# Short Script Description:
This script performs an analysis on gene expression time course data to estimate half-lives of genes using exponential decay modeling. It reads the input CSV file, cleans the data, fits an exponential decay curve to each gene's expression data, calculates the half-life for each gene, identifies genes in the top and bottom 10 percentiles of half-lives, and saves the results to separate CSV files.

# Output Files:
half_life_df.csv: Contains all genes with their corresponding half-lives.
top_lives.csv: Contains genes in the top 10 percentile of half-lives.
bottom_lives.csv: Contains genes in the bottom 10 percentile of half-lives.
gProfiler_top10%.png , gProfiler_bottom10%.png : The biological importance of these genes in yeast was investigated by doing a functional enrichment analysis utilizing online resources like g:Profiler, after genes with high and low half-lives were identified. 
Following the analysis, PNG files uploaded provides the results.
