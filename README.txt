Google Maps Simple Text Field Formatter

This module is a field formatter for Drupal 7 text fields. It allows you to
enter a single-line address that Google Maps would recognize in a plain text
field, such as:
   100 Madison Ave, New York, NY
And then on your Manage Display screen (or in Views field setup), you can choose
to display the field as an embedded iframe Google Map, a link to a Google Maps
map, or both.

No Google Maps API, JavaScript downloads, etc. are required. This just uses
Google Maps' iframe embedding capability to embed a map at a given address that
Google Maps can recognize, or to make a link to Google Maps.

To install and use:
- Upload/unzip to your Drupal 7 sites/all/modules directory (or
  sites/default/modules or whatever).
- Enable the module.
- Add a plain Text field to your content type. You probably should add some
  Help text to the field to explain that a one-line address that Google Maps can
  recognize needs to be entered, and that the output will be formatted with a
  map (or a link or both, depending on how you are using this field).
- On the Manage Display screen, or when adding this field to Views, choose one
  of the three provided mapping formatters.
- If desired, click the button to change the field display settings.

Note: this is just a sandbox project so far... There are no field validation
steps or theme overrides, and it just uses a regular Text field rather than
defining its own field. The display settings let you choose the size of the map,
the text for the map link, the map zoom level (applies to both embedded and
linked map), and whether to display information about the address in a bubble,
but that's pretty much it. Feel free to download and modify to fit your
purposes!
