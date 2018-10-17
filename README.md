Jupyter notebook that:
  1) web scrapes the CIA world fact book using beautiful soup using the get_data function
  2) cleans up the data and normalizes the resultant data
  3) allows for detection of outliers via either a Isolation Forest method or basic S.D. thresholds
  4) allow to specific a variable of interest
  5) correlates all other varibles read in to that target variable
  6) cluster the target variable using an interactive kernel density
  7) plots the scatter plots of the target variable against the other read in variables - but know color coded by cluster
  8) plot all possible combinations of scatter plots of non-target variables, whilst color coding the data by the clusters
    the target variable
