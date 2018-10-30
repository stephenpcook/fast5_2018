# fast5_2018

This is an analysis of score data from the 2018 Netball Fast5 World Series in
Melbourne.  The data used has been extracted from official statistics, of which
I make no claim of ownership (sources described below).  The series was played
between Australia, England, New Zealand, Jamaica, South Africa and Malawi on 27
and 28 October 2018.  See
https://en.wikipedia.org/wiki/2018_Fast5_Netball_World_Series/ .

The main file is the jupyter notebook `fast5_melbourne.ipynb`, running python
3, and uses the data analysis toolkit pandas.

# Data sources and description

The tab-separated data in `fast5_melbourne_all.csv` is taken from the team
statistics pages of http://fast5worldseries.com.au/ for example
http://fast5worldseries.com.au/2018-teams/england-2018/#statistics/ .  These
give the zones scored from, and the attempted shots, but do not indicate when a
score was during a power play period, where the points are doubled.  Country
codes have been appended to each row.

Data in `R1_2.csv` has been extracted from the *Score Flow* section of the
match reports at https://mc.championdata.com/fast5worldseries/ , which
indicates when points were scored in power play periods.  These data could be
manually modified to indicate when misses were during power play periods, which
would allow for analysis on power play behaviours (e.g. accuracy and shot
choice during power plays).

# License

Code is released under the MIT license.  Ownership of the data remains with
Champion Data and Fast 5 World Series.

Stephen Cook, 2018.
