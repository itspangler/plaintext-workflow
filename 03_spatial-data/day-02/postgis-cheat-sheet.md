# A quick intro to PostGIS

### What is it?

PostGIS is a spatial plugin for PostgreSQL, the free and open-source database software.

### Again...

Right—sorry!

**PostgreSQL** is a database software. **SQL** is a language you can use to query PostgreSQL (and many other) databases—that's where the "SQL" in the name comes from.

| ![csv](https://docs.microsoft.com/en-us/power-query/images/me-combine-files-csv-sample-csv-file.png) |
| ---------------------------------------------------------------------------------------------------- |
| A `.csv` file                                                                                                   |

A **database** is simply a collection of structured data (and structured data is data that's been formatted consistently, for example, like comma separated values `.csv`).

| ![db](https://www.databasejournal.com/wp-content/uploads/2021/12/Post01.png) |
| ---------------------------------------------------------------------------- |
| A screenshot of a PostgreSQL database and some SQL code                                                                             |

A **spatial database**, then, is a database that can store spatial data—not just latitudes and longitudes, but geometry formats like polygons and lines. PostgreSQL competes with software like Microsoft Access, and PostGIS competes with software like ArcGIS and MapInfo.

| ![pgis](https://live.osgeo.org/en/_images/postgis_screenshot.png) |
| ----------------------------------------------------------------- |
| A similar screenshot to the previous one; it's in the same application, but we can see that there are two fields in the table for spatial data: `shape_leng` and `shape_area`                                                                  |



### So why do I want to use this stuff?

We already talked a little bit about QGIS. Let's say you're deliberating whether to start a new project in PostGIS, but you're torn; it's perfectly easy to store your data as `.shp` or `.geojson` format in a directory on your computer.

In many circumstances, it still makes a great deal of sense to do this. Understanding spatial databases will just extend your capability, and allow you to scale up to bigger projects, faster analyses, and

Spatial databases are especially helpful in the following circumstances:
- Data will be used repeatedly for more than 6 months
- Multiple users will be editing the same dataset
- Data is being reused across multiple projects
- Data retention is crucial (backups are needed)
