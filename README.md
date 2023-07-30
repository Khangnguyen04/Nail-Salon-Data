# Nail-Salon-Data

SQL and Tableau project that takes nail salon data across Northeast Ohio and compares salon prices, ratings, and populations.

## Background

My family has owned a local nail salon for the past six years, and I wanted to do a project that could help my family see where their salon stands in this region, and that also supports my passion for data analytics.

## Objective

Collect data on nail salons in Northeast Ohio to find the highest-rated salons in each city, the price range of services, and if population density correlates with the number of salons in the city.

## Data Source and Collection

* Web-scraping Google for info
* Note salons' ratings out of five stars and the number of reviews
* Input their services and place them in five categories:
  * Dip, regular, gel, acrylic, and feet services
* City population

The Excel file can be found in a separate file in this repo

## Methodology

* Import data into SQL Server
* Insights:
  * How many cities are in the data and what cities they?
  * Highest-rated salons with four or more stars and 50 or more reviews?
  * Cheapest salon in each city
  * The city with the most salons
  * Population correlation with salon number

The code can be found in a file within this repo

## Interpretation

* There were 42 cities
* The highest-rated salon out of every city was Bronze Beauties Bar in Strongsville
* The cheapest salon out of the cities is King Nails in Strongsville
* Cleveland has the most salons with 46 and a population of 370,000
* Cities with higher populations provide more nail salons than those with lower populations

## Tableau

Visualizations: [https://public.tableau.com/app/profile/khang.nguyen4719/viz/NailSalonsAcrossNortheastOhio/Dashboard1]

## Summary

This was my first time web-scraping the internet and it was a tedious project. After further research I should automate this process using Python next time.

