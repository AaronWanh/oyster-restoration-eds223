# Homework Assignment 3

In this assignment, we explore the historical redlining in LA county and analyze if other factors such as particulate matter 2.5 concentrations, low life expectancy, and low income percentages are driving factors to a high Home Owners’ Loan Corporation grade. We will also observe if there is a correlation between redlining grade categories to the frequency of bike and pedestrian accidents. The transportation crash data we chose to use was collected between 2020 and 2025 which allows us to see modern environmental injustice affected by historical safety disparities among neighborhoods in Los Angeles. 

## Inside the Repo:

This repository contains a data folder that holds environmental and demographic information for the U.S. at the census tract and block group levels by EJScreen. Additional files were included such as a csv file that contains bike and pedestrian accidents and a json file that contains the HOLC grades of Los Angeles neighborhoods. It also has a PDF of the metadata for this dataset and explains how the data was collected and in what ways were they expressed. However we have a gitignore file to prevent the large dataset from bloating the repository. The main code and graphs are within the quarto document hw2.qmd. Finally the README.md file is a summary of what is contained inside the repository and what it accomplishes. 

```text
C:.
│   .gitignore
│   hw2.qmd
│   README.md
│   
└───data
    │   Crashes.csv
    │   ejscreen-tech-doc-version-2-2.pdf
    │   EJSCREEN_2023_BG_Columns.xlsx
    │   mapping-inequality-los-angeles.json
    │   
    └───EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
```

## Authors/Collaborators:
- Aaron Wang
- Annie Adams https://github.com/annieradams 


## Citations:
* U.S. Environmental Protection Agency (EPA), 2023. EJScreen Technical Documentation.
* Nelson, R. K., Winling, L., Marciano, R., Connolly, N., et al. (n.d.). Mapping inequality: Redlining in New Deal America. Digital Scholarship Lab, University of Richmond. https://dsl.richmond.edu/panorama/redlining/
* California Highway Patrol. (n.d.). Statewide Integrated Traffic Records System (SWITRS) [Data set]. https://tims.berkeley.edu/
