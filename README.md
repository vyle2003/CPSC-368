# CPSC-368
**Group 4 (2025W2): Sri Chaitanya Bonthula, Arushi Goel, Alice Le**

## About
For this study, we aim to compare COVID-19 mortality rates between Canada and the United States from 2020 to 2023. The study focuses on analyzing how the pandemic impacted different age groups and genders in these two countries, which have distinct healthcare systems: Canada's public healthcare versus the USA's privatized system. 

**Key Research Questions:**

- *Age Distribution of Deaths:* Investigate how COVID-19 mortality rates varied across age groups (0-29, 30-49, 50+) in Canada and the USA over time.

- *Disproportionate Mortality:* Identify if specific age groups experienced higher mortality rates in one country compared to the other.

- *Gender Differences:* Examine how mortality rates differed between males and females across various age groups in both countries.

## Libraries 

Please install these libraries to run the code smoothly
- pandas
- altair
- oracledb
- csv
- matplotlib.pyplot

## Folders
Feel free to download any of the provided files if you want to skip some steps, else, you only need **data_country-1.csv** files to run the first half of the code, the rest can be obtained by completing the steps provided in the **Final Report.ipynb**.
- Outputs: These dataframes are needed for visualizations and answering our research questions. **country_w_population.csv** files are the summary for total mortality and mortality rate for each country. The processes of how to turn sql queries into csv file are included in **Final Report.ipynb**. **country_deaths_data.csv** files are used to answer our 3rd question, here the mortality rate are not provided, we worked with the raw death counts.
- SQL Insert Statements: 2 insert statements files, 1 for each country, this can be done using the code provided in **Final Report.ipynb**.
- data: we included both cleaned and uncleaned data, the **population_country.csv** are files to compute the estimated population for our final report.
## How to run the code
**Warning**: Some of the code may take you 20-25 minutes #line 563

1. Install the packages above
2. Download **data_CA-1.csv** and **data_USA-1.csv**
3. Connect to ssh
4. Load **Final Report.ipynb** in Jupyter Notebook 
5. Kindly cmd/ctl+F to find places with "user" and "password" and replace it with your own oracle account.
6. Run the file line by line (DO NOT RUN ALL)
7. You will get some csv files along the way, to use for visualization or insert statements
8. You can skip some parts by just downloading the csv files needed for the next part!! 

