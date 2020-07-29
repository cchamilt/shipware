# Shipware
A simple script to process orders on [Tindie](https://tindie.com) through [Shippo](https://goshippo.com) to create shipping labels.  
It is very US centric, but could be made more international.  

Uses yaml files to map carrier rate parcels and product information for customs and shipping  

## Requirements
Python 3.6+ and the requirements.txt  

## Optional
postal.parser with some extra configuration  

## TODO
* Finish glabels testing
* Mass conversions - kg,g,oz,lbs
* Sales tax check/calculation
* Cheapest rate option
* Submit tracking info to Tindie somehow
* Automatically email or print packing list, baggy labels, and shipping labels when processed
* Address cleansing with postal.parser and geotagging for certain countries
* Accounting csv output