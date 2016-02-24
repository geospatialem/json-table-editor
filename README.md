# Json Table Editor
An attempt to create a Json table editor, without a spatial component.

## Main Goals
* Allow the user to input in the Json text
* Display the Json in-full
* Display a table
* Allow the user to delete a field.
* Allow the user to change a field name.
* Allow the user to change values within the fields.

## Design Notes
* **_Functionality is key, look is secondary._**
* The interface could hold a button that would *alter* the settings. This would speed up processing time, instead of making changes on-the-fly.
* Allow users to input in a url that will grab the Json.
* Table view example: [Geojson.io](http://geojson.io), or the [GitHub repo](https://github.com/mapbox/geojson.io).
* Button example: [Json Editor Online](http://jsoneditoronline.org), or the [Github Repo](https://github.com/josdejong/jsoneditor).
* *Nice to have option:* Sortable values that move the entire row when sorting.
