# NCAA Basketball Statistics using Streamlit
## Overview
This app performs web scraping of NCAA Division 1 men's basketball team statistics for the current season from [www.sports-reference.com](https://www.sports-reference.com/cbb/).

[Click here to see the live Version -->](https://eda-college-basketball.onrender.com)

## Functionality
* View team statistics
* Analyze ranked and unranked teams by offensive and defensive performance
* Compare conferences by a chosen metric (e.g., strength of schedule or margin of victory)

## Technologies
* Web application was built with Streamlit and run with Render

## Requirements
* Python libraries: pandas, numpy, streamlit, plotly.express, datetime, lxml
* To launch this project on a local machine, run `streamlit run app.py` in the project's root directory.

## Data Description
* Data Source: https://www.sports-reference.com/cbb/seasons/men/2023-ratings.html
  * *The year should automatically update in the python source code each season.*

## Images

![Offensive and Defensive Ratings](/images/eda_scatterplot.png)

![Conference Comparisons](/images/eda_histogram.png)
