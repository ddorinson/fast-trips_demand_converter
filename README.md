# fast-trips_demand_converter
Converts disaggregate SF-CHAMP Activity-Based Travel Model demand to Fast-Trips input demand using time of day distributions from observed transit boardings and alightings.

Fast-Trips_Transit_Travel_Demand.py

Reads: daysim_outputs_2010.h5 (Soundcast trip file in HDF5 format)
Writes: Input demand to Fast-Trips in Dyno-Demand format:

household.txt
person.txt
trip_list.txt

This is based on a script originally written by Lisa Zorn and Alireza Khani in 2012: Q:\Model Development\FastTrips\Demand.CHAMP\ft_CHAMPdemandGenerator.py
