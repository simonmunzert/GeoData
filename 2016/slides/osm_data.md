# Datenquelle OpenStreetMap
Jan-Philipp Kolb  
Thu Mar 10 08:27:12 2016  

## [OpenStreetMap](http://www.openstreetmap.de/) Projekt


> OpenStreetMap.org ist ein im Jahre 2004 gegründetes internationales Projekt mit dem Ziel, eine freie Weltkarte zu erschaffen. Dafür sammeln wir weltweit Daten über Straßen, Eisenbahnen, Flüsse, Wälder, Häuser und vieles mehr. 

<http://www.openstreetmap.de/>


## OpenStreetMap

> OpenStreetMap (OSM) ist ein kollaboratives Projekt um eine editierbare Weltkarte zu erzeugen.

[Wikipedia - OpenStreetMap](https://en.wikipedia.org/wiki/OpenStreetMap)

## [OSM Map Features](http://wiki.openstreetmap.org/wiki/DE:Map_Features)

<http://wiki.openstreetmap.org/wiki/DE:Map_Features>

![osmMapFeatues](http://docs.cartodb.com/img/layout/tutorials/overpassturbo/img2.efe758ad.png)


## [Overpass Turbo](https://overpass-turbo.eu/)

<https://overpass-turbo.eu/>

![OverpassTurbo](http://blog.openstreetmap.de/wp-uploads/2014/01/Overpass_turbo_query_wizard_result_DE.png)


## Query Overpass

```
node
  [amenity=bar]
  ({{bbox}});
out;
```

## Download von OpenStreetMap Daten

- Ausschnitte von OpenStreetMap für einzelne Städte ([metro extracts](https://mapzen.com/data/metro-extracts/))

<https://mapzen.com/data/metro-extracts/>

- Über Geofabrik lassen sich aktuelle Ausschnitte herunterladen (auch Shapefiles)

<http://download.geofabrik.de/>

- Kartendaten ([openaprs](http://www.openaprs.net/))

## [PostgreSQL](http://www.postgresql.org/)

- PostgreSQL hat den Vorteil, dass es Open-Source ist.

- [Download PostreSQL](http://www.postgresql.org/download/windows/)

<http://www.postgresql.org/download/windows/>

- [Einführung](https://datashenanigan.wordpress.com/2015/05/18/getting-started-with-postgresql-in-r/)

<https://datashenanigan.wordpress.com/2015/05/18/getting-started-with-postgresql-in-r/>

- Sehr empfehlenswert: Arbeiten mit pgAdmin III
- Beispiel: um Verknüpfung zu einer Datenbank herzustellen - Doppelklick auf den Server in pgAdmin III


## PostGIS

- [PostGIS Erweiterung](http://postgis.net/install/)

<http://postgis.net/install/>

```
CREATE EXTENSION postgis;
```


## osm2pgsql - Import der OSM Daten in PostgreSQL

- Läuft unter Linux deutlich besser

```
osm2pgsql -c -d osmBerlin --slim -C  -k  berlin-latest.osm.pbf
```

## Nutze bspw. [QGIS](http://www.qgis.org/de/site/) um Shapefiles zu extrahieren

![qgis](https://underdark.files.wordpress.com/2012/07/stamen_watercolor1.png?w=700)

- [Plugin OpenLayers](http://www.qgistutorials.com/de/docs/downloading_osm_data.html)

## Links

- [Wiki zum Downlaod](http://wiki.openstreetmap.org/wiki/Downloading_data)

<http://wiki.openstreetmap.org/wiki/Downloading_data>

- Liste möglicher Datenquellen für räumliche Analysen ([weltweit](http://wiki.openstreetmap.org/wiki/Potential_Datasources), [Deutschland](http://wiki.openstreetmap.org/wiki/DE:Potential_Datasources)
)

<http://wiki.openstreetmap.org/wiki/Potential_Datasources>

- [SALB](http://wiki.openstreetmap.org/wiki/SALB) - Administrative Grenzen

<http://wiki.openstreetmap.org/wiki/SALB>
