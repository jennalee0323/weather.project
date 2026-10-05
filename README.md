# Seattle vs. Syracuse: Where does it rain more? 
This project is to measure and compare whether it rains more in Seattle, WA, than in Syracuse, NY. 

# Project Overview
Provide a short and concise overview of the project. Mention the problem it solves, the data used, and the key outcomes or findings.

# Objective: 
To find out if Syracuse, New York, has a higher precipitation rate than Seattle, Washington.
Domain: Weather
Key Techniques: pandas, numpy, matplotlib, seaborn, jupyter
Project Structure
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
# Data
Sources:
https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

# Description:
New York dataset was reduced to focus on John Hancock Intl. Airport weather station, and bar graph was made to compare and contrast between the two cities. 

# Analysis
The analysis is performed in `code/SEA_Weather_II.ipynb`. The notebook compares precipitation in Seattle, Washington, and Syracuse, New York, using NOAA weather data.

The analysis inspects and cleans the data by selecting the Syracuse Hancock International Airport weather station, limiting both datasets to the same date range, and removing missing precipitation values. The cleaned datasets are then combined into a tidy dataframe, followed by summary statistics and a bar graph comparing total precipitation between the two cities.

The clean data file produced by the analysis is `data/weather_clean.csv`.

To test this hypothesis, I decided to use a dataset that recorded precipitation amounts for both cities from the year 2018 to 2022, retrieving data from the National Oceanic and Atmospheric Administration’s website. Before starting with a proper analysis, the datasets for both cities were organized to the same date range, and missing precipitation values. For the Syracuse dataset, there were multiple weather stations. To make it easier to read, compare, and contrast, I decided to narrow down to one weather station with the most recorded precipitation data: Syracuse Hancock International Airport weather station. 

Results
In conclusion, Syracuse, New York, had about 35 more inches of precipitation than Seattle, Washington. This shows that Seattle is not the most nor the only “rainy city” in the United States of America. While the study does not show whether it is constantly raining in Syracuse like Seattle, or whether they get a surge of rain at once, this can keep us wondering how many other cities are out there that get more precipitation than Seattle.
Authors
Jenna Lee
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Tools/libraries used
Tutorials or papers referenced
Inspiration or collaborators