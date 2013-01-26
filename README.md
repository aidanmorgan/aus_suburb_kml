Description
==============

A repository that contains the boundaries of all Australian suburbs as individual KML files.

Why?
====

For a long time I have looked for a free method of getting the borders of Australian suburbs, but have always been frustrated
 by having to pay for them.

One drunken evening I happened to stumble across the Australian Bureau of Statistic's (ABS) website, which offered the administrative
 boundaries of suburbs as a free to download shapefile. Armed with a copy of global mapper, I managed to export the shapefile to a
 KML file.

 With this KML file, a free copy of the Gazeteer of Australia (from Geosciences Australia), a list of suburbs from Australia Post and some custom java code, I have generated an individual KML
 file for each of the suburbs in Australia that are published by the ABS and Geosciences Australia.
 
 
Getting the Data
================

Gazeteer of Australia: http://www.ga.gov.au/meta/ANZCW0703014255.html

ABS Suburb Boundaries: http://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202011?OpenDocument   (look for "State Suburbs ASGS Non ABS Structures Ed 2011 Digital Boundaries in ESRI Shapefile Format ")

Help/Changes
============

This data comes from the ABS, and I do not take any responsibility for any inaccuracies, use at your own risk.

The "Unknown" directory contains suburbs that cannot be automatically determined because the suburb name does not exist according to the Gazetteer or Australia Post suburb reference files. If you know where one of them should go, please feel free to put it into the right subdirectory and send me a pull request (please try to keep to the naming convention followed).
