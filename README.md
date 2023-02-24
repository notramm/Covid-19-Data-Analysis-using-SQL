# Covid-19-Data-Analysis-using-SQL

# SQL for COVID-19 Data Analysis 
*Deep dive analysis of worldwide COVID-19 data regarding case and death trends.*

According to **Our World in Data**, the actual death toll from COVID-19 is "likely to be higher than the number of confirmed deaths" due to limited testing and problems in the attribution of the cause of death. The difference between reported confirmed deaths and actual deaths varies by country. 
###### DATA UPDATED JANUARY 20, 2022.

## Skills used
* Joins
* CTE's
* Temp Tables
* Windows Functions
* Aggregate Functions
* Creating Views
* Converting Data Types

## About the Database
The *Our World in Data* COVID-19 datasets can be found on https://ourworldindata.org/covid-deaths. \
Obtain the database tables for this starter project within the `database` folder.

#### Two Microsoft Excel Files:
The reason behind two files between COVID-19 vaccinations and deaths data for this starter project was for optimization and clarity purposes for certain queries.

**CovidDeaths**: contains columns such as 
``isocode continent	location	date	population	total_cases	new_cases	new_cases_smoothed	total_deaths	new_deaths	new_deaths_smoothed	total_cases_per_million	new_cases_per_million	new_cases_smoothed_per_million	total_deaths_per_million	new_deaths_per_million	new_deaths_smoothed_per_million	reproduction_rate	icu_patients	icu_patients_per_million	hosp_patients	hosp_patients_per_million	weekly_icu_admissions	weekly_icu_admissions_per_million	weekly_hosp_admissions	weekly_hosp_admissions_per_million``

**CovidVaccinations**: contains columns such as ``isocode continent	location	date	new_tests	total_tests	total_tests_per_thousand	new_tests_per_thousand	new_tests_smoothed	new_tests_smoothed_per_thousand	positive_rate	tests_per_case	tests_units	total_vaccinations	people_vaccinated	people_fully_vaccinated	total_boosters	new_vaccinations	new_vaccinations_smoothed	total_vaccinations_per_hundred	people_vaccinated_per_hundred	people_fully_vaccinated_per_hundred	total_boosters_per_hundred	new_vaccinations_smoothed_per_million	new_people_vaccinated_smoothed	new_people_vaccinated_smoothed_per_hundred	stringency_index	population_density	median_age	aged_65_older	aged_70_older	gdp_per_capita	extreme_poverty	cardiovasc_death_rate	diabetes_prevalence	female_smokers	male_smokers	handwashing_facilities	hospital_beds_per_thousand	life_expectancy	human_development_index	excess_mortality_cumulative_absolute	excess_mortality_cumulative	excess_mortality	excess_mortality_cumulative_per_million``

## Refrence
[AlexTheAnalyst](https://www.youtube.com/@AlexTheAnalyst)
