# Mapping_Earthquakes

### Overview
In this challenge we used API's in order to map out the magnitude of eathquakes around the world. Using different layers of mapbox (Dark / Satellite / Streets) as well as a filter for (Earthquakes / Tectonic Plates / Major Earthquakes) in order to change the visualization of the index.html file

### Summary
In my logic.js file, I used a basic layer to hold (Earthquakes / Tectonic Plates / Major Earthquakes). I then added a 2nd layer in order to hold the tectonic plate data. From there, I used D3 to retrieve the earthquake GeoJson data. Once all of that was plotted, the features enabled the earthquakes to have a style, color, and radius in order to let the end user visually see the severity of each earthquake. The "bindPopup" layer allowed each circle marker to display the magnitude and location of the Earthquake. My index.html file put all of this together while protecting the integrity of the API key needed to pull the map information using gitignore.
