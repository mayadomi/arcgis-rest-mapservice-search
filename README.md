# Search/List layers with a given field-name in an ArcGIS REST Service

This is a quick snippet of code to search for a field name in an ArcGIS REST service.

This was borne out of a need to find layers across a number of services that had a particular field name. So I built this as an exercise in better understanding JS promise-chaining and creating something reusable.

It's extended from ESRI sample code here: https://developers.arcgis.com/javascript/latest/sample-code/request/

Hosted on GitHub Pages here https://mayadomi.github.io/arcgis-rest-mapservice-search/

## Bugs
CORS-handling

## Improvements
Options for broader searches - eg wildcards, partial results, case sensitivity etc. Currently searching is by exact name/case only
