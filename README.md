# [Covid-19 Analysis](https://github.com/itummino/PortfolioProjects/blob/main/CovidData.sql) ![image](https://user-images.githubusercontent.com/84094369/120266911-dcb66a00-c270-11eb-9df0-c20d82d87cad.png)
## *A Global Look into Confirmed Cases, Death Rates, & Vaccinations Data*
![](/covid1.jpeg)  
### Sources/Procedure:
- Imported global Covid-19 data from [OurWorldInData](https://ourworldindata.org/covid-deaths) from pandemic start (Feb 2020) to (May 2021) into Microsoft SQL Server Management Studio
- Extracted and organized case/deaths data and vaccinations data into two separate CSVs to perform table JOINs
- Used SQL data cleaning and complex queries to determine aggregate figures of total cases VS the population, analyzing trends between both the United States and around the globe
#### 👉[Click here to view my SQL Code](https://github.com/itummino/PortfolioProjects/blob/main/CovidData.sql)

### Points of Interest: 
- Countries with the highest infection rate and highest death count compared to the population
- Trends of cases/deaths over time, created a death percentage to visualize data more accurately
- Calculated the percentage of the U.S. population that contracted Covid-19 vs global figures
- Total population versus recorded vaccinations over time, calculated a global vaccination rate and used TEMP table and CTE 
- All new vaccines administered in the US over time
- Total vaccinations administered globally according to income bracket (low, lower middle, upper middle, high income)

### Data Visualizations:
- Created SQL views to store/condense the data in SSMS and then export into Tableau for data vizzes
- Built 3 different vizzes in Tableau Public for final analysis (linked below): 

#### [Global Covid-19 Data](https://public.tableau.com/app/profile/isabel.tummino/viz/GlobalCovid19Data/GlobalCovidData)
#### [US Covid-19 Data](https://public.tableau.com/app/profile/isabel.tummino/viz/U_S_Covid19Data/U_S_CovidData)
#### [Global Vaccinations Data](https://public.tableau.com/app/profile/isabel.tummino/viz/VaccinationsData/GlobalVaccinationData)
