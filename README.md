# Chicago-Data-Analysis-with-SQL

## Introduction

This repository contains a Python notebook which focuses on understanding three datasets related to Chicago, loading them into a Sqlite database, and executing SQL queries to answer relevant analytical questions.

## Datasets

The assignment utilizes three datasets:

1. **Socioeconomic Indicators in Chicago**
   - Download Link: [Socioeconomic Indicators in Chicago CSV](https://ibm.box.com/shared/static/05c3415cbfbtfnr2fx4atenb2sd361ze.csv)
   - Description: This dataset includes six socioeconomic indicators and a hardship index for each Chicago community area for the years 2008 – 2012.

2. **Chicago Public Schools**
   - Download Link: [Chicago Public Schools CSV](https://ibm.box.com/shared/static/f9gjvj1gjmxxzycdhplzt01qtz0s7ew7.csv)
   - Description: This dataset provides school-level performance data used to create CPS School Report Cards for the 2011-2012 school year.

3. **Chicago Crime Data**
   - Download Link: [Chicago Crime Data CSV](https://ibm.box.com/shared/static/svflyugsr9zbqy5bmowgswqemfpm1x7f.csv)
   - Description: This dataset contains reported incidents of crime in the City of Chicago from 2001 to present, excluding the most recent seven days.

## Loading Data into Database

The datasets were manually loaded into tables in a Sqlite database. Each dataset was loaded into a separate table with the following names:

1. **CENSUS_DATA**
2. **CHICAGO_PUBLIC_SCHOOLS**
3. **CHICAGO_CRIME_DATA**

## Questions

The assignment requires executing SQL queries to answer specific questions related to the datasets. The questions cover various aspects such as socioeconomic indicators, school performance, and crime incidents in Chicago.

- Find the total number of crimes recorded in the CRIME table.
- List community area names and numbers with per capita income less than 11000.
- List all case numbers for crimes involving minors?(children are not considered minors for the purposes of crime analysis).
- List all kidnapping crimes involving a child?
- List the kind of crimes that were recorded at schools. (No repetitions).
- List the type of schools along with the average safety score for each type.
- List 5 community areas with highest % of households below poverty line.
- Which community area is most crime prone? Display the coumminty area number only.
- Use a sub-query to find the name of the community area with highest hardship index
- Use a sub-query to determine the Community Area Name with most number of crimes?

## Repository Structure

- **code.ipynb**: Python notebook containing the questions, dataset loading instructions, and SQL queries.
- **README.md**: Readme file providing an overview of the project.
- **CENSUS_DATA.csv**: CSV file for the Socioeconomic Indicators in Chicago dataset.
- **CHICAGO_PUBLIC_SCHOOLS.csv**: CSV file for the Chicago Public Schools dataset.
- **CHICAGO_CRIME_DATA.csv**: CSV file for the Chicago Crime Data dataset.
