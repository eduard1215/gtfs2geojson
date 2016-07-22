# gtfs2geojson

[![CircleCI](https://circleci.com/gh/tmcw/gtfs2geojson/tree/master.svg?style=svg)](https://circleci.com/gh/tmcw/gtfs2geojson/tree/master)<Paste>

Convert [GTFS](https://developers.google.com/transit/gtfs/?hl=en) data into
[GeoJSON](http://geojson.org/).

    npm install --save gtfs2geojson

## API


`lines(gtfs)`

Parse GTFS shapes.txt data given as a string and return a GeoJSON FeatureCollection
of features with LineString geometries.

`stops(gtfs)`

Parse GTFS stops.txt data given as a string and return a GeoJSON FeatureCollection
of features with Point geometries.




