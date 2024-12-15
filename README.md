# BRFSS Data Analysis Project

## Overview
This project explores the Behavioral Risk Factor Surveillance System (BRFSS) 2013 dataset, which contains comprehensive health survey data from U.S. adults. The analysis focuses on investigating three key research questions related to public health.

In order to analyze the results please check out intro_data_prob_project.pdf

## Dataset
- **Source**: BRFSS 2013 Survey
- **Sample Size**: 491,775 respondents
- **Variables**: 330 different health-related metrics
- **Collection Method**: Telephone surveys (both landline and cellular)
- **Coverage**: 50 U.S. states, District of Columbia, and three U.S. territories

## Research Questions

### 1. Tobacco Use and Cancer Correlation

![image](https://github.com/user-attachments/assets/fdf047a3-c218-4415-8e3f-f0cae44909f2)

Investigated the relationship between:
- Smoking history (100+ cigarettes)
- Smokeless tobacco use
- Non-skin cancer occurrence

**Key Finding**: People who smoked 100+ cigarettes and use smokeless tobacco daily showed an 11.23% chance of developing non-skin cancer.

### 2. Sleep, Mental, and Physical Health Correlation

![image](https://github.com/user-attachments/assets/7b37d1ae-e2c1-44aa-a664-369f779637d3)

![image](https://github.com/user-attachments/assets/a79f165b-4e10-40b8-a95c-4d088f748dde)

Analyzed the relationships between:
- Sleep duration
- Mental health status
- Physical health status

**Key Finding**: While no strong linear correlation was found, the analysis suggested that extreme sleep patterns (too little or too much) might be associated with poorer health outcomes.

### 3. Gender, Income, and Health Status

![image](https://github.com/user-attachments/assets/da10e958-6669-4b96-ab95-b65feea90a08)


Examined how:
- Gender
- Income levels
- Impact poor health days

**Key Findings**:
- Higher income levels correlate with fewer poor health days
- Males showed slightly higher poor health rates than females at similar income levels
- Income disparities between genders were observed

## Technologies Used
- R Programming Language
- Libraries:
  - ggplot2
  - dplyr

## Methodology
The analysis employs:
- Data visualization
- Statistical analysis
- Correlation studies
- Stratified sampling analysis

## Limitations
- Non-Response bias present (only includes willing respondents)
- Observational study (no causality can be inferred)
- Telephone-based survey limitations

## Repository Structure
- `intro_data_prob_project.rmd`: Main analysis file
- `brfss2013.RData`: Dataset file

## How to Run
1. Ensure R and required packages are installed
2. Place the data file (`brfss2013.RData`) in the same directory as the RMD file
3. Run the R Markdown file in RStudio
