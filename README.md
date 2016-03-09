# fast-trips_demand_converter
This scripts converts disaggregate SoundCast Activity-Based Travel Model demand, output from Daysim model, to Fast-Trips input demand. 
The demand data is reformatted to the Dyno-Demand format to be able to be read by Fast-Trips. 
The Dyno-demand format has one mandatory file (trip_list.txt) and two optional files [ household.txt and person.txt ].
Dyno-Demand technical memo: https://github.com/osplanning-data-standards/dyno-demand 
