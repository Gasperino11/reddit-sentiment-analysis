# Sentiment Analysis on titles of Reddit Posts using Google Cloud NLP
This repo was built as a part of my master's program at the University of Missouri for my cloud computing class. It goes through the process of extracting data from Reddit RSS feeds, running Google Cloud's NLP API on it, and using a BI tool to extract insights out of the results. It was built using a JupyterHub environment and so the data extraction and intial data exploration code are provided as Jupyter notebooks.

*Data Extraction* provides the python code used to extract the reddit RSS data, run sentiment analysis on it, and then flatten that data into a CSV for easy ingestion into a BI platform like Tableau, Power BI, or R Shiny.

*Aggregation and Visualization* is the R code that was used as initial data exploration and is ultimately what inspired the R Shiny dashboard.

The Shiny dashboard is current under construction but will be available on shinyapps.io and the code will be available under the shinyApps folder. I will also update the repo with a link once finished.