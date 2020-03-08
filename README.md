### Transshipment Problem
# Minimize Transportation Costs
<br>
Ryan is an electronics company with production facilities in Denver and Atlanta. Components produced
at either facility may be shipped to either of the firm’s regional warehouses, which
are located in Kansas City and Louisville. From the regional warehouses, the firm supplies
retail outlets in Detroit, Miami, Dallas, and New Orleans. The key features of the
problem are shown in the network model depicted.
<br><br>
<img src="https://raw.githubusercontent.com/juanduranc/imgs/master/transshipment2.JPG" />
<br>

Networ Model Descripton
-------------
  - Denver and Atlanta are the facilities labeled as nodes 1 and 2. <br>Their unit supplies are 600 and 400 respectively.
  - Every arrow in the chart has a number designated. These are the costos of transportation.
  - Kansas City and Louisville are the distribution centers.
  - The nodes on the right are the retail outlets. Each one with its respective demand.

Problem Statement
-------------
Optimize the transportation of units to minimize transportation costs.
<br>

Unit cost of each route
-------------
The following image displays the cost of each unit transported.

<img src="https://raw.githubusercontent.com/juanduranc/imgs/master/transhipment Costs.JPG" />
<br>

Constraints
-------------
  1) Kansas City supply should be less than or equal to 600.
  2) Atlanta supply should be less than or equal to 400.
  3) Kansas City is used as an intermediate warehouse. input = output
  4) Louisville is used as an intermediate warehouse. input = output
  5) Detroit should recieve 200 units.
  6) Miami required 150 units.
  7) Dallas requires 350 units.
  8) New Orleans requires 300 units.
<br>
Total constraints = 8
<img src="https://raw.githubusercontent.com/juanduranc/imgs/master/transhipment Constraints.JPG" />
<br>

Implementing Solver
-------------
<img src="https://raw.githubusercontent.com/juanduranc/imgs/master/transshipment Solver.JPG" />
