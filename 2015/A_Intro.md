Motivation
==========

Hello world
-----------

![pic](https://raw.githubusercontent.com/Japhilko/GeoData/master/data/figure/FraMauroDetailedMap.jpeg.jpg)

-   Drawing maps has a long history
-   Fra Mauro map (1450) is the greatest memorial of medieval
    cartography
-   Source: [Wikipedia](https://en.wikipedia.org/wiki/Fra_Mauro_map)

Migrant route to Germany
------------------------

![pic](http://ichef.bbci.co.uk/news/624/cpsprodpb/32F6/production/_85164031_migrant_journeys_turkey_to_germany_624.png)

-   Used at BBC - get an overview of more maps like this
    [here](http://www.lib.utexas.edu/maps/)

The road to Europe
------------------

Source: [The
Independent](http://www.independent.co.uk/incoming/article10471117.ece/alternates/w460/Migrant-Map-Website.jpg)

![pic](http://www.independent.co.uk/incoming/article10471117.ece/alternates/w460/Migrant-Map-Website.jpg)

-   Data on the conflict in Syria -
    [UNHCR](http://data.unhcr.org/syrianrefugees/regional.php)

-   Analysis on [Syrian Refugee Settlement Clinic
    Locations](http://www.r-bloggers.com/syrian-refugee-settlement-clinic-locations/)
    with R

GDP per capita
--------------

Data source: [World Development
Indicators](http://data.worldbank.org/data-catalog/world-development-indicators)

![](A_Intro_files/figure-markdown_strict/unnamed-chunk-5-1.png)

GDP in German federal states
----------------------------

GDP in billion Euro

![pic](https://raw.githubusercontent.com/Japhilko/GeoData/master/data/figure/BIP2BLA.png)

-   Map produced with R-package
    [sp](https://cran.r-project.org/web/packages/sp/index.html)

-   Data source:
    [Wikipedia](https://de.wikipedia.org/wiki/Land_%28Deutschland%29)

-   Polygon source: Global Administrative Areas
    ([GADM](http://www.gadm.org/))

More detailed - more interesting?
---------------------------------

Social index - Proportion of social benefits recipients in Berlin

![pic](http://www.tagesspiegel.de/images/sozialhilfeempfaenger/1487336/5-format11.jpg)

Source:
[Tagesspiegel](http://www.tagesspiegel.de/images/sozialhilfeempfaenger/1487336/5-format11.jpg)

Is the necessary data available?
--------------------------------

![pic](https://raw.githubusercontent.com/Japhilko/GeoData/master/data/figure/Zensus_Mannheim2.png)[Source](https://atlas.zensus2011.de/)

The spatial perspective...
--------------------------

-   ... is relevant to get an overview of current developments

-   ... is relevant to understand circumstances.

### But how to get the adequate data?

-   Often the necessary data is not available
-   More spatial visualisations are possible with data from web 2.0. If
    we use Application Programming Interface (API)

A little quiz - which town is it?
---------------------------------

![pic](http://images.fastcompany.com/upload/4621770959_383261aebe_b.jpg)

Background info
---------------

-   maps of photographic/traffic activity around the world
-   data from [flickr](https://www.flickr.com/) used
-   guess about picture taker's mode of transportation
-   time stamps and distance traveled between a user's pictures
    -   Black is walking (less than 7mph),
    -   Red is bicycling or equivalent speed (less than 19mph),
    -   Blue is motor vehicles on normal roads (less than 43mph);
    -   Green is freeways or rapid transit.

New York
--------

![pic](http://images.fastcompany.com/upload/4621770959_383261aebe_b.jpg)

Source: [Eric
Fischer](http://www.fastcompany.com/1652550/infographic-day-using-flickr-geotags-map-worlds-cities-updated)

-   [The geotaggers world
    atlas](https://www.flickr.com/photos/walkingsf/sets/72157623971287575/)

World Map Of Touristiness
-------------------------

![pic](http://s3.amazonaws.com/infobeautiful2/550_touristyness.jpg)

Source: [Touristiness](http://www.bluemoon.ee/~ahti/touristiness-map/)

Based on tourist pictures uploaded on
[panoramio](http://www.panoramio.com/)

Tracking Taxis Across Manhattan
-------------------------------

![pic](http://images.fastcompany.com/upload/Screen%20shot%202010-04-05%20at%209.05.50%20AM.png)

Source: [The New York
Times](http://www.fastcompany.com/1607065/infographic-day-tracking-taxis-across-manhattan)

Target / Motivation
-------------------

<strong>The target is to visualize <FONT COLOR="red"> social </FONT>
aspects in maps.</strong>

<a href="http://spatial.ly/2015/07/15minutemap/" target="_blank"><img src="http://spatial.ly/wp-content/uploads/2015/07/hurricanes.jpg" width="240" height="180" border="10" /></a>
<a href="https://www.mapbox.com/blog/osm-community-visualized/" target="_blank"><img src="https://farm3.staticflickr.com/2849/9774592706_3c2eafe310_c.jpg" width="240" height="180" border="10" /></a>
<a href="https://uchicagoconsulting.wordpress.com/" target="_blank"><img src="https://uchicagoconsulting.files.wordpress.com/2011/04/5.png?w=450&h=309" width="240" height="180" border="10" /></a>
<a href="http://blogs.casa.ucl.ac.uk/category/r/" target="_blank"><img src="http://spatial.ly/wp-content/uploads/2014/07/journey_to_work_web.gif" width="240" height="180" border="10" /></a>
<a href="http://statmatt.com/r-ggmap-examples-plot-overlay-spatial-data/" target="_blank"><img src="http://statmatt.com/wp-content/uploads/2014/01/Baltimore_3.jpg" width="240" height="180" border="10" /></a>
<a href="http://www.pilod.nl/w/images/6/62/D9-fig4.jpg" target="_blank"><img src="http://www.pilod.nl/w/images/6/62/D9-fig4.jpg" width="240" height="180" border="10" /></a>

More [examples](http://spatial.ly/blog/)

Spatial? - Motivation
---------------------

-   Massive amounts of data ... and growing!
-   Often freely accessible on the web (e.g. through APIs)
-   Often unstructured or semi-structured (e.g. web documents, news
    archives), often heterogeneous
-   Often not intended for geographic purposes, but implicitly
    containing geographic info implicitly (Web 2.0)
-   Often with little or no metadata

[Examples](https://www.flickr.com/groups/qgis/pool)

Organisation
============

Targets
-------

I want to....

-   ... show you examples of useful and less useful visualisations and
    applications.
-   ... talk about the developments of maps/geography.
-   ... clarify, why it is important for social sciences.
-   ... show you how to produce your own maps/visualisations.
-   ... tell you where you can find data.

Targets
-------

Every participant should present his/her own maps.

-   Presentation of toolbox (R, Google API, OpenStreetMap etc.)
-   Learning by doing is very important

Background
==========

Personal information
--------------------

![pic](https://raw.githubusercontent.com/Japhilko/GeoData/master/data/figure/Places.png)

University of Trier
-------------------

![pic](https://www.uni-trier.de/fileadmin/_processed_/csm_campus_01_dbe11f5d99.gif)

Source: [Website with city
maps](https://www.uni-trier.de/fileadmin/_processed_/csm_campus_01_dbe11f5d99.gif)

Erasmus - Univerity Lyon III
----------------------------

![pic](http://www.orangesmile.com/common/img_city_maps_560/lyon-map-0.jpg)

Source:
[orangesmile](http://www.orangesmile.com/common/img_city_maps_560/lyon-map-0.jpg)

Organisation Gesis
------------------

Five departments - Survey Design and Methodology

-   Monitoring Society and Social Change

-   Data Archive for the Social Sciences

-   Computational Social Science

-   Knowledge Technologies for the Social Sciences

Gesis
-----

GESIS is:

-   Infrastructure Services for social sciences

-   over 250 employees at three sites (Mannheim, Cologne)

GESIS offers:

-   Consulting for research projects in all phases

-   Research based services

Tasks GESIS-Team Statistics:
----------------------------

Consulting and research on ...

-   Planning of survey designs
-   Development of sample designs for face-to-face, written, and
    telephone-assisted surveys
-   Data analysis and visualisation

Your background?
----------------

-   Where do you come from?
-   What are you studying?
-   What are your main research interests?

Tools for this course
=====================

Tools and services
------------------

![pic](http://developer.r-project.org/Logo/Rlogo-5.jpg)

![pic21](http://www.webmasterpro.de/portal/news/2010/11/25/microsoft-arbeitet-mit-openstreetmap-zusammen.html/image/800px-OSM_Logo.svg.png/scale/250x400/)

![pic21](http://wiki.openstreetmap.org/w/images/thumb/b/b5/Overpass_API_logo.svg/400px-Overpass_API_logo.svg.png)

![pic21](http://st1.bgr.in/wp-content/uploads/2014/06/google-maps-logo.jpg)

Why use R
=========

Why use R - It's open source
----------------------------

-   It's free
-   It's open source
-   ...

> R is the leading tool for statistics, data analysis, and machine
> learning. It is more than a statistical package; its a programming
> language, so you can create your own objects, functions, and packages.

Source: <http://www.r-bloggers.com/why-use-r/>

Why use R - many specific packages
----------------------------------

A big number of (very specific) packages:

![pic21](http://www.kdnuggets.com/wp-content/uploads/top-20-r-packages-downloads.jpg)

[Overview of available packages on CRAN](http://www.r-pkg.org/)

Why use R - overview of reasons
-------------------------------

![pic21](http://www.edureka.co/blog/wp-content/uploads/2013/06/bar-learn-r-img11.png)

Why use R - interfaces
----------------------

-   Interfaces with other programs, for example
    [Javascript](http://www.w3schools.com/js/),
    [ArcGis](http://uwm.edu/software/arcgis/),
    [GDAL](http://www.gdal.org/) and others...

![pic21](https://jresponse.net/blog/wp-content/uploads/2015/04/javascript-logo-png-200x200.png)
![p](http://uwm.edu/software/wp-content/uploads/sites/76/2014/06/ESRI_ARCMAP_transparente.png)

Why use R - GIS
---------------

R can be used as geographic information systems (GIS)

-   R and
    [qgis](http://upload.wikimedia.org/wikipedia/commons/thumb/7/71/QGis_Logo.png/300px-QGis_Logo.png)

-   Virgilio Gómez-Rubio - [Applied Spatial Data Analysis with
    R](http://www.uclm.es/profesorado/vgomez/useR2015/)

-   [spatstat: Spatial Point Pattern
    Analysis](http://cran.r-project.org/web/packages/spatstat/index.html)

-   [Task view mapping](https://github.com/ropensci/maptools)

-   [giswerk](http://giswerk.org/)

Why use R - visualisation
-------------------------

Because it is possible to create nice graphics:

-   [Producing Simple Graphs with R](http://www.harding.edu/fmccown/r/)

-   [Lattice](http://stat.ethz.ch/R-manual/R-devel/library/lattice/html/Lattice.html)

-   [R Graphics by Paul
    Murrell](https://www.stat.auckland.ac.nz/~paul/RGraphics/rgraphics.html)

-   [Possibilities to
    visualize](http://mesa.ac.nz/wp-content/uploads/2012/05/all_presentations.pdf)

-   [ggplot2
    Tutorial](http://www.ceb-institute.org/bbs/wp-content/uploads/2011/09/handout_ggplot2.pdf)

-   [Visualizing data in
    R](https://dl.dropboxusercontent.com/u/24648660/ggmap%201.pdf)

-   [Interview Hadley Wickham - R-Project Data Visualization
    Guru](http://decisionstats.com/2010/01/12/interview-hadley-wickham-r-project-data-visualization-guru/)

[Github](https://github.com/) stack
-----------------------------------

![pic21](http://40.media.tumblr.com/19f7c16e223f2bd2e12c0bb4b6f5f666/tumblr_mzr6zsI3TK1tqzc7ko1_1280.png)

Using Github
============

Github page
-----------

-   All relevant resources for this course will be available at:

<https://github.com/Japhilko/GeoData>

If you are interested in what is behind the scenes:

-   [Introduction to
    Github](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1)

First steps in R
================

How to learn R
--------------

-   [Manuals on the R-project
    webpage](http://cran.r-project.org/manuals.html)

-   Thomas Girke - [Programming in
    R](http://manuals.bioinformatics.ucr.edu/home/programming-in-r)

-   Use [Reference
    cards](http://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf),
    plot them and have them next to your computer

-   [How to get help in
    R](http://itfeature.com/tag/how-to-get-help-in-r)

I will try to keep it simple and provide lots of resources.

Basic R
-------

![pic21](https://erpinr.files.wordpress.com/2014/04/rsession.png%3Fw%3D620%26h%3D500)

Download and install R
----------------------

-   Click
    [here](http://mirrors.softliste.de/cran/bin/windows/base/R-3.2.2-win.exe)
    to download R for Windows.

-   R for other platforms (Linux and Mac OS) is available under:

<http://mirrors.softliste.de/cran/>

Rstudio
-------

![pic21](http://rprogramming.net/wp-content/uploads/2012/10/RStudio-Screenshot.png)
Source: [R-programming](http://rprogramming.net/)