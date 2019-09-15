# Coursera-Course-3
Coursera Course 3 - Getting and Cleaning Data

This repository contains:
- run_analysis.R script
- Codebook

The run_analysis.R script will do the following:
- Check the current directory for a zip file called "course3.zip"
- If the zip file exists, the script assumes that its contents have already
  been extracted to the current working directory.
- If the zip file does not exist, the script will download the zip file 
  using the URL provided in the Project instructions. It will then extract all
  contents of the zip file to the current working directory.
- The relevant data will be read into R, and merged and transformed into 
  2 datasets:
  - tidy_data - this is the dataset corresponding to item 4 in the Project 
    instructions which is the merged and transformed data
  - tidy_data_averages - this is the dataset corresponding to item 5 in the
    Project instructions and gives average figures for each variable provided
    in tidy_data, summarised by Subject and Activity
- No other output is provided - all temporary variables are removed.