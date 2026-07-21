# Project Title: The Impact of Austerity Measures on Eurozone Economies 

This project investigates how fiscal consolidation strategies, specifically spending cuts versus tax hikes and internal devaluations, as a response to the Greek Debt Crisis impacted GDP growth, unemployment, household consumption, and income inequality across Eurozone member states from 2002 to 2019.

## About the Data

This project utilizes multiple macroeconomic and survey panel datasets located in the `data/` folder, covering 11 Eurozone countries over an 18-year period.

* **Source:** Eurostat, European Commission AMECO database, and the Bank for International Settlements (BIS) Data Portal.
* **Format:** CSV files and standardized Excel spreadsheets.
* **Content:** Annual country-level indicators including real GDP growth, trade openness, cyclically adjusted government revenues/expenditures, output gaps, total and youth unemployment, labor productivity, direct/indirect tax revenues, HICP inflation, private sector debt, residential property prices, S80/S20 income inequality ratios, social protection expenditures, and adjusted wage shares.

## Repository Structure

This project is built as a fully reproducible RStudio Project:
* `Greek project.Rproj` - The RStudio Project configuration file (the transparent cube).
* `data/` - Folder containing all 20 source datasets.
* `Greek Project.R` - The main R script containing the core analysis.
* `Greek-Project.Rmd` - The R Markdown document that generates the final report.

## How to Run This Project

1. Click the green **Code** button at the top right of this page and select **Download ZIP** (or clone the repository if you use Git).
2. Extract the ZIP file to your computer.
3. Open the folder and double-click the **`Greek project.Rproj`** file (the transparent cube icon) to launch RStudio.
4. Open `Greek-Project.Rmd` or any script in the `scripts/` folder.
5. Run the code or click **Knit** to generate the final report document. All file paths will automatically resolve themselves!

## Required R Packages

Before running the code, ensure you have the following packages installed:

* `plm` (for panel data estimation and Two-Way Fixed Effects models)
* `lmtest` and `sandwich` (for estimating Driscoll-Kraay robust standard errors)
* `car` (for regression models)
* `here` (required for dynamic R Markdown file paths)
* `knitr` (for report generation)
