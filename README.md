# CP2030-Power-Flow-Modelling
Modelling the additional infrastructure required for CP2030

There are six Jupyter Notebooks in this reposotory:

FLOPS_and_Demand_2025
-
- This splits GB into 18 different regions and aggregates demand from all the GSPs based off NESO's FES for 2025

Power_Flow_2025
-
- This runs a power flow using pandapower to see where the network is stressed at max. demand and max. renewable gen in 2025

FLOPS_and_Demand_2030
- 
- This splits GB into 18 different regions and aggregates demand from all the GSPs based off NESO's FES for 2030

Power_Flow_2030
- 
-  This runs a power flow using pandapower to see where the network is stressed at max. demand and max. renewable gen using 2030 predictions

Power_Flow_Sol_1
- 
- The network is incredibly overloaded, and so this solution models adding OHLs throughout the country

Power_Flow_Sol_2
- 
- This solution adds two HVDC cables (subsea) from Scotland to demand centres in England and Wales.
