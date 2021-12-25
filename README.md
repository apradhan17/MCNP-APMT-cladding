# MCNP-APMT-cladding
This is a repository for MCNP input files that I used as a grad student while evaluating performance of Kanthal APMT as fuel cladding material. 

For '3% enriched Uranium fuel, 42% enriched uranium fuel, and Neutron energy profile',
All these folders contains MCNP input files that model a 17*17 single Westinghouse assembly.
The assembly uses enriched uranium as fuel and water as moderator. There is an air gap between the fuel and fuel-cladding. There isn't any structure assumed outside the assembly.

For 'Radiation damage'
The calculation for radiation damage is done on a different model than the one used for above three. Californium is used as a strong neutron source.
The neutron emission rate for californium is assumed to be in the order of 1.2E16.
The materials tested are wrapped one after the another and their respective radiation damage is calculated from the flux noted from MCNP output file.
