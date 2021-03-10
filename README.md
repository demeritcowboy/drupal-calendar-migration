# drupal-calendar-migration
Migrate a json file into drupal as nodes intended as calendar-like entries.

You install this on the destination site.

## TODOS

* The source view can be installed on the source site with the file "todo.this is the view on the source site.txt" but that could go in its own module.
* There would also be a Full Calendar view on the destination site which pulls its data from "calendarentry" nodes.
* There doesn't seem to be a way to have a configurable url for the source url, meaning you have to edit the migration file and set it before you install this module. That might make sense if you're doing a one-time migration but otherwise seems awkward. You can override it in code to pull from somewhere, but at the moment there isn't a field in the UI you can just edit after install to set the source url.
* Authentication similarly needs to be hardcoded into the file before install, so I've left it out for the moment.
