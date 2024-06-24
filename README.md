# OSM Bike Parking Map

This map uses crowd-sourced OpenStreetMap (OSM) data to illustrate the locations of bicycle parking, amenities, and bicycle lanes.

You can select your administrative/city boundary by changing the 'rel' parameter at the end of the URL, and adding the map as an iframe to your own webpages.

You can find your boundary parameter using OSM's Nominatim tool at https://nominatim.openstreetmap.org/ui/search.html.

Using this tool and searching for Cleveland, click your correct result and scroll down to the 'OSM' row, and here you will see "relation 182130". "182130" is the value you will put for your URL link.

Your final iframe src url will be "https://trivisonno.github.io/bikerackmap/?rel=182130" if you want to show Cleveland's data.

Larger cities take longer to load because there is more data.