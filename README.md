classes
=======

Python-functions that help to evaluate the input from command line

* **getIOFiles**

	- *Parameters:* -i <inputfile> -o <outputfile>'
	- *Usage:* not used so far (used as dummy-function)

* **getIOFilesObject**

	- *Parameters:* -i <inputfile> -o <outputfile> -f <feature>'
	- *Usage:* Build GeoJSON-Features from TopoJSON-Features
	- *Examples:* https://github.com/milkbread/TopoJSON-Arcs/blob/master/makeGeoJSON.py

* **getIOFilesRoute**

	- *Parameters:* -o <outputfile> -s <start> -e <end>'
	- *Usage:* Convert Json-Route-Features provided by [Cloudmade routing service](http://cloudmade.com/documentation/routing)
	- *Examples:* https://github.com/milkbread/SnakesSmoothing/blob/master/routeToJson.py


* **getIOFilesThreshold**

	- *Parameters:* -i <inputfile> -o <outputfile> -t <threshold>'
	- *Usage:* Simplify some geometries, needs a threshold (or tolerance), so you have to request that too
	- *Examples:* 
		* https://github.com/milkbread/SnakesSmoothing/blob/master/smoothToFeatClass.py
		* https://github.com/milkbread/Visvalingam-Wyatt/blob/master/simplify.py

*Current version: 0.2*
