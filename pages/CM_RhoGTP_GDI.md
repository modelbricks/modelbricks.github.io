---
layout: default
title: Curated Model by Ota et al., 2015
permalink: /CM_RhoGTP_GDI/
---
## Curated Model: RhoGTPase regulation by RhoGDI interaction with GAPs

### Publication 

Ota, T., Maeda, M., Okamoto, M., & Tatsuka, M. (2015). <br />
Positive regulation of Rho GTPase activity by RhoGDIs as a result of their direct interaction with GAPs. <br />
<i> BMC systems biology, 9 </i> (1), 3.

 PMID: <a href="https://www.ncbi.nlm.nih.gov/pubmed/?term=25628036">25628036</a>&ensp; 
 DOI: <a href="https://doi.org/10.1186/s12918-015-0143-5">10.1186/s12918-015-0143-5</a><br />

### Description
This model describes how GEFs and GAPs interact with GDIs in Rho GTPase signaling. GDIs have a negative role in Rho GTPase signaling, as they inhibit GEFs, thereby suppressing overall Rho activity. GDIs also have a positive role, in which they inhibit GAPS under specific conditions, allowing sustained Rho activation.

### The curated model

#### VCell reaction diagram

<center><a href="https://modelbricks.github.io/images/Vcellimages/CM_RhoGTP_VCellDiagram.PNG"><img width="500" src="/images/Vcellimages/CM_RhoGTP_VCellDiagram.PNG"/></a></center>

#### The model with varying GDI activity

<center>
 <table style="border-collapse:separate; border-spacing:0 30px; margin-top:-15px;"> 
 <tr class="spaceUnder">
  <td align="center" width="300"><a href="https://modelbricks.github.io/images/SBGNfiles/RhoGTP_Fig1a_SBGN.PNG"><img width="250" style="vertical-align:middle" src="/images/SBGNfiles/RhoGTP_Fig1a_SBGN.PNG"/></a></td>
  <td align="center" width="300"><a href="https://modelbricks.github.io/images/publications/RhoGTP_Fig1a_sim.PNG"><img width="250" style="vertical-align:middle" src="/images/publications/RhoGTP_Fig1a_sim.PNG"/></a></td>
  <td align="center" style="vertical-align:middle"> In this canonical application, GDIs inhibit GEF and GAP activities by sequestering GTPase. Kinetic law was adjusted to eliminate effect of GDI on both GEF and GAP. <br /><br /> Figure 1A </td>
 </tr>
 <tr class="spaceUnder">
  <td align="center" width="300"><a href="https://modelbricks.github.io/images/SBGNfiles/RhoGTP_Fig1b_SBGN.PNG"><img width="250" style="vertical-align:middle" src="/images/SBGNfiles/RhoGTP_Fig1b_SBGN.PNG"/></a></td>
  <td align="center" width="300"><a href="https://modelbricks.github.ioimages/publications/RhoGTP_Fig1b_sim.PNG"><img width="250" style="vertical-align:middle" src="/images/publications/RhoGTP_Fig1b_sim.PNG" height="230"/></a></td>
  <td align="center" style="vertical-align:middle"> In this GDI-integrated application, GDIs inhibit GEF and GAP activities by sequestering GTPase and by interacting with GEFs and GAPs. <br /><br /> Figure 1B</td>
  </tr>
 <tr class="spaceUnder">
  <td align="center" width="300"><a href="https://modelbricks.github.io/images/SBGNfiles/RhoGTP_Fig1c_SBGN.PNG"><img width="250" style="vertical-align:middle" src="/images/SBGNfiles/RhoGTP_Fig1c_SBGN.PNG"/></a></td>
  <td align="center" width="300"><a href="https://modelbricks.github.ioimages/publications/RhoGTP_Fig1c_sim.PNG"><img width="250" style="vertical-align:middle" src="/images/publications/RhoGTP_Fig1c_sim.PNG" height="230"/></a></td>
  <td align="center" style="vertical-align:middle"> In this GDI-integrated application, GDI/GEF interaction was removed. Kinetic law was adjusted to eliminate effect of GDI on GEF. <br /><br /> Figure 1C</td>
 </tr>
 <tr>
  <td align="center" width="300"><a href="https://modelbricks.github.io/images/SBGNfiles/RhoGTP_Fig1d_SBGN.PNG"><img width="250" style="vertical-align:middle" src="/images/SBGNfiles/RhoGTP_Fig1d_SBGN.PNG"/></a></td>
  <td align="center" width="300"><a href="https://modelbricks.github.ioimages/publications/RhoGTP_Fig1d_sim.PNG"><img width="250" style="vertical-align:middle" src="/images/publications/RhoGTP_Fig1d_sim.PNG" height="230"/></a></td>
   <td align="center" style="vertical-align:middle"> In this GDI-integrated application, GDI/GAP interaction was removed. Kinetic law was adjusted to eliminate effect of GDI on GAP. <br /><br /> Figure 1D</td>
 </tr>
 </table>
</center>

### Downloads
<center> 
 <table style="border-collapse:separate; border-spacing:0 5px;"> 
 <td align="center" width="33%"><a href="/modelbricks/VCML_SBMLfiles/RhoGTP_ModelBrick_New.vcml">VCML</a> designed with <a href="http://vcell.org"> VCell</a> </td> 
 <td align="center" width="33%"><a href=".xml">SBML</a> exported from <a href="http://vcell.org">VCell</a> </td>
 <tr>
      <td align="center" width="33%"><a href="/modelbricks/SBGNexecutablefiles/CM_RhoGTP_SBGN.xml">XML</a> designed with <a href="http://www.celldesigner.org/">CellDesigner</a></td>
    <td align="center" width="33%"><a href="/modelbricks/SBGNexecutablefiles/CM_RhoGTP_SBGN.graphml">GraphML</a> exported from <a href="https://immersive-analytics.infotech.monash.edu/vanted/addons/sbgn-ed/">VANTED (SBGN-ED)</a></td>
 </tr>
 <tr>
 <td colspan="2" align="center" width="33%"><a href="/modelbricks/SBGNexecutablefiles/CM_RhoGTP_SBGN.sbgn">SBGN-ML</a> exported from <a href="http://www.celldesigner.org/">CellDesigner</a></td>
 </tr>
 </table>
</center>
 
### ModelBricks

<ol>
 <li> <a href="/MB_RhoGTP_GEF_act/">GEF activation</a>
 </li>
 <li> <a href="/MB_RhoGTP_GDI_activity/">GDI effects on RhoGTPase cycle</a>
 </li> 
</ol>  
  
  
### Contributors
John Albanese, Michael Blinov
 

