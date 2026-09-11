My thesis proposes the implementation of "Database-driven Event Logs for Process Mining", which include information of database interactions that occur during a process execution.

In order to prove this concept there were  2 Event Log Generators created to produce event logs according to this new proposed standart. 

Generator A is based on Petri Nets, requires a PNML file to run and produces a Xes file withe the results of the simulation.
Generator B is baed in BPMN to run, and produces a XES and a CSV file with the simulation results.

Both of them were connected to the same Postgres database during simulation.
