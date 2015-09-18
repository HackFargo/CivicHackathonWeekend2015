# CivicHackathonWeekend2015
General manifesto and data sets for the Civic Hackathon Weekend 2015

Philosophy
-----------

The theme of this hackathon is 'Civic Data'. We have provided
several data sets -- some new, some old -- that you are welcome
to use, or not use, for your project. There are also a bunch of
shape files that have relevant data from around the city of fargo.

The event is held at the Prairie Den in downtown Fargo, starting
at noon on Saturday 9/19 with demos at 4pm on Sunday. Try to get
some sleep -- we're closing up at 1am and opening at 10am.

Competition
-----------

Remember -- you may elect to build something useful or practical,
but this does not have to be the case. This is a *hackathon*, and
you're making a *hack*. Make something that leaves an impression. 
Something quirky, and clever. Something that makes the judges 
say "hey, now thats pretty neat". We want to see you do something
that is awesome. A successful hack shows creativity, depth, and a
wow factor. Something that no one would think possible in the 
scope of a weekend. 

This is a fun and light hearted competition. There will be prizes,
and demo/judging will happen at 4pm on Sunday. Judges will want to see
projects that relate, in some way, to life in Fargo. Naturally,
they will also be impressed if they see software that is functional
in some way, with extra points for ingenuity and usefulness.

Teams
------

You may work on your own, or with a team of up to 4 people. 

Ideas
-----

The best way to go about coming up with a project idea is to 
think about a life in the day of a citizen. Figure out what
that citizen cares about, what their job is, what their
passions and concerns are. Then build something that makes
their life better. For example, my hypothetical citizen 
could be a normal, every day person who just wants to be 
connected with resources around them -- or other people with
similar hobbies (think specific!). They could be a business
analyst who wants better tools for helping to make decisions.

For every unique person, you can think of some way that they
could interact with their city and people around them in
a better way. This could be through a new tool that helps
make decisions, or an app that connects people. Or just a
game that uses civic data sources and educates. Alerts
on events (social, or emergency). Information on flooding
or rail roads. Games and competition using real world
props. Heat maps and charts showing mosquitoes and bike
share correlation (maybe with twitter to back it up!).
The only limit is your imagination (and... maybe time!)

Be creative!

   * You could just work on analytics and correlations
   * You could make apps for other people to use
   * You could build a service that uses a data set 
     mashed up with something else
   * You could just have fun with it, and see what happens

You have until Sunday at 4pm!

Data Sets
=========

There are several data sets that are available for this hackathon. 
Some of the data is available to the public, other data has been
released just for this event. Feel free to ask questions, pick
through the various data, and even create your own if you want.

There's a whole bunch of GIS Shapefile data available. I've done
the leg work to a) curate the dozens of sets down into a few that
should be relevant for this event and b) convert them all into
GeoJSON, which is a flat web-friendly format. 

Shapefile Repository
--------------------

