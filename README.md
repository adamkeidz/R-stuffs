# Power Data Analysis

This project involves analyzing power data from a CSV file and generating graphs using ggplot2 in R.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [License](#license)

## Introduction

The purpose of this project is to read power data from a CSV file, perform data manipulation and analysis, and generate graphs to visualize the data. The code has been refactored to improve readability, efficiency, and maintainability.

## Prerequisites

To run this project, you need to have the following software installed:

- R (version 3.6 or higher)
- R packages: ggplot2, lubridate, dplyr

## Installation

1. Clone the repository or download the code files.

2. Open R or RStudio.

3. Install the required packages by running the following commands in the R console:

   ```R
   install.packages("ggplot2")
   install.packages("lubridate")
   install.packages("dplyr")
   
4. Update the file path in the code to point to your CSV file.

## Usage

1. Run the code in R or RStudio.

2. You will be prompted with options to view graphs and perform calculations:

- Enter 1 to see a graph of Power vs. Device in a specific month.
- Enter 2 to see the minimum power value in the dataset.
- Enter 3 to see the maximum power value in the dataset.
- Enter 0 to exit the program.
3. Follow the prompts to input the Device ID and the month (August or September) for graph visualization.

4. The graphs will be displayed using ggplot2, and the minimum/maximum power values will be printed to the console.

5. Repeat the steps to view different graphs or calculations.

## File Structure

1. The project files are organized as follows:

 - power_analysis.R: The refactored R code for data analysis and graph generation.
 - activepowertotal.csv: The input CSV file containing power data. (Available here https://bit.ly/R-adamkeidz)
 - README.md: This README file.
