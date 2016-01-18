Step 4
======

  * Prepare the statistical data
  * Select some colors
  * Color the municipalities by attribute
  * Static domain
  * dataById
  * Try to change the key of the map? (urban / agriculture / forest / unproductive)

Prepare statistical data:

  Download from http://www.bfs.admin.ch/bfs/portal/de/index/regionen/02/daten.html

  Delete unnecessary columns:

  Needed:
    Gemeindecode
    Gemeindename
    Gesamtfläche in km²
    Siedlungsfläche in %
    Landwirtschaftsfläche in %
    Wald und Gehölze in %
    Unproduktive Fläche in %

  Delete headers, resp. replace them by code
    id
    name
    area
    urban
    agriculture
    forest
    unproductive

  Also delete comments at bottom of file

  Save as
    /data/areastatistics.csv

    Format: Text CSV (.csv)

    Character set: Unicode (UTF-8)
    Field delimiter: ,
    Text delimiter: ""


Colors:

  http://colorbrewer2.org/

  Select a color range, e.g. YlGnBu

  Set number of data classes: 9

  Export: CSS classes

  Add them to the custom styles


Code
----

https://github.com/lvonlanthen/data-map/blob/step-04/index.html
