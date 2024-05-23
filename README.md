# NTUA_Computer_System_Performance
NTUA ECE CSPERF 2023
## Network Simulation with Task Clustering
This Python script simulates a network environment with task clustering. It categorizes incoming tasks into three clusters using a clustering algorithm and simulates their processing through various network resources.

### Description
The simulation includes the following components:

CPU: Tasks are processed using Processor Sharing.
Disk: Tasks requiring disk access are queued and processed in a first-in, first-out (FIFO) manner.
Outgoing Link: Once processed, tasks are sent out through the outgoing link.
The simulation tracks the response times and throughput of tasks, as well as resource utilization and the percentage of tasks that need to backtrack due to resource limitations.
