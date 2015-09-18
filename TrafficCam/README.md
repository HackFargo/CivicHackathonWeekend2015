Traffic Images are located here:
https://drive.google.com/folderview?id=0B-3U-E1nUzSxVUhhZWJrbkhvZ2c&usp=sharing

README file for MhdI94Images.zip data
 
This data was collated off the MN DOT Website here: http://lb.511mn.org/mnlb/cameras/camera.jsf?id=762&view=state over the course of 15 days, starting on September 3rd, 2015.
 
A cron job was run every 5 minutes, to collect the pictures. No duplicate detection or 0-byte file detection was run, leading to some noise in the data. One of the first steps in working with this file would be eliminating duplicates and 0-byte files.
 
For reference, this is the shell script used to download the images:
 
#!/bin/bash
/usr/bin/wget -q -O -  "http://mn.carsprogram.org/mncam/Vid-000330096-00-00.jpg"  >  $(HOME)/MhdTraf/$(date -d "now" '+%Y-%m-%d-T%H-%M')-0.jpg
/usr/bin/wget -q -O -  "http://mn.carsprogram.org/mncam/Vid-000330096-00-01.jpg"  >  $(HOME)/MhdTraf/$(date -d "now" '+%Y-%m-%d-T%H-%M')-1.jpg
/usr/bin/wget -q -O -  "http://mn.carsprogram.org/mncam/Vid-000330096-00-02.jpg"  >  $(HOME)/MhdTraf/$(date -d "now" '+%Y-%m-%d-T%H-%M')-2.jpg
/usr/bin/wget -q -O -  "http://mn.carsprogram.org/mncam/Vid-000330096-00-03.jpg"  >  $(HOME)/MhdTraf/$(date -d "now" '+%Y-%m-%d-T%H-%M')-3.jpg
