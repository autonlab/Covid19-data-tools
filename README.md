# Covid19 Data Processing
1. Data source is [John Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)
1. [Python code](Covid19-Data.ipynb) to convert wide format to long format and sanitize the data
1. Inputs are three files: `confimred`, `deaths`, and `recovered`
1. Ouput four files:
    1. `covid19-confirmed-<date>.csv`
    1. `covid19-deaths-<date>.csv`
    1. `covid19-recovered-<date>.csv`
    1. `covid19-<date>.csv` - contains confirmed, deaths and recovered
    1. `covid19-<date>.csv` - contains confirmed, deaths and recovered in the long format i.e. (type, count)
    1. `covid19.c6p` - geo-coordinates, i.e State to latlong