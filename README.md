# ETF-Analyzer

Financial database and web application designed to analyze the performance of a fintech ETF.

First, the ETF Analyzer uses SQL to query the database and import PYPL stock data. PYPL data is plotted to enhance its readability. In the below screenshot, Voilà library is used to present the plot in a web application.

![image](https://user-images.githubusercontent.com/69730757/154788869-a89499f1-1501-4b77-98b5-66498d9e957c.png)

Next, the app joins data from three other stocks into the PYPL dataframe to represent the entire ETF. The ETF Analyzer calculates average daily and annualized returns for the portfolio and plots the cumulative data.

![image](https://user-images.githubusercontent.com/69730757/154788975-f4f97040-0c71-48ae-8699-48495475fe27.png)

The ETF Analyzer creates value for users, namely investors, by calculating key metrics that are relevant in ETF analysis. The plots and data visualizations simplify the complex .db data for the investor.

The app is written in such a manner that it can take in data from any ETF and is still just as useful.

---

## Technologies

The ETF Analyzer is written in Python 3.10.1 using Jupyter Lab. It is compatible with Mac and PC OS.
The tool uses SQLite and Pandas to query and prepare data.
Data visualization plots are rendered using hvplot.
Visualizations are deloyed as a web application using the Voilà library.
This app references raw data that is provided in a .db file.

---

## Installation Guide

This app can be run in Gitbash or Terminal. The app and supporting files are located in the below Github repository:
https://github.com/kyhuber/ETF-Analyzer

---

## Usage

To use the ETF Analyzer, the user must have access to stock performance data.

---

## Contributors

The ETF Analyzer was written by Kyle Huber in February 2022.

---

# ETF Analyzer
