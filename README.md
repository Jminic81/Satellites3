## **The Danger of Space Junk:  Analysis of dataset Active Satellites in Orbit around Earth** 

### Introduction

Junk!  It’s a by-product of progress.  We build, consume, throw away.  Decay is visible every day in the form of personal trash, and 
on a larger scale in abandoned buildings, junkyards, and landfills.  But what about what is not seen every day but is there in the 
skies, in the form of “space junk” and where did it come from?  Satellites!  

### Dataset Origin and Significance

The dataset Active Satellites in Orbit around Earth (*Ref 1*) hails from the Satellite Database, produced by Teri Grimwood.  The Satellite Database is updated quarterly, free and publically accessible.  The data are collected from corporate, scientific, government, military, non-governmental, and academic websites available to the public.  It was last updated in July 2016 and contains 26 Columns and 1420 Rows.

In 1976, a United Nations protocal was established to register all objects launched into space.  With the evolution of international space law, space object registration was needed to identify which countries/entities were responsible/liable for issues related to space objects.

### Dataset Overview

Missing data is summarized in the Jupyter Notebook and was not treated. Column 2 “Country/Organization of UN Registry” contains "NR" 
for 28% of the entries.  A firm explanation for "NR" was not found; however, it is suspected it means “Not Registered” as 8% of all satellites launched since 1957 (Total = 7136) have not been registered with the United Nations.  The reason for lack of registration is believed to be unintentional transmission/receipt errors (*Ref 2*).

The first satellite, Sputnik, was launched by Russia in 1957.  That mission proved satellite viability and utility for radio telecommunications.  The number of launches has increased every year and over 50 countries now own or operate satellites.

Figure 1:  

The popularity of cell phones that function by instantly bouncing a signal off a satellite have led to roughly half of all active satellites used for communication.  

Since 1957, there have been 7136 satellite launches.  There are over 1400 active satellites (reference the dataset that is being analyzed) 
that orbit the Earth but over thousands of inactive satellites.  Although satellite dry mass (original mass minus fuel and launch vehicle) 
can range from 10 kgs to 10,000 kgs, the most common is about 500 kgs.  

Satellites are launched into a specific orbit, to avoid collisions with other satellites.  

Table 2:  Types of satellite orbits and height about Earth
LEO (Low earth orbit)                1,200 miles or less above Earth
MEO (medium earth orbit)                    Between 1,200 and 22,000
HEO (Highly elliptical orbit)      22,000 miles above Earth – combine with GEO 
GEO (Geo-stationary earth orbit)       22,000 miles above Earth – combine with HEO 

All satellites have limited life and most simply remain in orbit long after their utility has expired.  Launch vehicles, 
propulsion systems are left behind, accidental or intentional explosions of satellites or collisions with other satellites generate debris 
and compound the number of items.  A tiny chip of metal or a fleck of paint might seem innocuous but traveling at four miles per second 
in LEO causes great damage when impacting a space vehicle.  

Table 1:  Estimated quantity and size of space junk pieces and particles
Quantity   Size
21,000	     > 10 cm
500,000     1-10 cm
Millions      > 1cm

It can be argued that space is vast but more than half of all satellites and a large percentage of space junk is found in 
LEO (Low Earth Orbit) which is 1,200 miles or less above the Earth.  And satellites in LEO typically have relatively short life spans:  
five-seven years.  

And yes, debris often falls to earth.  Most matter is incinerated by Earth’s atmosphere but on average once per day something falls 
to Earth.  Most matter ends up in the ocean but there are recorded incidents of people being impacted.   More the danger is to space 
missions and new satellite launches.

Satellites have been launched to track space junk.  An international task force is evaluating clean-up methods. Unsanctioned proposals 
include giant nets, laser cannons, and magnets. 

### References:

1.	https://www.kaggle.com/jonathanbouchet/activity-of-satellites/data  Dataset and kernel by Jonathan Bouchet.
2.  http://planet4589.org/space/un/stat.txt
3.	http://www.explainthatstuff.com/satellites.html
4.	http://www.swiftutors.com/types-of-satellite-orbits.html
5.	https://www.space.com/16518-space-junk.html
