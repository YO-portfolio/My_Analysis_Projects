# Overview

This repository contains multiple data analysis projects, each with its own focus and dataset.
Below is a summary of each project along with relevant files and data sources.


## Projects

### Project 1: NYC Flights Delay Analysis
Exploration of flight delay patterns by month and time of day at New York City airports.

### Project 2: Airbnb Price Analysis in Bristol
Analysis of factors influencing Airbnb listing prices in Bristol, UK.


## Files

### Project 1: 
#### English Version
- [`NYC_Flights_Delay_Analysis.Rmd`](https://github.com/YO-portfolio/My_Analysis_Projects/blob/main/NYC13_Flights_Delay_Analysis.Rmd) : R Markdown analysis report  
- [`NYC_Flights_Delay_Analysis.html`](https://github.com/YO-portfolio/My_Analysis_Projects/blob/main/NYC13_Flights_Delay_Analysis.html) : Rendered HTML report  

#### 日本語版(Japanese Version)
- [`ニューヨーク市内の空港における遅延率に関する分析.Rmd`](ニューヨーク市内の空港における遅延率に関する分析.Rmd)：Rマークダウン形式
- [`ニューヨーク市内の空港における遅延率に関する分析.html`](ニューヨーク市内の空港における遅延率に関する分析.html)：HTML形式

### Project 2:
#### English Version
- [`Airbnb_Bristol_Price_Analysis.Rmd`](https://github.com/YO-portfolio/My_Analysis_Projects/blob/main/Airbnb_Bristol_Price_Analysis.Rmd) : R Markdown analysis report
- [`Airbnb_Bristol_Price_Analysis.html`](Airbnb_Bristol_Price_Analysis.html) : Rendered HTML report 

#### 日本語版(Japanese Version)
- [`イギリス・ブリストル市におけるAirbnbの宿泊価格に関する分析.Rmd`](イギリス・ブリストル市におけるAirbnbの宿泊価格に関する分析.Rmd)：Rマークダウン形式
- [``]()：HTML形式

## Data Source and Licenses

### Project 1: 
- Data from nycflights13 R package [`nycflights13`](https://cran.r-project.org/web/packages/nycflights13/index.html)  
- Data License: CC0 (Public Domain)

### Project 2:
- Data from Inside Airbnb (Bristol) [`listings.csv.gz`](https://insideairbnb.com/get-the-data/)
- Data License: CC BY 4.0

## How to Reproduce

1. Install R and RStudio.
2. Install required packages: `tidyverse`, `skimr`.
   - Project 1: Uses `nycflights13` package data.
   - Project 2: Uses `readr` for CSV loading.
3. Open the `.Rmd` file and knit to HTML.
