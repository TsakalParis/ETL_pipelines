# ETL_pipelines
1) comb_weather_etl
An ETL pipeline where we get data weather data from "weather.gov" and from "wunderground.com". We achieve that by using and api for "weather.gov" and data scraping via beautiful soup and python requests for "wunderground.com" since it dosent offer a free api. Continuous monitoring of the two data sources, combining their information into a single dataframe, and saving the information in SQL via condition.
