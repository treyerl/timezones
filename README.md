# Time Zones

This map is based on [Eric Mullers time zone map](http://efele.net/maps/tz/world/) the [time zone map provided by CIA](https://www.cia.gov/library/publications/the-world-factbook/graphics/ref_maps/physical/pdf/standard_time_zones_of_the_world.pdf) and on the [date line from natural earth data](http://www.naturalearthdata.com/downloads/110m-physical-vectors/110m-geographic-lines/).

Eric Muller's IANA time zones are merged by UTC offset (tz_world.shp). Territorial borders at sea are ignored. Instead we use the time zones as defined on the map by CIA.

The time zones shapefile has a size of ~7MB. A simplified version is provided in geojson format. [mapshaper.org](http://www.mapshaper.org) was used to acquire the simplified version (8% simplification, visvalingam, weighted, prevent shape removal, use planar geometry).
