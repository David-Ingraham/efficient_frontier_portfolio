![makowitz_efficient_frontier_hd-2](https://user-images.githubusercontent.com/86025349/130362396-26978a52-7b15-440e-a7e9-d81113f57ad8.png)

# *Group 4 Project 1*
## Portfolio Optimization: An Efficient Frontier-Based Advisement App

**Welcome to Group 4's Project 1 repository. Here, you can check out the interactive portfolio advisor application we built using Python and the Pandas library to analyze the performance of user-input portfolios based on its coordinate prximity to the Efficient Frontier curve.**

---

## Background
This project explores the concept of the Efficient Frontier: the set of optimal portfolios that offer the highest expected return for a defined level of risk or the lowest risk for a given level of expected return. The concept, which belongs to the larger framework of Modern Portfolio Theory (MPT), reveals the benefit of diversification resulting from the curvature of the efficient frontier. The curvature is integral in revealing how diversification improves the portfolio's risk / reward profile.

We wanted to better-understand this concept by testing its functionality in the form of an interactive robo-advisor application, in which a user could input stocks and associated values contained in their portfolio and visualize its efficiency in a graphical representation that shows its proximity to the efficient frontier curve. The app then offers investment options and advisement based on these inputs, so that the user might better-distribute their assets.

The efficient frontier graphically represents portfolios that maximize returns for the risk assumed. Returns are dependent on the investment combinations that make up the portfolio. The standard deviation of a security is synonymous with risk. 

Ideally, an investor seeks to populate the portfolio with securities offering exceptional returns but whose combined standard deviation is lower than the standard deviations of the individual securities. The less synchronized the securities (lower covariance), the lower the standard deviation. If this mix of optimizing the return versus risk paradigm is successful then that portfolio should line up along the efficient frontier line.

Portfolios that lie below the efficient frontier are sub-optimal because they do not provide enough return for the level of risk. Portfolios that cluster to the right of the efficient frontier are sub-optimal because they have a higher level of risk for the defined rate of return.

(source: Investopedia https://www.investopedia.com/terms/e/efficientfrontier.asp )

---

## Technologies & Usage
This project leverages Python 3.7 and the following libraries and dependencies:
- import numpy as np
- import pandas as pd
- import datetime as dt
- import sys
- import fire
- import constraint
- from pandas_datareader import data as pdr
- import ploty.graph_objects as go
- import scipy.optimize as sc
- from pathlib import Path

---

## Summary of Analysis
Through several tests of hypothetical user-input portfolios, it became evident to our group that while the efficient frontier is a handy concept for portfolio analysis and investment decision-making, there are limitations inherent to the concept itself that left us with the conclusion that a more robust and comprehensive analysis might include supplementary analytical devices. But, for the scope of the project presented here in its first version, we found that the concept allows for a concise visual demonstration of a portfolio's efficiency and enables user-friendly interactivity. Despite the limitations, the app allows for any investor to test the optimization of their portfolio by harnessing the fundamentals of the efficient frontier.

## Notes on Further Development
Future steps for this app's development include integrating the code responsible for plotting the user assets with a conditional statement that provides analytical functionality, improving the user interface, and providing more comprehensive advisment.
