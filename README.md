# Seamount-Biotrap-OTU-analysis-
##This is a project to analyze OTUs from sequences of zetaproteobacteria.

**Introduction:**
Zetaproteobacteria are iron-oxidizing bacteria that can use iron to obtain energy. Not only that, but they are also capable of doing so in different environments (both the deep ocean and estuaries)! They are only a recently described bacteria sublcass, and therefore there is still much we do not know about their growth and biogeographic patterns. This study deals with understanding the composition of artificial growth chamber set up near hydrothermal vents, where they were originally found. I have some genetic data (OTU data), which tells us the genetic similarity between these bacteria (very similar to species), as well as different environmental measurments.

**My objectives are to:**

Observe if there are differences between OTUs between two sites: Axial and Loihi

Use this project to apply the work to my thesis by analyzing what environmental factors influence how these bacteria are organized.

**Folders and Structure**

The main code for this project is labled "Data-analysis-clean-vers", which includes code after cleaning up certain data.
To see the original code, see the "BioTrap-Zetaproteobacteria-OTU-analysis"
Both files can be found in the "Scripts" folder.

Within the "Data folder", you can find the raw files from the original statistical program mothur which contain the OTU data. this is under "Raw-Data". The other data files can be found under "Organized-data".

To view associated figures, view the "Figures" folder.

**Data Analysis**
As stated previously, the raw data files contain OTU size, Taxonomy, and counts for each OTU. With this set, I created a new .csv file to include all of the information and make it more readable. This file contains OTU data for both sites (Axial and Lo'ihi).

Next, I used that .csv file to rearrange the data into something that could be analyzed by NMDS. I rearranged the data so that the samples could be arranged by specific taxa, in this case, by class.Class is a bit more descriptive than kingdom and phylum, which is why I chose it.

To get the data frame to work with NMDS, some arrangements were made to the data organization. Finally, I did my first NMDS and came up with 



**Aknowledgements**
I would like to thank my adviser, Heather FUllerton, for providing me with this data.
