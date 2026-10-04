# Seattle vs. Syracuse: Where does it rain more? 
This project is to measure and compare whether it rains more in Seattle, WA, than in Syracuse, NY. 

# Project Overview
Provide a short and concise overview of the project. Mention the problem it solves, the data used, and the key outcomes or findings.

# Objective: Clearly state the main goal of the project.
Domain: (e.g., Healthcare, Finance, E-commerce, etc.)
Key Techniques: (e.g., Regression, Classification, Clustering, NLP, Time Series)
Project Structure
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
# Data
Sources:
https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND


# Description: Brief overview of the dataset features, size, and format
License: (if applicable)
# Analysis
The analysis is performed in `code/SEA_Weather_II.ipynb`. The notebook compares precipitation in Seattle, Washington, and Syracuse, New York, using NOAA weather data.

The analysis inspects and cleans the data by selecting the Syracuse Hancock International Airport weather station, limiting both datasets to the same date range, and removing missing precipitation values. The cleaned datasets are then combined into a tidy dataframe, followed by summary statistics and a bar graph comparing total precipitation between the two cities.

The clean data file produced by the analysis is `data/weather_clean.csv`.

Results
Include a short discussion of the findings and what they imply.

Authors
Jenna Lee - @yourhandle
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Tools/libraries used
Tutorials or papers referenced
Inspiration or collaborators