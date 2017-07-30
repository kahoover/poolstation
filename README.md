# poolstation

## description
Code to run a small floating buoy that checks the pool temperature and sends it to a website using RESTful statements.

## segments
- _Pool Segment_ is a set of joined PVC pieces into the form of a "U". The PVC contains a Adafruit Feather M0, two 6V 6W solar panels, a 1-wire temperature probe, 9DOF platform, a 2700 mAh 3.7V LiPO battery, and a charge controller. There is also a vertical boom that contains a 2.4 GHz antenna
- _Ground Segment_ is a pair of python programs. One takes REST requests from the Pool Segment and writes them to a database. The second creates a page representing the data when called.

## Disclaimer
Yes, this is a terrible way to run a railroad. I just wanted to play with a few concepts.