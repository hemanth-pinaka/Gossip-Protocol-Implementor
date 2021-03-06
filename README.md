{\rtf1\ansi\ansicpg1252\deff0\nouicompat\deflang1033{\fonttbl{\f0\fnil\fcharset0 Calibri;}}
{\*\generator Riched20 10.0.10240}\viewkind4\uc1 
\pard\sa200\sl276\slmult1\f0\fs22\lang9             \par
               \tab\tab       \b DISTRIBUTED OPERATING SYSTEMS                                            \par
\tab\tab\tab\tab\tab PROJECT-2\par
-----------------------------------------------------------------------------------------------------------------------\par
\ul Team Members :\par
NAME\ulnone\tab\tab\tab\tab\tab\tab\ul UFID\par
\ulnone\b0 1. Sai Vishnu Teja Vempali\tab\tab\tab 16141381\par
2. Hemanth Pinaka\tab\tab\tab\tab 18118134\par
\ul\b Gossip Simulator :\par
\ulnone\b0 Implemented Gossip type algorithms for message propagation over large networks. Implemented the gossip and push-sum algorithm and determined the time taken for convergence. \par
\ul Input :\par
\ulnone Gossip : number of nodes topology, algorithm,null\par
Push-Sum :number of nodes, topology, algorithm, avg/sum\par
In the pushsum algorithm we also give an extra input of avg or sum which computes the sum or the average values for aggregate computation. In the case of sum, the initial values of weight are set to 0 and for average they are set to 1. \par
In the case of Gossip we passed a NULL value in this place and this argument is never used.\par
\ul  Output :\par
\ulnone Gossip :  Time taken for convergence\par
Push-Sum :  Time taken for convergence\par
\ul\b Working Parts :\par
\ulnone\b0 We implemented all the mentioned topologies with the given Gossip and Push-Sum algorithms. All the functionalities are working correctly. Use the command below to execute :\par
Run using sbt\par
\b -    run NumberOfNodes topology algorithm avg\par
Example for gossip: run 1000 full gossip null\line Example for gossip: run 1000 full pushsum avg\par
Choice of Inputs  for topology: full , 3d, imperfect3d, line\line Choice of Inputs  for algorithm: pushsum, gossip\line Choice of Inputs  for sum / avg: sum, avg\b0\par
\ul\b Largest Network :\par
\ulnone\b0 The largest network that we were able to run was 15625 nodes for the full topology and the convergence ratio was 7811.499. The time taken was 1329s. The maximum number of nodes we tried for 3D and Imperfect 3D were 10000 but for convenience sake we didn't include them in the graph in Report.pdf file. For line topology, we were able to deal with a maximum of 216 nodes.\par
We also included the build.sbt and plugins.sbt files along with the project2.scala file in the compressed zip folder. Please run using sbt. The folder also has a README file, a Report.pdf file and excel files for the gossip, Pushsum convergence values and Sum convergence values as well.\par
The graphs are included in Report.pdf\b\par
}
 