# PSRC-SoundCast to Fast-Trips Demand Data Converter
This project converts disaggregate SoundCast Activity-Based Travel Model demand to [Fast-Trips](https://github.com/MetropolitanTransportationCommission/fast-trips) input demand, using output from [PSRC Daysim Model] (https://github.com/psrc/daysim-old). 

# Full Documents
[Dyno-Demand technical memo](https://github.com/osplanning-data-standards/dyno-demand)

The demand data is reformatted to the Dyno-Demand format to be able to be read by Fast-Trips. 
The Dyno-demand format has one mandatory file (trip_list.txt) and two optional files [ household.txt and person.txt ].

# Related Projects
This is based on a script originally written by Lisa Zorn and Alireza Khani in 2012. 

# Getting started

`Convert_demand.py`

Reads:     `daysim_outputs_2010.h5` (PSRC Daysim trip file in HDF5 format)  
Writes:    Input demand to [Fast-Trips](https://github.com/MetropolitanTransportationCommission/fast-trips) in [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) format:  
 - [`household.txt`](https://github.com/osplanning-data-standards/dyno-demand/blob/master/files/household.md)
 - [`person.txt`](https://github.com/osplanning-data-standards/dyno-demand/blob/master/files/person.md)
 - [`trip_list.txt`](https://github.com/osplanning-data-standards/dyno-demand/blob/master/files/trip_list.md) 

# Running 
The outcome saved at [Soundcast_fasttrips_demand_version0.1.zip](https://app.box.com/files/0/f/6528666953/1/f_53135430525)

# Credits
This is based on a script originally written by [Lisa Zorn](https://github.com/lmz) and [Alireza Khani](https://github.com/akhani) in 2012:
`Q:\Model Development\FastTrips\Demand.CHAMP\ft_CHAMPdemandGenerator.py`
This task also referred to the parallel project [SF-CHAMP to Fast-Trips Demand Data Converter](https://github.com/sfcta/fast-trips_demand_converter) completed by [Bhargava Sana](https://github.com/bhargavasana) 
