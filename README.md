## Tr-Centrality

A Tr-Centrality is novel centrality introduce in a conference paper <a href="https://ieeexplore.ieee.org/document/9064208">
Most Powerful Node Identification in Complex Network Using a Multiperspective Approach</a> with the aim of identifying social influence in a given complex network. 
Tr-Centrality is the Extension of Gruebler’s Equation which Originally <a href="http://users.encs.concordia.ca/~nrskumar/Index_files/Mech343/Mobility%20and%20Grashof.pdf">Gruebler Equation</a> is used calculate the 
degree of freedom of a planar mechanism, which can be also represented as the power or mobility of a planar mechanism.


Steps:<br>
<li>We introduce a new centrality equation that adopt or extended from Gruebler Equation to identify local strength of node on its neighbors.<br>
<li>Assuming a node one-hop triangular connection signified it local trustworthiness, so we decomposing the network graph into triangular structure
sub-graph for each and every node in the network. node with no triangle connected neighbors becomes irrelevant.<br>
<li>Then we treat those one-hop triangular structural sub-graphs as a planner mechanism, by ignoring the mobility property of a planner mechanism, we can 
apply our improved Gruebler Equation as the qualified ranking of node in a given complex network.<br>
<li>To evaluation the equation we used karate club network and USAir97...<br>
