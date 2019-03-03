# WoltApp
The code for the woltapp 2019


Your task is to help one of our courier operation managers to analyze pickup times. The courier operation manager has sent you a following message:

I would like understand what is the median pickup time for each restaurant between certain hours (e.g. 15-16). The data set of pickup times has been collected from Helsinki between 7.1. - 13.1.2019.

locations.csv
pickup_times.csv
The first file contains all pickup locations (restaurants) in Helsinki and the second one all pickup times from that week.

I would like to have either an command line application or some kind of graphical user interface. Whichever you want to create. I need to be able to select the day and start / end hours when using the program.

The command line program could work something like this:

$ median_times Helsinki 07-01-19 19-20 mediantimes.csv

This command would calculate medians of pickup times for all locations (in Helsinki) between 19-20 on Monday 7.1 and store times to a CSV file (example below).

location_id,median_pickup_time
1,21
2,15
3,6
etc.
