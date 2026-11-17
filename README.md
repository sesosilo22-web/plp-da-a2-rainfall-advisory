# plp-da-a2-rainfall-advisory
Kenya County Rainfall Analysis

Project Overview

This project analyses monthly rainfall data for five counties in Kenya: Nairobi, Nakuru, Kisumu, Mombasa and Machakos.

The aim is to use Python and NumPy to explore rainfall patterns, identify dry and wet months, 
and determine potential planting windows to support agricultural planning.

Objectives

Clean missing and invalid rainfall data.

Combine rainfall records into a NumPy array.

Calculate annual rainfall totals for each county.

Calculate average monthly rainfall across all five counties.

Identify the wettest month in each county.

Count the number of dry months (rainfall below 50 mm).

Identify the two consecutive months with the highest combined rainfall.

Export the rainfall summary into a CSV file.

Tools and Technologies

Python – Data cleaning and analysis.

Google Colab – Writing and running Python code.

NumPy – Numerical calculations and array operations.

CSV module – Exporting results into a CSV file.

GitHub – Storing and sharing the project.

Data Cleaning

The Machakos rainfall dataset contained two invalid entries: 
N/A for April and a blank value for September.

These missing values were replaced with the rounded average of the valid Machakos rainfall readings, which was 68 mm.

Key Findings

Kisumu recorded the highest annual rainfall at 1,371 mm.

Machakos recorded the lowest annual rainfall at 811 mm.

April and May were the two-month periods with the highest combined rainfall in Nairobi, Nakuru, Kisumu and Mombasa.

November and December had the highest combined rainfall in Machakos.

Data Quality Consideration

The missing Machakos rainfall values were estimated using the average of the available readings. 
Therefore, the calculated results may not represent the actual rainfall for those months. 
The planting windows are based on the available dataset and should be considered potential periods rather than confirmed planting recommendations.

How to Run

Open the notebook using Google Colab.

Run the notebook cells in order, from top to bottom.

Review the rainfall calculations and results.

Generate the rainfall_summary.csv file.

Output

The analysis produces a CSV file named rainfall_summary.csv containing:

County

Annual rainfall total (mm)

Wettest month

Number of dry months

Two-month planting window

Conclusion

This project demonstrates how Python and NumPy can be used to clean, organise and analyse rainfall data. 
The findings provide a starting point for understanding rainfall patterns and supporting agricultural planning across the five counties.
