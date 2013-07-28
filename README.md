Visualizing OLSRD topography using d3 force-directed graphs.
============================================================

takes a topo dump from olsrd (using textinfo /topo) with little
reformatting (see the sample). And visualizes it.

Do your own
-----------

* Clone the github repo
* Have OLSRD with textinfo running on your network
* change the get-topo.sh file to reflect the IP of your OLSRd textinfo node
* run ./get-topo.sh
* Done!

Dependencies
------------

* Netcat, bash and tail for getting the data.

Legal
-----
Created during the [CONFINE](http://confine-project.eu) EU-FP7 Project.
Using [d3](http://d3js.org) and the [Force-directed graph example](http://bl.ocks.org/mbostock/4062045)
See LICENSE for licensing information
