# Portfolio Return Analysis vs. S&P500 - Challenge 4 Submission
The enclosed program conducts a historical financial analysis of four portfolios and the S&P 500 from 2014 through 2020. The analysis includes calculations and plots of portfolio returns, variances, volatility, and betas.

--

## Technologies
Technologies used are jupyter lab, python, and several imported libraries to import a csv file, plot data, and assist in calculating many of key financial data points.

--

## Installation Guide
Import these libraries before running the file:
    %matplotlib
    import pandas as pd
    from pathlib import Path
    import matplotlib.pyplot as plt
    import numpy as np
    import seaborn as sns
    %matplotlib inline

--

## Usage

To use, import the csv file called "whale_navs" in the Resources folder.
Once the data from the csv file is exported, then the rest of the file can be run and the user can interpret the data accordingly.

Here are the answers to the questions posed in this challenge:
**Question** Based on the cumulative return data and the visualization, do any of the four fund portfolios outperform the S&P 500 Index?

**Answer** # Overall, no. All the portfolios do outperform the S&P a couple of times in 2014, 2015, and 2016. After those few times, the S&P outperforms all the portfolios.

**Question** Based on the box plot visualization of just the four fund portfolios, which fund was the most volatile (with the greatest spread) and which was the least volatile (with the smallest spread)?

**Answer** # Berkshire Hathaway INC was the most volatile, Tiger Global Management LLC was the least volatile.

**Question 1**  Based on the annualized standard deviation, which portfolios pose more risk than the S&P 500?

**Answer 1** # Neither
**Question 2** Based on the rolling metrics, does the risk of each portfolio increase at the same time that the risk of the S&P 500 increases?

**Answer 2** # Berkshire Hathaway mostly resembles such trend.
**Question 3** Based on the rolling standard deviations of only the four fund portfolios, which portfolio poses the most risk? Does this change over time? 

**Answer 3** # Berkshire Hathaway poses most risk. Paulson becomes more risky, but Berkshire remains the riskiest portfolio.

**Question** Which of the four portfolios offers the best risk-return profile? Which offers the worst?
    
**Answer** # Berkshire offers the best risk-return and Paulson offers the worst.

**Question 1** Which of the two portfolios seem more sensitive to movements in the S&P 500?
    
**Answer 1** # The Berkshire Hathaway portfolio is more sensitive to S&P movements.
**Question 2** Which of the two portfolios do you recommend for inclusion in your firm’s suite of fund offerings?
    
**Answer 2** # Since the Tiger portfolio has shown to be more balanced over time, I would recommend the Tiger portfolio rather than Berkshire Hathaway.

--

## Contributors
Angela Richter is the sole contributor to this program

--

## Licenses

This program and related items in this repository is intended for learning purposes only.
