### **The Danger of Space Junk:  Analysis of Dataset "Active Satellites in Orbit around Earth"** 

#### Introduction

Junk!  It’s a by-product of progress.  We build, consume, throw away.  Decay is visible every day in the form of personal trash, and 
on a larger scale in abandoned buildings, junkyards, and landfills.  But what about what is not seen every day but is there in the 
skies, in the form of “space junk” (*Ref 1*) and where did it come from?  Satellites!  

#### Dataset Origin

The dataset "Active Satellites in Orbit around Earth" (*Ref 2*) is from the Satellite Database, produced by Teri Grimwood.  The Satellite Database is updated quarterly, free and publically accessible.  The data are collected from corporate, scientific, government, military, non-governmental, and academic websites available to the public.  It was last updated in July 2016.  

#### Dataset Significance and Overview

The first satellite, Sputnik, was launched by Russia in 1957(*Ref 3*).  That mission proved satellite viability and utility for radio telecommunications.  The number of launches has increased every year and over 50 countries now own or operate satellites.

__Figure 1:  

![alt text](https://github.com/Jminic81/Satellites3/blob/master/Country.png)

In 1976, a United Nations protocal was established to register all objects launched into space.  With the evolution of international space law, registration was needed to identify which countries/entities were responsible/liable for issues related to space objects.  The dataset contains a column summarizing UN Registry; however, "NR" appears in 28% of the entries.  A firm explanation for "NR" was not found; however, it is strongly suspected it means “Not Registered” as 8% of all satellites launched since 1957 (Total = 7136) have not been registered with the United Nations.  The reason for lack of registration is believed to be unintentional transmission/receipt errors (*Ref 4*).

The popularity of cell phones that function by instantly bouncing a signal off a satellite have led to roughly half of all active satellites used for communication but a large number are used to observe Earth (for example, weather).  

__Figure 2:  

![altext](https://github.com/Jminic81/Satellites3/blob/master/pie1.png)


Since 1957, there have been 7136 satellite launches.  Per the dataset, there are over 1400 active satellites that orbit the Earth but over thousands of inactive satellites.  Although satellite dry mass (original mass minus fuel and launch vehicle) can range from 10 kgs to 10,000 kgs, the most common is about 500 kgs.  

Satellites are launched into a specific orbit, to avoid collisions with other satellites.  Most are in Low Earth Orbit (LEO). 

__Table 1:  Classes of satellite orbits and height above Earth(*Ref 5*)__

|__Abbreviation__  |__Meaning__                  |__Miles above the Earth__    | 
|:-----------------|----------------------------:|:----------------------------|
| LEO              | Low Earth Orbit             |  1,200 or less              |
| MEO              | Medium Earth Orbit          |  Between 1,200 and 22,000   |
| GEO              | Geo-Stationary Earth Orbit  |  22,000                     |
| HEO, Elliptical  | High/Elliptical Earth Orbit |  22,000                     |

__Figure 3:  

![altext](https://github.com/Jminic81/Satellites3/blob/master/Orbit.png)

#### Propogation and Danger of Space Junk

All satellites have limited life and most simply remain in orbit long after their utility has expired.  Launch vehicles and propulsion systems are left behind, accidental or intentional explosions of satellites occur, and collisions with other satellites generate debris and compound the amount of space junk.  A tiny chip of metal or a fleck of paint might seem innocuous but traveling at four miles per second in LEO causes great damage when impacting a space vehicle.  

__Table 2:  Estimated quantity and size of space junk pieces and particles (*Ref 1*)__

|__Quantity__  |__Size__   | 
|:-------------|-----------|
| 21,000       | > 10 cm   |
| 500,000      | 1-10 cm   |
| Millions     | <  1 cm   |

It can be argued that space is vast but more than half of all satellites and a large percentage of space junk is found in 
LEO which is 1,200 miles or less above the Earth.  And satellites in LEO typically have relatively short life spans:  
five-seven years.  

And yes, debris often falls to earth.  Most matter is incinerated by Earth’s atmosphere but on average once per day something falls 
to Earth.  Most matter ends up in the ocean but there are recorded incidents of people being impacted.   More the danger is to space 
missions and new satellite launches.

Ironically enough, satellites have been launched to track space junk.  An international task force is evaluating clean-up methods. Unsanctioned proposals include giant nets, laser cannons, and magnets. 

### Analysis

The Jupyter notebook "Satellites" in ths repository contains the raw data analysis and visualizations *(Ref. 6)*

#### References:

1.	https://www.space.com/16518-space-junk.html
2.  https://www.kaggle.com/jonathanbouchet/activity-of-satellites/data  Dataset and kernel by Jonathan Bouchet.
3.  http://www.explainthatstuff.com/satellites.html
4.  http://planet4589.org/space/un/stat.txt
5.  http://www.swiftutors.com/types-of-satellite-orbit
6.  https://www.kaggle.com/jminic81/data-analysis-and-visualization/editnb
