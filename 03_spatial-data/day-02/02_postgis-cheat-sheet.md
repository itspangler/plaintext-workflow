# A quick intro to PostGIS

### What is it?

PostGIS is a spatial plugin for PostgreSQL, the free and open-source database software.

### Again...

Right—sorry!

**PostgreSQL** is a database software that uses **SQL**.

A **database** is simply a collection of structured data (and structured data is data that's been formatted consistently, for example, like comma separated values `.csv`).

| ![csv](https://docs.microsoft.com/en-us/power-query/images/me-combine-files-csv-sample-csv-file.png) |
| ---------------------------------------------------------------------------------------------------- |
| A `.csv` file                                                                                                   |

**SQL** is a language you can use to query PostgreSQL (and many other) databases—that's where the "SQL" in the name comes from.


| ![db](https://www.databasejournal.com/wp-content/uploads/2021/12/Post01.png) |
| ---------------------------------------------------------------------------- |
| A screenshot of a PostgreSQL database queried with some SQL code                                                                             |

A **spatial database**, then, is a database that can store spatial data—not just latitudes and longitudes, but geometry formats like polygons and lines. PostgreSQL competes with software like Microsoft Access, and PostGIS competes with software like ArcGIS and MapInfo.

| ![pgis](https://live.osgeo.org/en/_images/postgis_screenshot.png) |
| ----------------------------------------------------------------- |
| A similar screenshot to the previous one; it's in the same application, but we can see that there are two fields in the table for spatial data: `shape_leng` and `shape_area`|

### So why do I want to use this stuff?

Let's say you're deliberating whether to make PostGIS the database for your new project, but you're torn; it's perfectly easy to store your data as `.shp` or `.geojson` format in a directory on your computer.

In many circumstances, it still makes a great deal of sense to store files on your local machine (you'll often see these referred to as "flat files"). Understanding spatial databases will just extend your capability, and allow you to scale up to bigger projects and faster analyses.

Spatial databases are especially helpful in the following scenarios:

- Data will be used repeatedly for more than 6 months
- Multiple users will be editing the same dataset
- Data is being reused across multiple projects
- Data retention is crucial (backups are needed)

If you have a big dataset, or a project that requires data to be accessed remotely via a web app, or you are collaborating with others on a long-term project that requires a "single source of truth" (e.g., a master data layer)—or if you envision any of these things might happen in the future—PostGIS will be useful for you.

### Where do I even start with using this?

Let's start with what a PostGIS database contains: **schemas** and **tables**.

**Schemas** are like buckets for your data. Think of them as a folder. You can create and store **tables** inside of a schema. When you open up PostGIS, it will intialize with a `public` schema by default.

Let's say you're working on a project about coyote sightings in the greater Boston area. In your `public` schema, you might include `polygon` data like a county boundary and Census block groups. In your `coyote-map` schema, you might include `point` data that contains coyote sightings, as well as modified versions of your polygon files, if necessary.

### What do the tables contain?

PostGIS has three primary ways of associating spatial data with a database:

- **Spatial data types** (like points, lines, and polygons)
- **Spatial indexing** (which is useful for geoprocessing)
- **Spatial functions** (such as SQL, or structured query language, which lets you perform spatial queries on a database)

![spatial data types](https://postgis.net/workshops/postgis-intro/_images/hierarchy.png)

### How do I integrate it with QGIS?

There are great tutorial videos and other instructions out there about how to get started with linking PostGIS and QGIS. The steps are basically:
1. Download QGIS
2. Download PostgreSQL
3. Install the PostGIS extension
4. Connect to your PostGIS database using the QGIS DB Manager

The DM Manager is a user interface for manipulating the contents of a PostGIS database directly from QGIS:

![dbmanager](https://docs.qgis.org/3.4/en/_images/db_manager1.png)

If you've used QGIS, you'll be familiar with geoprocessing functions like `buffers` and `intersects`, as well as selection queries like `select by location`. You've also probably had to wrestle with QGIS in order to re/format your fields as you work through a dataset.

The DB Manager allows you to perform all of these functions, and more, through simple text commands in the DB Manager.

Again, these are just some of many ways to query and manipulate spatial data. There's no universal, one-size-fits-all answer!

# [Click this link to return to the assignment](./)
