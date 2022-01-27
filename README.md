# World Bank Data Dashboard
Dashboard that pulls data directly from World Bank API displaying data baseds on indicators.


## Installation
The code was developed using Python versions of 3.* as well as Bootstrap 4, `Flask`, `pandas` and `request`. For deployment, the package `gunicorn` needs to be installed as well.

## Project Motivation
The dashboard was developed to provide an overview of top 10 world economies land use related information in interactive graphs to allow end-user to explore its different dimensions. `Plotly` was used to make plots dynamic. 

## File Description
- `myapp`: folder with all rendering of the frontend of the web app `HTML`, `CSS` and `Python` filed.
- `requirements.txt`, `Procfile`, `myapp`: these files are used for deployment of the dashboard.

## Licence, Authors and Acknowledgement
The underlying data for analysis is pulled from the [World Bank](https://data.worldbank.org/summary-terms-of-use) api. Feel free to use the code to add additional features to the data dashboard.