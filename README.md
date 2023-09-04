# Airline Data Analysis with R

## Overview

This repository contains an R script for conducting various analyses on an airline dataset. The analyses include:

- Gender distribution by nationality for the top 10 countries
- Flight flow by airport's country of origin
- Flight status statistics by airport
- Delay percentages by airport

## 📋 Requirements

- R Programming Language
- R Libraries: `dplyr`, `ggplot2`

## 📁 Dataset

The script uses a dataset named `Airline Dataset.csv`, located in the folder `C:\\r\\flight\\`. Ensure this file is available at the specified location before running the script.

## 📊 Features

### Gender Distribution by Nationality

- Counts travelers by gender and nationality
- Calculates gender percentage for each country
- Filters for the top 10 countries
- Visualizes the data in a bar chart

### Flight Flow by Country of Origin

- Counts the number of flights by the airport's country of origin
- Identifies the top 10 countries in terms of flight flow
- Visualizes the data in a bar chart

### Flight Status by Airport

- Counts occurrences of each flight status by airport
- Filters for delays and cancellations
- Visualizes the data in bar charts

### Delay Percentages by Airport

- Counts the total number of flights and delayed flights by airport
- Calculates the percentage of delayed flights by airport

## 🚀 How to Run

1. **Clone the repository or download the R script**.

2. **Ensure the dataset is available** at `C:\\r\\flight\\Airline Dataset.csv`.

3. **Run the script in your R environment**.

## 📜 Output

- Several CSV files summarizing the analyses will be generated.
- PNG images of the bar charts will also be saved.

## 📝 Usage Notes

- Column names in your dataset should match those expected by the script.
- Modify the timeout or other parameters if needed.

## 📜 License

This project is open-source and available under the MIT License.

Feel free to adapt this README to your needs.
