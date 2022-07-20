# Resources for getting started in QGIS

### What's QGIS?

QGIS is a free and open-source **geographic information system (GIS)**, or software for creating, manipulating, and analyzing spatial data.

### Lots to take in, there...

Let's start with spatial data.

**Spatial data** is data that contains machine-readable information about where something's located in relation to the earth.

That means you might have data with spatial information (e.g., a Word document, report, or journal article with city names) might not necessarily be *spatial data*. Conversely, you might have spatial data that has no meaningful descriptive information attached to it.

### Is all spatial data the same?

Not at all!

There are two main kinds of spatial data: **raster** and **vector**.

Raster data is like a giant piece of gridded paper, where each cell—or pixel—is a section of the Earth's surface. It's often used to represent continuous phenoemona, like temperature.

![raster](https://cartinal.leventhalmap.org/assets/img/RasterMapExampleAirQuality.161995ae.jpeg)

Vector data is like a game of connect the dots, where dots can be connected as points, lines, or polygons. It's often used to represent discrete phenomena, like county boundaries or bus routes.

![vector](https://cartinal.leventhalmap.org/assets/img/VectorMapExampleBostonDeathRates.5a8a1785.png)

### How does a computer know how to associate spatial data with descriptive information?

The process of associating descriptive information with spatial data is called a **table join**. Table joins use common identifers between tabular data and spatial data to attach descriptive information with actual geographies. Those common identifiers are usually called **GEOIDs**, but they could be anything, as long as they're consistent between the descriptive data and the spatial data.

| ![tablejoin](https://cartinal.leventhalmap.org/assets/img/joining-features-attributes.71eaf04a.jpg) |
| --------------------------------------------------------------------------------------------------- |
| Descriptive data (numbers) being connected to spatial data (polygons). Drawings by [Tess McCann](https://tessmccann.com/)

### Where can I get QGIS?

It's super easy to [download from the QGIS website](https://www.qgis.org/en/site/forusers/download.html). I usually recommend downloading the long-term release, which at the time of writing is 3.22.

If you've never downloaded before, and you're on a Mac, you might have to go into your security preferences in order to allow your machine to run the app.

Once you get it running, you'll see something sort of like this:

![qgis](https://cartinal.leventhalmap.org/assets/img/1-qgis-labeled.e4e44daa.gif)

There's a nice [guide from the Leventhal Map & Education Center](https://cartinal.leventhalmap.org/guides/get-started-qgis/#what-is-qgis) with instructions on getting started with QGIS. If you've never used the software before, I recommend checking it out. You might also look into [LMEC's Making Sense of Maps & Data course](https://cartinal.leventhalmap.org/guides/making-sense-maps-data/session-2/part-2.html#raster-data-the-earth-as-a-spreadsheet), from which I cribbed the images in this cheat sheet.

# [Click this link to return to the assignment](./)
