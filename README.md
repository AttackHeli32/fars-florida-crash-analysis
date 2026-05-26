# Florida Fatal Crash Residency Analysis

## Project Overview

This project analyzes fatal crash patterns in Florida between Florida resident drivers and out-of-state drivers. The analysis uses Fatality Analysis Reporting System (FARS) data from 2021 through 2023 and focuses on whether driver residency is associated with differences in fatal crash characteristics.

The main goal of the project was to compare Florida resident and out-of-state drivers across several crash-related factors, including crash type, time of day, speeding involvement, age group, county, weather conditions, and monthly crash patterns.

This project was completed as part of a class research project and was presented in class.

## Research Question

Do fatal crash characteristics differ between Florida resident drivers and out-of-state drivers involved in fatal crashes in Florida?

## Dataset

The project uses data from the Fatality Analysis Reporting System (FARS), which is maintained by the National Highway Traffic Safety Administration (NHTSA).

The analysis focuses on Florida crash records from:

- 2021
- 2022
- 2023

Main datasets used:

- `person.csv`
- `vehicle.csv`
- `accident.csv`

These files were merged and filtered to focus on drivers involved in fatal crashes in Florida.

## Key Variables

Some of the main variables used in the analysis include:

- Driver licensing state
- Driver residency group
- Crash type
- Time of crash
- Speeding involvement
- Driver age group
- County of crash
- Weather conditions
- Month of crash

Since the dataset does not directly label a driver as a resident or visitor, driver licensing state was used as a proxy for residency. Drivers with a Florida license were treated as Florida residents, while drivers with a non-Florida license were treated as out-of-state drivers.

## Methods

The analysis was completed using Python in Google Colab.

Main methods used:

- Data cleaning
- Dataset merging
- Filtering Florida crash records
- Creating residency groups
- Descriptive statistics
- Frequency tables
- Contingency tables
- Chi-square tests of independence
- Two-sample proportion z-tests
- Fisher’s Exact Test
- Data visualizations using Matplotlib and Seaborn

A significance level of 0.05 was used for hypothesis testing.

## Hypotheses Tested

The project explored several hypotheses, including:

1. Whether crash type distribution differs between Florida resident and out-of-state drivers.
2. Whether out-of-state drivers are more likely to be involved in nighttime fatal crashes.
3. Whether speeding involvement differs between Florida resident and out-of-state drivers.
4. Whether fatal crashes differ by county between the two groups.
5. Whether weather-related fatal crashes differ by residency group.
6. Whether fatal crash involvement differs across age groups.
7. Whether monthly crash patterns suggest a possible tourism-related effect.

## Main Findings

The analysis found several statistically significant differences between Florida resident and out-of-state drivers.

Some major findings included:

- Fatal crash type distribution differed significantly by driver residency.
- Out-of-state drivers had a higher proportion of nighttime fatal crashes.
- Florida drivers had a higher proportion of speeding-related fatal crashes.
- Age group distribution differed between Florida resident and non-Florida resident drivers.
- Some county and monthly crash patterns also showed differences between residency groups.

These results suggest that driver residency may be associated with different fatal crash patterns in Florida.
