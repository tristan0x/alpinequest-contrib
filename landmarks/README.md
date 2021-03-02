# paraglidingearth-french-sites.gpx

Extraction of all french paragliding sites from
https://paraglidingearth.com/api/

GPX file is available here: [paraglidingearth-french-sites.gpx](https://raw.githubusercontent.com/tristan0x/alpinequest-contrib/master/landmarks/paraglidingearth-french-sites.gpx)

To build the GPX file on your own:
1. Install [togpx](git@github.com:tyrasd/togpx.git) utility
1. Download the geojson file containing all paragliding sites in France:
   ```
   curl https://www.paraglidingearth.com/api/geojson/getCountrySites.php?iso=fr&style=detailled --output paraglidingearth-french-sites.geoson
   ```
1. Convert the geojson to gpx: `togpx paraglidingearth-french-sites.geojson > paraglidingearth-french-sites.gpx`