[Go check out the Hack Fargo Shapefile Repo](https://github.com/HackFargo/Shapefiles) -- seriously,
there's so much we can do with that. Get on it!

Some highlights from the Shapefile repo that are worth mention:

   * Voting precints and locations
   * Bike trails and shared paths
   * Fargo park locations and boundaries
   * Fargo Metro bus routes and transit stations
   * Schools, Colleges, Universities
   * Locations of railroad crossings and rail lines
   * Boundaries: City, Roads, River, Counties, States

More Data
----------

Additional data sets follow. Most of these are either available
in a folder in this repo, or through a link out to the internet.

   * Mosquito Trap Data. This is brought to you by our friends at
     Cass County. They use this data to monitor the "bug situation"
     throughout the County, including as an input for scheduling
     truck and airplane spraying. We not only have an up to date
     interactive map, but also historic data. Ben will be at the
     hackathon to answer questions.

   * Great Rides Bike Share. This data set is an anonymized set
     of all Great Rides trips over the past year -- about 95000!
     I've copied the files into this local repo for safe keeping,
     So be sure to go check it out. There's also some information
     that Aaron wrote about the data set, and a few challenge ideas to
     wet your whistle. There's also complete shapefiles for all
     of the bike lanes and shared use lanes in the Shapefiles
     repo. Also, Strava has a bunch of data but I'm not sure how
     accessible it is (they apparently have an API but I haven't
     looked into how easy it is to use). [Check out the heatmap](http://labs.strava.com/heatmap/#14/-96.79053/46.88304/yellow/bike)

   * Downtown Fargo Pedestrian and Traffic Data. So, there's a 
     pedestrian counter on the 100th block of Broadway. There's
     also a traffic counter that keeps track of traffic at
     a few intersections downtown, as well stats on vehicle turning. 
     I hope we can see more data like this in the future! Have some
     fun with it. There are also some links to the ND DOT system,
     which has state wide traffic data (but I could only figure out
     how to download it in CSV format -- no shapefiles yet. I'm only
     one man! You may have better luck)

   * Police Logs. Both [Fargo](http://www.cityoffargo.com/CityInfo/Departments/Police/DispatchLog/FargoPDDispatchLogs.aspx) and 
     [Moorhead](http://rrrdc.com/dispatch-logs/) (and a few other cities
     in the area) publish their police logs online. Now there's
     even a searchable filter! You can go out and find a bunch
     of data that you're interested in (including dates, block-
     level address, and description) for the purpose of finding
     patterns and analysis. If I get the time I'll pull down
     a few subsets that look interesting, and make them available
     in an easy to use format, ideally geocoded as well.

   * [Mat Bus Mobile](http://matbusmobile.com/portal/fr2/index.jsf). This one is more of an API, and less of an
     actual data set. Behind the scenes on Mat Bus Mobile's new site
     is a slick JSON API. You can use it to get information on 
     where buses were last seen. Combined with the transit route
     shape files, and you may have the recipe for some interesting
     project ideas. You may want to get friendly with Chrome's
     developer tools to see how it works. 

   * Traffic Cam Images. This one is a bit experimental, but maybe it'll
     be useful. These images were pulled from the local traffic cam. 
     Maybe you could use some machine vision to find traffic patterns?

   * Crop Output. These were pulled directly from George Mason University,
     who have this huge database of crop data, county by county. I just
     pulled a bunch of aggregate data for Cass County by year, but you
     could totally run your own reports and generate specific data if
     this interests you. There's a serious amount of data there. There
     is also this other huge amount of data from the USDA if interested.
     [Link here](http://www.ers.usda.gov/data-products/agricultural-productivity-in-the-us.aspx)

   * [City of Fargo Building Permits](http://data.cityoffargo.com/files/buildingpermits.csv). An oldie but a goodie. 
     These are kept relatively up to date, and combined with some of the
     other GIS shapefiles, may prove useful.

   * [US Distribution of Production of Oil and Gas Wells](https://catalog.data.gov/dataset/u-s-distribution-and-production-of-oil-and-gas-wells-24b0f). I found this on data.gov and it looked
     interesting. Maybe you'll find some value there. Honestly it's
     pretty huge.


Misc. APIs
----------

   * [Weather Forecast API](https://developer.forecast.io/). Forecast.io is a pretty cool
     *free* resource for historic weather and forecasting.

   * [Censor Demographic API](http://www.broadbandmap.gov/developer/api/demographics-api-by-coordinates). This is a project
     that collects demographic information for the purpose of evaluating who does and
     does not have broadband access. You can get coordinate-level demographic information
     such as income level, ethnicity, and access to broadband.

   * Social Media APIs. Twitter, Instagram, Yelp -- love 'em or hate 'em, all  
     of these services have geo-fence capabilities and location services. Use 
     them to your advantage. Search for keywords, get mashups, correlate events,
     find activity around you, etc.
