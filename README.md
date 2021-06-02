# Battery-System-Design-Framework
A Battery System Design Framework which designs the most effective battery system for a certain use-case. This framework aims to design and compare viable battery pack configurations (cell models, electronic configurations), in order to determine the best pack for an inputted use-case.

The current implementation takes a power profile (positive values indicate battery discharge) and iterates through energy capacity and minimum voltage redundance factors to determine the most cost efficient battery, which can deliver the required power over an inputted service life.

More details on how the framework has been designed and implemented can be found in the thesis attached: "Battery System Design Framework: applied to the investigation of virtual synchronous inertia provision"

Several csv files (attached) are required for the operation of this Framework:
- Required power timeseries csv (giving time vs power dispatch)
- BatPaC: https://www.anl.gov/partnerships/batpac-battery-manufacturing-cost-estimation, access must be given by Argone National Laboratories
- Cell Database
