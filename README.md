# fast-trips_demand_converter
This scripts converts disaggregate SoundCast Activity-Based Travel Model demand, output from PSRC Daysim model, to Fast-Trips input demand. 
The demand data is reformatted to the Dyno-Demand format to be able to be read by Fast-Trips. 
The Dyno-demand format has one mandatory file (trip_list.txt) and two optional files [ household.txt and person.txt ].
Dyno-Demand technical memo: https://github.com/osplanning-data-standards/dyno-demand 

This is based on a script originally written by Lisa Zorn and Alireza Khani in 2012: Q:\Model Development\FastTrips\Demand.CHAMP\ft_CHAMPdemandGenerator.py
