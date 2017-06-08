# Time Zones

![Time zones](./timezones.png)

This map is based on [Eric Mullers time zone map](http://efele.net/maps/tz/world/) the [time zone map provided by CIA](https://www.cia.gov/library/publications/the-world-factbook/graphics/ref_maps/physical/pdf/standard_time_zones_of_the_world.pdf) and on the [date line from natural earth data](http://www.naturalearthdata.com/downloads/110m-physical-vectors/110m-geographic-lines/).

Eric Muller's IANA time zones are merged by UTC offset (tz_world.shp). Territorial borders at sea are ignored. Instead we use the time zones as defined by CIA.

A simplified (850kb) version is provided in geojson format. [mapshaper.org](http://www.mapshaper.org)'s visvalingam algorithm was used to acquire an 8% simplification.

[Example Application](http://ia.arch.ethz.ch/datamap/show.html)
