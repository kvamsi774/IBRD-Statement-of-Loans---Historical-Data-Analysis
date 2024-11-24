# IBRD-Statement-of-Loans---Historical-Data-Analysis

**Project: IBRD Statement of Loans - Historical Data Analysis**

**Introduction**
The International Bank for Reconstruction and Development (IBRD) is a vital institution within the World Bank Group, playing a pivotal role in international finance and development.


This report analyzes historical snapshots of the Statement of Loans, focusing on data expressed in U.S. dollars and calculated using historical rates.


These loans are extended to or guaranteed by member countries of IBRD, embodying a critical aspect of global economic cooperation.


**Objective**
To scrutinize and interpret the trends, patterns, and implications embedded in the IBRD loans dataset.


To unveil insights that can contribute to a nuanced understanding of international financial dynamics, showcasing how IBRD loans impact member countries and, in some cases, the International Finance Corporation (IFC).


**Data Overview**

The dataset encompasses a historical record of IBRD loans, capturing various facets of public and publicly guaranteed debt.


These loans, often extended at market rates, reflect the financial relationships between the IBRD and its member nations.


The dataset may include instances where IBRD loans are directed towards the IFC.


**Methodology**

The analysis leverages R Studio, a powerful tool for statistical computing and data analysis.


Exploratory data analysis (EDA) techniques, visualization, and statistical modeling are used to extract meaningful insights from the dataset.


The analysis will uncover trends over time, identify influential factors, and highlight any noteworthy anomalies.


**Data Cleaning**

Missing values imputed with the mean.


Unnecessary columns removed.


Date columns converted to Date type.


**Analysis & Visualizations**

Interest Rate by Region

A bar chart shows the average interest rate by region.


The average interest rate in each region is higher than the average interest rate in the other regions.


Distribution of Loan Types across courts

A bar chart shows the distribution of loan types.


The most common loan types are BLNC and BLNR, followed by BLOAN, CPL, and FSLGuarante.


The least common loan types are JROCP, USDSCPD, SCPM, SCBNGL, and CRNC.


Distribution of Loan Status

A pie chart shows the distribution of loan status.


The most common loan status is Approved, followed by Disbursed and then Cancelled.


Original Principal Amount vs. Disbursed Amount

A scatter plot shows the relationship between the original principal amount and the disbursed amount.


The two most common original principal amounts are $100,000-$250,000 and $250,000-$500,000, accounting for 46% and 32% of all loans, respectively.


Disbursed Amount over Time in India

A time series plot shows the trend of the disbursed amount over time in India.


The disbursed amount has increased steadily over time, from ₹0 in 2002 to ₹2.0e+09 in 2012.


**Statistical Summary**
The script calculates the mean, median, and standard deviation of the Interest.Rate column.


The mean interest rate is 4.504073%, the median interest rate is 5.3%, and the standard deviation is 3.307183%.


**Script/Functions**
A function is defined to create a scatter plot of the original principal amount vs. the disbursed amount.


The scatter plot shows a positive correlation between the two variables. 


