---
title: Construction of a ModelBrick
layout: default
permalink: construction
---

# Construction of ModelBricks

## Obtaining the model 

The creation of ModelBricks begins with a full model. As an example, we can take a model of a Rho GTPase cycle which was created by Ota et al. in 2015 (PMID: <a href="https://www.ncbi.nlm.nih.gov/pubmed/?term=25628036">25628036</a>). 

<center>
  <table>
    <td align="center" width="500">
      <a href="https://modelbricks.github.io/images/publications/CM_PM25628036_SBGN.PNG">
        <img width="450" style="vertical-align:middle" src="/images/publications/CM_PM25628036_SBGN.PNG"/>
      </a>
    </td>
    <tr>
      <td align="center"> 
        SBGN visualization
        <br />
        Figure 1B from publication
      </td>
    </tr>
  </table>
</center>

In this publication, the authors are investigating possible positive regulation of Rho GTPase activity by RhoGDIs. Rho family GTPases act as molecular switches, controlling processes including actin cytoskeletal organization, microtubule dynamics, and vesicle trafficking. Guanine nucleotide exchange factors (GEFs) activate small G proteins by promoting the exchange of GDP for GTP. GTPase activating proteins (GAPs) inactivate small G proteins by promoting GTP hydrolysis. GDP-dissociation inhibitors (GDIs) have both a negative and a positive role in the Rho GTPase cycle. The negative role is to suppress overall Rho activity by inhibiting GEFs, while the positive role is to sustain Rho activation by inhibiting GAPs.

## Annotating the model

<center>
  <table>
    <td align="center" width="500">
      <a href="https://modelbricks.github.io/images/Vcellimages/CM_RhoGTP_VCellDiagram.PNG">
        <img width="450" style="vertical-align:middle" src="/images/Vcellimages/CM_RhoGTP_VCellDiagram.PNG"/>
      </a>
    </td>
    <tr>
      <td align="center"> 
        VCell reaction diagram
      </td>
    </tr>
  </table>
</center>

The SBML file provided in the publication was first imported into VCell. The model was then fully annotated to yield a more thorough understanding of the model for the viewer. Both textual and database annotations were added. 

<center>
  <table>
    <td align="center" width="600">
      <a href="https://modelbricks.github.io/images/Vcellimages/CM_PM25628036_annotation.PNG">
        <img width="550" style="vertical-align:middle" src="/images/Vcellimages/CM_PM25628036_annotation.PNG"/>
      </a>
    </td>
    <tr>
      <td align="center"> 
        Annotation of original model in VCell
      </td>
    </tr>
  </table>
</center>

Species were modified so that they were constructed of individual molecules. By completing this step, each species became much more comprehensive and the constituent parts are clearly shown. 

<center>
  <table>
    <td align="center" width="600">
      <a href="https://modelbricks.github.io/images/Vcellimages/CM_PM25628036_molecularization.PNG">
        <img width="550" style="vertical-align:middle" src="/images/Vcellimages/CM_PM25628036_molecularization.PNG"/>
      </a>
    </td>
    <tr>
      <td align="center"> 
        Species composed of individual molecules
      </td>
    </tr>
  </table>
</center>

Once the model was fully annotated, simulations were run in VCell and confirmed to replicate those from the publication.

diagram of matching simulations HERE

## ModelBrick creation

daigram of first two modelbricks splitting HERE

The first ModelBrick derived from the full model describes the activation of GEF and the degradation of the activator. The remaining large and complex ModelBrick can be further broken down into additional ModelBricks.

diagram of further breakdown HERE

Two additional ModelBricks were then created. One of these ModelBricks describes a much simpler Rho GTPase cycle, while the other ModelBrick describes GDI and G protein complex formation.

All of these ModelBricks can have simulations completed in VCell on their own. Therefore, they are independent entities that can be combined to construct full models that are fully annotated and computable. 
