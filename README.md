### SUBDOCK

Documentation: https://wiki.docking.org/index.php?title=SUBDOCK_DOCK3.8

currently supports 3 job schedulers- SGE, SLURM, and GNU Parallel

If you would like to add support for the queueing system you use to SUBDOCK, ctrl-F "QUEUE TEMPLATE" in subdock/rundock for guidelines and help on which areas of code need to be edited.

Support for Singularity Engine is deprecated until DOCK3R is incorporated with it.

Henceforth, you need to provide a DOCK3R image instead of a DOCK executable.  
