# COVID-19 Data Analysis Project

## Overview

This repository contains an in-depth SQL analysis of global COVID-19 data, focusing on cases, deaths, and vaccination rates. Utilizing Microsoft MySQL, the project explores complex relationships within the data to derive insights into the pandemic’s impact and vaccination efforts.

## Data Sources

The datasets include:

- **CovidDeaths.csv and CovidDeaths.xlsx**: Daily updates on COVID-19 deaths by country.
- **CovidVaccinations.csv and CovidVaccinations.xlsx**: Information on COVID-19 vaccination doses administered worldwide.

## Project Structure

- **COVID Portfolio Project - Data Exploration.sql**: Contains all SQL queries used for data analysis.

## SQL Techniques Employed

- **Basic Data Retrieval**: Filtering and ordering operations to prepare datasets.
- **Complex Calculations**: Analyses of mortality and infection rates to understand the severity and spread of the virus.
- **Data Joining**: Merging death and vaccination data to assess the progress of vaccination campaigns relative to case numbers.
- **Window Functions**: Utilized for rolling calculations such as cumulative vaccinations.
- **Temporary Tables and Views**: For efficient data manipulation and streamlined future analyses.

## Analysis Highlights

- **Mortality Rate Calculation**: Evaluates the likelihood of dying from COVID-19 in various regions.
- **Infection Rate Analysis**: Determines the percentage of the population infected with COVID-19.
- **Vaccination Analysis**: Analyzes the cumulative percentage of populations vaccinated over time, employing advanced window functions.

## Tools and Technologies

- **Microsoft MySQL**: Primary database platform for executing SQL queries.
- **Excel**: Used for preliminary data cleaning and formatting.

## Acknowledgments

This project builds upon and extends methodologies discussed by Alex the Analyst, whose tutorials have been instrumental in shaping the analytical approaches used in this project.

## Contributions and Usage

- **Cloning the Repository**: You can clone this repository to run and modify the analyses.
- **Running the SQL Scripts**: Import the datasets into your MySQL environment and execute the SQL scripts provided.
- **Contributions**: Contributions to enhance the analyses or extend the datasets are welcome. Please fork the project, make improvements, and submit a pull request.
