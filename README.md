# Mini Seismo Tracker
Made by BAYARD KALYAN 180103001 CSE for Mini Project.

Data From: 
[USGS API](https://earthquake.usgs.gov/fdsnws/event/1/)

### Services
Services holds the `fetch` requests to the USGS API. There `fetchQuakes` (which returns all earthquakes for last 30 days) and `searchQuakes` (which returns all earthquakes that meet user-specified criteria) functions. The results of the fetch requests are stored in the `quakes` state in the `EarthquakesContainer`. 
