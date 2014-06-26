Data Catalog Guide
====

###File Formats and How to Open Them

**[CSV (Comma-Separated Value)](http://en.wikipedia.org/wiki/Comma-separated_values)**
* What: A tabular (spreadsheet) data format, where the column values are separated by commas. CSV files are both human and machine readable. In the wild, you may see many other "[delimiters](http://en.wikipedia.org/wiki/Delimiter-separated_values)" used, including tabs.
* How: Many applications, including Microsoft Excel, [OpenOffice](https://www.openoffice.org/), and [Google Docs](https://drive.google.com) and by text editors like [Sublime Text](http://www.sublimetext.com/), [TextWrangler](http://www.barebones.com/products/textwrangler/), Apple TextEdit, and Microsoft Notepad. When the CSV includes geographic coordinates, you may also open them in desktop mapping applications, such as [TileMill](https://www.mapbox.com/tilemill/) and [QGIS](http://www.qgis.org/), and with web-mapping tools, like [GeoJSON.io](http://geojson.io/) and [CartoDB](http://cartodb.com/).

**[JSON (JavaScript Object Notation)](http://en.wikipedia.org/wiki/JSON)**
* What: JSON is an easily human and machine readable open standard format, which transmits data objects consisting of attribute-value pairs. [GeoJSON](http://en.wikipedia.org/wiki/GeoJSON) is an extension of JSON that allows for the encoding of simple geographical features (points, lines and polygons) along with non-spatial attributes. [TopoJSON](https://github.com/mbostock/topojson/wiki) itself extends GeoJSON by "stitching" together shared geometries (e.g. borders). This reduces file size and also facilitates certain visualizations.
* How: GeoJSON files can be opened by desktop mapping applications and web-mapping tools, by R (with the right extensions), and by text editors. The online utility [ogr2ogr](http://ogre.adc4gis.com/) supports conversion from many geospatial file formats into GeoJSON.

**[KML (Keyhole Markup Language)](http://en.wikipedia.org/wiki/KML)**
* What: KML is an XML notation format used to express geographic information (longitude, latitude, altitude) on two- and three-dimensional maps. These files are easily readable by humans and machines.
* How: These files were originally developed for use with [Google Earth](https://www.google.com/earth/). They can also be opened in a variety of other desktop GIS applications and web-mapping platforms.

**[PNG (Portable Network Graphics)](http://en.wikipedia.org/wiki/Portable_Network_Graphics)**
* What: PNG is a [raster graphics](http://en.wikipedia.org/wiki/Raster_graphics) file format that supports [lossless data compression](http://en.wikipedia.org/wiki/Lossless_data_compression). The data catalog uses PNG format for general images.
* How: PNG files can be opened in any image viewer and can be pasted into documents.

**[SHP (ESRI Shapefile)](http://en.wikipedia.org/wiki/Shapefile)**
* What: Shapefiles are one of the most common geospatial formats out there. Like GeoJSON, shapefiles can store both spatial geometries (points, lines and polygons) and other feature attributes. In our data catalog, you will find shapefiles zipped together with a few other files (with extension .shx, .dbf, .sbn).
* How: In addition to ArcGIS, these files can be opened in free an open source GIS applications like QGIS. They can also be converted to many other data formats.

**[TIFF (Tagged Image File Format)](http://en.wikipedia.org/wiki/TIFF)**
* What: TIFF is a computer file format used to store [raster graphic](http://en.wikipedia.org/wiki/Raster_graphics) images, which are made up of usually rectangular grids of pixels. In our data catalog, TIFFs are used for geographic images (e.g. satellite imagery or [heat maps](http://en.wikipedia.org/wiki/Heat_map)). These TIFFs include georeferencing information (or metadata) that allow you to project them onto a map and are referred to as GeoTIFFs.
* How: TIFFs can be opened in image viewers, like Apple Preview. In the case of GeoTIFFs, you might find it useful to use GIS software, such as QGIS.

**[TXT (Text)](http://en.wikipedia.org/wiki/Text_file)**
* What: Essentially just textual data without stylistic formatting commands. All metadata is currently stored in TXT format, though this may change when a new data management platform is adopted.
* How: Can be opened in any text editor.

###Getting the Data

###Understanding the Data

###Using the Data
