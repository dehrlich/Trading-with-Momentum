# Trading with Momentum

### Project Motivation:

- To generate a trading signal based on a momentum indicator and test the strategy to see if it has the potential to be profitable.

- The notebook covers data collection and inspection, stock universe construction, resampling, log return calculation, momentum indicator calculation, projected returns based on momentum indicator strategy, T-test and P-value calculation to determine statistical significance of returns based on momentum indicator, and conclusions drawn from tests.

### File Descriptions:


    project_1.ipynb
    | - Jupyter notebook containing all data collection, cleaning, and data frame construction, momentum trading signal construction, projected returns, and statistical significance testing functions, as well as conclusions drawn from tests.
    helper.py
    |- helper file to abstract some data collection and import statements
    project_helper.py
    |- helper file to abstract graphing functions
    project_test.py
    |- unit tests to flag any major errors
    README.md


### Installations:
- This project requires access to Quandl dataset hosted on Udacity instances for the "AI for Trading" course. See 'helper.py' `download_quandl_dataset` function for specifics on Quandl API access.
- You will need a python environment with the following:
    - pandas, numpy, scipy, plotly, os, tempfile, zipfile, glob, tqdm, math, requests
    - python verson 3.6 or higher

### Instructions:
1. Run each cell in 'project_1.ipynb' in sequence. Make sure the Jupyter notebook is in the same level of the directory as 'helper.py', 'project_helper.py', 'project_tests.py', and 'tests.py'.