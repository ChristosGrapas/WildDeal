# The Wild Deal 

**The Wild Deal is a project of IAAC, Institute for Advanced Architecture of Catalonia developed in the Master in City & Technology 01 - 2022-2023 by the student(s), Christos Grapas,  Reda Petravičiūtė and Roman Pomazan during the course MaCT01 22/23 Internet of Cities with Eduardo Rico, Mathilde Marengo and Iacopo Neri.**

![Wild Deal Connectivity](https://user-images.githubusercontent.com/128100178/225778869-3dd00295-0a55-4b69-b3ca-4a155242fe2b.png)

This study aims to highlight the  urgency of environmental connectivity  through rewilded landscapes given  back to nature as part of wild species.
By identifying the possible conflicts between human - boar activity as well as by locating the four areas with the highest natural connectivity, this project explores the potential of land types and the built space to be transformed into rewilded landscapes. By creating rewilded landscapes, the “Wild Deal” takes into consideration the ways that both human and wild spcecies could benefit from the adaptation of wildlife to peri-urban environments and vice versa

![Map_1](https://user-images.githubusercontent.com/128100178/225910197-fa6e673f-4fc3-46dc-911c-aa1edf9a9cd9.png)

**This study employs geographic information systems and algorithmic planning techniques to assess the ecological connectivity of peri-urban areas in Barcelona based on land use, in order to identify potential sites that contribute to fragmentation of natural habitats and biodiversity loss.**

![Selected Areas_ Connectivity_cg](https://user-images.githubusercontent.com/128100178/225777718-7e6b14a4-e995-4ea7-b45b-7446cec99ccb.png)

The methodology involves the utilization of (a) GIS technology, (b) circuit theory-based software for modelling connectivity in complex landscapes, and (c) algorithmic design software for processing connectivity analysis data. The model has potential applications in analyzing the movement and distribution of plant and animal species, identifying ecologically significant areas for conservation efforts, designing natural corridors to facilitate species migration, and pinpointing critical locations for environmental emergency management.

![A3 IMAGES LAYOUT_Wild_Deal-4](https://user-images.githubusercontent.com/128100178/225910575-4ac91e33-2cf7-4388-94b2-b02d2ee4d34c.png)

# Software Requirements for Environmental Connectivity Analysis:

1. **QGis**. The connectivity analysis is based on the classification of land uses from the CORINE Land Cover (CLC) inventory. After downloading the rasterfile from the CLC the reclassification aims at creating different kinds of resistances per selected land-use. The process in QGis will be done as soon as we also set the points of  our interest. In this case we set them in the areas habitated by wild species. 

2. **Circuiscape**. Circuitscape is an award-winning connectivity analysis software package which borrows algorithms from electronic circuit theory to predict patterns of movement, gene flow, and genetic differentiation among plant and animal populations in heterogeneous landscapes. Importing the resistances and the points of attraction constructed in QGis the program will produce a geo-located raster file, which can be imported again back to the QGis. 
