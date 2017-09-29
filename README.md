# Recreating Roy Leban's Analysis of NY Times Crossword Puzzle Difficulty by Day of the Week

A short, just-for-fun web scraping exercise to recreate an analysis of New York Times crossword difficulty from Bill Butler's crossword solutions web site.

The Jupyter notebook is meant to be self-contained and stand-alone.  Running it will:
  * scrape the relevant data from the web and write the data to .csv file; once this is completed, the notebook will skip the web scraping auto-load the data from file.
  * generate histograms of crossword puzzle difficulty by day of the week
  * fit Gaussian distributions to the histograms / examine them for Gaussianity
  * produce Q-Q plots and IQR plots to examine the data distribution
  * recreate a "Bulter Index" puzzle difficulty plot using the data scraped from the web.
