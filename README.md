# A Proportional Symbol Map of North Carolina County Population in 2023 

This map was developed using scaled circles to represent county population in 2023. A legend and custom mouse events are included to improve user interaction. 

County population and latitude/longitude data were provided from the [US Census Bereau](https://www.osbm.nc.gov/facts-figures/population-demographics/state-demographer/county-population-estimates/certified-county-population-estimates) and [Gigasheet](https://www.gigasheet.com/sample-data/spreadsheet-list-of-all-counties-in-north-carolinacsv). The data was compiled into a CSV file and turned into a GeoJSON file using [geojson.io](https://geojson.io/#map=2/0/20). The GeoJSON file was loaded into [Leaflet](https://leafletjs.com/) for map creation and customizaiton. Additionally, [jQuery](https://jquery.com/) was utilized for handling DOM manipulation and event handling. 
