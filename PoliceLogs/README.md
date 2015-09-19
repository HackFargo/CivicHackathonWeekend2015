These are simple json copies of a subset of the Fargo police
logs through 9-18-2015. Basically, I just did a single
search over time for a specific call type: Fireworks,
Impaired Driver, Bike Theft, etc.

If I get time, I'll create .geojson versions of these
that are also geocoded through Hack Fargo's reverse
gocoding GIS system.

You may explore on your own directly with the JSON API. 
There are also logs for other cities like Moorhead and
Dilworth (and others).

Here's an example URL:

You can change Venue to see other cities on the RRRDC
service. Start Date and End Date are self explanatory,
but beware that you'll get a HTTP 500 if there is too
much data over the time range (so you'll have to narrow
the range and concatonate). You can leave out the
CallType, or use it as a filter. 

To see what values work for Call Type, just check out
the frontend website. Click search options, and see
the values that are in the dropdown. There's a ton.

API URL: http://services.rrrdc.com/dispatchlogs/Service.asmx/SearchDispatchLogJSON?callback=x&Venue=FGO&StartDate=09%2F19%2F2014&EndDate=09%2F19%2F2015&Address=&Description=&CallType=Bicycle%20-%20Theft
Frontend: http://www.cityoffargo.com/CityInfo/Departments/Police/DispatchLog/FargoPDDispatchLogs.aspx
