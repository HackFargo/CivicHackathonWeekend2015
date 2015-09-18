CDL Crop Data
============

This is aggregate crop data just for Cass County. You can go 
and pull any county you like. 

There's a huge map that has all kinds of stuff.
http://nassgeodata.gmu.edu/CropScape/

To generate a document, hit a url that looks like this. fmt can be txt, json or csv:
http://nassgeodata.gmu.edu:8080/axis2/services/CDLService/GetCDLStat?year=1997&fips=38017&format=csv

You'll then get a url back that you can use to access your document.
I found the fips code for cass county on Wikipedia. [More info on the API](http://nassgeodata.gmu.edu/CropScape/devhelp/help.html)
