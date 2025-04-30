# Project Name
Insights into Health Insurance Disparities Based on State-Level Political Affiliation

### Authors
* Richard Qin, Sean Lee, Kenneth Lim
* Emory University

## Project Objective
The project aims to better understand the role of state-level political parties in healthcare insurance coverage of constituents. Through the analysis, it unveils the connection between political party affiliation (Republican or Democratic) on United States residents using data from the United States Census. Moreover, the analysis provides a specific value associated with the likelihood based on the state residency’s governor political party. 

### Methods Used
* Data Exploration
* Data Visualization
* Predictive Modeling
* Inferential Statistics

### Technologies
* RStudio 
* RMarkdown
* HTML

## Project Description

Is there a strong correlation between the state-level political party and health insurance coverage? The project aims to uncover this question in-depth by exploring the Annual Social and Economic Supplement (ASEC) 2024 from the U.S. Census Bureau and the Bureau of Labor Statistics alongside the KFF dataset that provides information regarding each state’s political affiliation. The analysis first utilizes bar graphs to highlight summary statistics before using a multinomial regression analysis with household income and party affiliation. Following the multinomial regression analysis, an odds ratio value was computed for each of the given scenarios to provide more insight into the specific probabilities. However, after completing the analysis, the next issue that arose was confounding variables, which may influence the healthcare insurance coverage. Specifically, looking into employment information, the highest level of education, and an individual’s current health status can yield more insight into insurance information. With this in mind, the current U.S. Census Bureau does not provide additional information on individuals’ health status, which may require additional datasets to be imported.

## Getting Started
1. Clone this repository (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept `/my-project-EDA/data/asecpub24csv` within this repo.    
3. Data processing/analysis scripts are being kept `EDA_Code_Notebook.Rmd`

## Directory Structure
```
.
└── my-project-EDA/
    ├── data/
    │   └── asecpub24csv/
    │       ├── asec2024_ddl_pub_full
    │       ├── hhpub24.csv
    │       ├── state_political_affliation.csv
    │       └── us-state-ansi-fips.csv
    ├── EDA_Code_Notebook.html
    ├── EDA_Code_Notebook.Rmd
    ├── EDA_Project.Rproj
    ├── forest_plot_health_insurance.png
    ├── README.md
    ├── renv
    └── renv.lock
```

#### Other Members:
- [Kenneth Lim](https://github.com/LimK2025)
- [Sean Lee](https://github.com/hmseanlee)

## Contact
* Richard Qin: richard.qin@emory.edu
* Kenneth Lim: kenneth.lim@emory.edu
* Sean Lee: sean.lee@emory.edu


