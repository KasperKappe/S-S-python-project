# S-S-python-project
Kasper Kappe 5349214

I have two proposals:

1: For work i did in the past, i created a script capable of reading a Mineral collection database file, interpreting the location of each sample with the use of Google Maps 
and MinDat APIs, and plotting each sample on an interactive map using Folium. However, this script is written in jupyter notebooks and is diffficult to use. I would like to 
make a GUI for this script to make it easier to understand, use, and more versitile. This GUI would include the ability to open the read and write files with file explorer, 
the ability to set the settings and parameters in an organised manner, keep track of progress and report errors, and maybe more.

2: Design a program that can read, process, plot, export to excel raw data files from the HotDisk.
The HotDisk is a laboratory machine i use for my work at the university laboratory, and it can be used to determine the thermal properties of materials.
I think the machine works as follows: The machine has a plastic flap with a heater and temperature sensors in it. The temperatrue sensors are temperature dependent resistor 
wires. The machine records the voltage over these wires as a function of time, as well as the imput energy.
To use this data i would need to program a script that: can read the raw data file (i think it is in Javascript), that recreates the 
physics model that converts the raw voltage and energy data to thermal material properties, and that then exports these results to an excel file.
The first of these steps might already be quite difficult since the data file is in Javascript, and the second step will be very difficult since all the inner workings of the
machine are unknown. I might be able to make a model that can conceptually replicate the process but it will not be useful in real life. So in retrospect, this idea might be
too difficult. Maybe i can do only (part of) one of the three steps instead.
