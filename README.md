# Coupling grids with different geometries and scales: an example from fluvial geomorphology
A landlab experiment linking upland precipitation runoff and sediment tranport to lowland overbank flooding and infiltration. We provide an educational notebook, `'CoupledGridsEKT.ipynb'` addressing the fluvial geomorhpology and software engineering learning objectives - the main result from the fluvial group in ESPIn 2020.

|Contributors|At|
|:--|:--|
|Shelby Ahrendt|University of Washington| 
|Josie Arcuri|Indiana University| 
|Eric Barefoot|Rice University| 
|Rachel Bosch|University of Cincinnati| 
|François Clapuyt|Université Catholique de Louvain| 
|Hima Hassenruck-Gudapati| University of Texas at Austin| 
|Vinicius Perin|North Carolina State University| 
|Edwin Saavedra C.| Northwestern University | 
|Mohit Tunwal|Penn State University|

Learning Objectives:

A. Software engineering objectives

Through implementing this coupled notebook, students will be able to design a jupyter notebook to:

1. Introduce two model grid types (network and rectilinear)
2. Connecting these two grids by layering them on top of each other.
3. Connecting two rectilinear grids by having output of one feed into the input for another.

B. Fluvial geomorphology objectives

Given a structured Jupyter notebook with parameters that can vary, students will have the opportunity to explore the synergistic effects of:

- rainfall intensity
- rainfall distribution
- sediment supply
- infiltration properties on overbank flow in a floodplain



## **Conceptual model**
<img src="https://i.imgur.com/TsYaQqu.png" alt="conceptual framework" width="500"/> 

## **Coupling stuff**
<img src="https://i.imgur.com/ty6NZyi.jpg" alt="conceptual framework" width="500"/>

## **Floodplain + Infiltration**
![gifThing](sample_output/floodplainanimation.gif?raw=true)
