# POOL App

Pool App analyzes existing taxi routes to generate dynamic shuttle ride schedules to create more efficient and affordable transportation options.

## Heroku Web App

https://poolapp.herokuapp.com/

## Summary

In this project, I used NYC taxi trips public dataset to investigate possible improvements to transportation. The idea is to identify similar rides (in terms of starting and ending locations, as well as pick-up times), and grouping them together to schedule a shuttle service. I used K-Means clustering algorithm to group the trips together, and analyzed what percentage of the rides can be potentially reduced by this approach, as well as the total business revenue for providing this service.

The dataset can be found at

http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml
http://www.nyc.gov/html/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
