# Shipware
A simple script to process orders on [Tindie](https://tindie.com) through [Shippo](https://goshippo.com) to create shipping labels.  
It is very US centric, but could be made more international.  

Uses yaml files to map carrier rate parcels and product information for customs and shipping  
Based on https://github.com/NuclearManD/TindieAPI Tindie API classes  

## Requirements
Python 3.6+ and the requirements.txt  

## TODO
* Finish glabels testing
* Mass conversions - kg,g,oz,lbs
* Sales tax check/calculation
* Cheapest rate option
* Submit tracking info to Tindie somehow
* Automation for emailing or printing packing list, baggy labels, and shipping labels when processed
* Address cleansing with https://github.com/openvenues/pypostal and geotagging for certain countries
* Accounting csv output