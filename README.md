</strong></h1>Aufgabe 6</strong></h1>
<h4>Authors:  Jonathan Mader, matr.Nr.: 502644 - Erkam Dogan, matr.Nr.: 508236</h4>

Our files for the 6th Assignment of the Geosoftware 1 course

The first website gives information about the busstops in Münster and lets the user get information about the time of depature,
the busline and the direction of the bus from a choosen busstop that is clicked on on the map.
It also allows you to choose a location that is stored in the database and lets you get information about the
nearest busstops, that would be the distance in kilometers, the busstop name, the direction and the coordinates.

The other website is a location creator, where the user can input new locations either by setting a marker on the map via leaflet drawm
enter a adress which will get converted to GeoJSON via forward geocoding or by using the browser location. These locations can also be updated
or deleted when they are stored in the mongoDB.

<h2>Tutorial</h2>

For the forward geocoding you need a MapBox access Token at var access_token = "access Token" in /public/locationcreationmap

VS-Code Terminal:

$ npm init and confirm everything.
After that 
$ npm install package.json"

If the two steps above were successfull, you need to install <br>
express <br>
mongodb <br>
body-parser <br>
jquery <br>
for the app to work with 
$ npm install ...

This will add the dependencies needed for the app to the package.json file which is needed later for the Dockerfile


