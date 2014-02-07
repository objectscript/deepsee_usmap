deepsee_usmap
=============

- Execute do ##class(USA.Utils).Populate()
- Move the marker icons in /csp/broker/images
- In the widget "Map" indicate (if not, the markers will be standard) (now there are registered links to the server hosting images)
Marker Special Icon = /csp/broker/images/mapMarkerPink.png
Marker Icon = /csp/broker/images/mapMarkerAzure.png


Changes in the portlet
Added options :
Marker Special Icon - icon address for a special marker
Marker Special Property - property name of the sample for choosing special icons (0 /1). For example - regional centers are marked with the special marker, and the rest of the city - with a plain one, if Marker Special Icon = "", the marker will look like the Marker Icon, and if Marker Icon = "", then plain markers by Google are used.
onrightclickpolygon - to display the information about the polygon in infowindow
onrightclickmarker - to display the information about the marker in infowindow, in case if marker duplicates the polygon

Added range slider (jquery)
Jquery connection to USA.MapPortlet - Method %DrawHTML()
now downloads from Google.
