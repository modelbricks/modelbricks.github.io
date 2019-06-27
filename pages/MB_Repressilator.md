---
layout: default
title: Repressilator
permalink: /MB_Repressilator/
---
## Repressilator: A Synthetic Oscillatory Network

### Publication 
Elowitz, M. and Leibler, S. (2000). A synthetic oscillatory network of transcriptional regulators. Nature, 403(6767), pp.335-338.
 PMID:<a href="https://www.ncbi.nlm.nih.gov/pubmed/?term=10659856">10659856</a>&ensp; 
 DOI: <a href="https://doi.org/10.1038/35002125"> 10.1038/35002125</a><br />

### Description
This ModelBrick describes the oscillatory response of tree repressor proteins in a Network. 
LacI is a repressor protein that will inhibit the transcription of tetR, tetR protein in turn represses the transcription of cI,
and finally cI inhibits the transcription of LacI. Closing the cycle. This mechanism creates oscilation in the protein Concentration of the tree proteins as seen in the simulation.

### Images
<center>
 <table> 
 <tr>
  <td align="center" width="280"><a href="https://modelbricks.github.io/images/Vcellimages/repressilator_Vcell_diagram.PNG"><img align="center" src="/images/Vcellimages/repressilator_Vcell_diagram.PNG"/></a></td>
    <td align="center" width="280"><a href="https://modelbricks.github.io/images/SBGNfiles/repressilator_Vcell_sim1.PNG"><img align="center" src="/images/SBGNfiles/repressilator_Vcell_sim1.PNG" height="230"/></a></td>
 </tr>
 <tr>
  <td align="center"> Vcell: reaction diagram </td>
   <td align="center"> Vcell: Stochastic Simulation </td>
   </tr>
 </table>
</center>
### Downloads 

In this section you can find the executable counterpart for the ModelBrick in the description as well as the visualizations files
<center>
<table> 
 <td align="center"><a href="/modelbricks/VCML_SBMLfiles/Elowitz2000_Repressilator_curated.vcml">VCML</a> designed with <a href="http://vcell.org"> VCell</a>  </td> 
 <td align="center"><a href="/modelbricks/VCML_SBMLfiles/Elowitz2000_Repressilator_curated.xml">SBML</a> exported from <a href="http://vcell.org"> VCell</a>  </td>
 <tr>
    <td align="center" width="33%"><a href="/modelbricks/SBGNexecutablefiles/">GraphML</a> designed with <a href="https://immersive-analytics.infotech.monash.edu/vanted/addons/sbgn-ed/">VANTED (SBGN-ED)</a></td>
    <td align="center" width="33%"><a href="/modelbricks/SBGNexecutablefiles/">SBGN-ML</a> exported from <a href="https://immersive-analytics.infotech.monash.edu/vanted/addons/sbgn-ed/">VANTED (SBGN-ED)</a></td>
 </tr>
 </table>
 </center>
 


### Contributors
Maria Heredia, Michael Blinov
 
