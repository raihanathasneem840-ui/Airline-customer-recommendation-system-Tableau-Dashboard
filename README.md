# Airline Reviews & Recommendation Analysis — Tableau Dashboard

## Project Overview

This project uses **Tableau** to explore airline passenger reviews and understand how passengers rate their flight experience and whether they recommend the airline.

The dashboard brings together recommendation metrics, passenger segments, airline-level comparisons, and service ratings to make the review data easier to interpret.

## Project Objectives

- Analyse passenger recommendations and recommendation rates.
- Compare recommendation patterns across airlines.
- Explore differences by travel class and traveller type.
- Compare service ratings across key parts of the flight experience.
- Present review data in a visual dashboard that supports quick exploration.

## Dataset

The workbook uses an airline reviews dataset named `airlines_reviews.csv`.

Fields referenced in the Tableau workbook include:

- **Airline** — airline being reviewed
- **Verified** — whether the review is marked as verified
- **Reviews** — written passenger review
- **Type of Traveller** — passenger/traveller category
- **Month Flown** — month of travel
- **Route** — route associated with the review
- **Class** — travel class
- **Seat Comfort** — seat comfort rating
- **Staff Service** — staff service rating
- **Food & Beverages** — food and beverage rating
- **Inflight Entertainment** — inflight entertainment rating
- **Value For Money** — value-for-money rating
- **Overall Rating** — overall passenger rating
- **Recommended** — whether the passenger recommends the airline

## Dashboard Analysis

The Tableau workbook contains these worksheets:

1. **Recommendation Rate** — presents the calculated recommendation rate.
2. **Total Reviews** — summarises the review volume.
3. **Recommendation Distribution** — explores the distribution of recommendation responses.
4. **Recommendation by Airline** — compares recommendations across airlines.
5. **Recommendation by Travel Class** — explores recommendation patterns by cabin/travel class.
6. **Recommendation by Traveller Type** — compares responses across traveller categories.
7. **Service Rating Comparison** — compares ratings for seat comfort, staff service, food and beverages, inflight entertainment, and value for money.

## Calculated Fields

Two calculated fields are defined in the workbook:

- **Recommended Numeric** — converts a `yes` recommendation into `1` and other responses into `0`.
- **Recommendation Rate** — calculates the average of the numeric recommendation field, which can be formatted as a percentage.

These calculations help turn recommendation responses into a metric that can be compared across groups.

## Tools & Skills Demonstrated

**Tableau**
- Dashboard development
- Data visualisation
- Calculated fields
- Aggregation and KPI reporting
- Comparative analysis
- Worksheet design
- Translating review data into business insights

**Data analysis concepts**
- Segmenting data by airline, travel class, and traveller type
- Comparing service-rating measures
- Analysing recommendation patterns

## Project Outcome

The dashboard provides a visual overview of passenger recommendations and service ratings. It demonstrates how Tableau can be used to organise review data, compare passenger segments, and communicate findings in a business-friendly format.

## Project Type

**Data Analytics | Tableau | Airline Reviews | Dashboard & Data Visualisation**

This project was developed as part of a data analytics portfolio to demonstrate practical skills in dashboard creation, calculated fields, KPI reporting, and exploratory analysis using Tableau.
