---
title: ModelkBricks Motivation
layout: default
permalink: motivation
---

# The need for ModelBricks 

<p> Most computational models in biology are built and intended for “single-use”; the lack of appropriate annotation creates models 
where the assumptions are unknown, and molecules and pathways are not uniquely identified. As shown in figure 1, simply recreating a simulation result from a publication can be daunting; extending and expanding models to new and more complex situations is a Herculean task. As a result, new models are almost always created anew from scratch, repeating literature searches for kinetic parameters, 
initial conditions and modeling specifics.  It is akin to building a brick house starting with a pile of clay. </p>

<center>
  <table border="1px solid black">
    <td> <image src="/images/problems_1loop.gif"/></td> 
   <tr>
    <td align="center"> <strong> Figure 1 </td>
   </tr>
  </table>
</center>


<p> Here we introduce a new concept for building annotated, reusable models, by starting with small well-annotated modules we 
call ModelBricks.  Curated ModelBricks, accessible through an open database, could be used to construct new models that will 
inherit ModelBricks annotations and thus be easier to understand and reuse.  Key features of ModelBricks include (1) reliance 
on a commonly used standard language (SBML), (2) rule-based specification such that species consist of molecules that are uniquely 
identifiable, (3) association with model specific numerical parameters as well as more common annotations,these and other chracteristics are found in Figure 2. The size, shape and color of physical bricks can vary substantively; likewise, to be useful the structure of ModelBricks must be highly flexible – methods to encapsulate mechanisms from single reactions to multiple reactions in a complex process must be able to be contained within a ModelBrick. Ultimately, a modeler would be able to construct large models by using multiple ModelBricks, preserving annotations and provenance of model elements, resulting in a highly annotated model. </p>

<center>
  <table>
    <td> <image src="/images/solution_loop1.gif"/></td> 
   <tr>
    <td align="center"> <strong> Figure 2 </td>
   </tr>
  </table>
</center>

<p> We present the library of ModelBricks to rapidly grow from community contributions. DOI registration can provide persistent 
citable references. This will incentivize model creators to contribute components of their models back as new ModelBricks, 
and users to add back to the library modified or extended ModelBricks. </p> 
