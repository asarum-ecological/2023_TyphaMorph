# Repository for Stewart, Buckholtz et al. (2023)

![Cattail](https://github.com/asarum-ecological/2023_TyphaMorph/blob/cd9ff2fab316cc6e35af3f346def201c96ad3e4e/Picture.jpg)

Welcome to the repository for our journal article entitled "Macroscopic traits effectively identify hybrid cattail (<i>Typha</i> × <i>glauca</i>) in the Fraser River Estuary, British Columbia ", which was published in XXXX in 2023. 

You will find the following in this repository:

#### [Publication Files](https://github.com/asarum-ecological/2023_TyphaMorph/tree/main/Publication%20Files)
  - a .pdf of the accepted manuscript
  - a .pdf of the digital supplemental materials 

#### [Spatial Data](https://github.com/asarum-ecological/2023_TyphaMorph/tree/main/Spatial%20Data)
  - precise locations of all <i>Typha</i> samples (morphological and genetic) in the estuary
  
#### [Data](https://github.com/asarum-ecological/2023_TyphaMorph/tree/main/Data)
  - morphological data 

#### [Code](https://github.com/asarum-ecological/2023_TyphaMorph/tree/main/Code)
  - R Code used to generate plots and conduct analyses
#### [Plot Data](https://github.com/asarum-ecological/2023_TyphaMorph/tree/main/Plot%20Data)
  - R scripts to plot both the triangle plot and MDS plot 
  - HIest package as it was removed from CRAN repository post-analysis 
  - Raw data used in plots
    - HIest_Formatted_G.csv contains genetic marker data in which each columnin a locus and there are two 
    rows for each individual since the allele type is="codominant"
    - HIest_Formatted_P.csv contains the locus name, allele name, P1 allele frequency, P2 allele frequency. contains a seperate row for each allele 
    - GenAlExPoppr.csv contains all individuals and their alleles at particular loci which are listed in the 3rd row. It is formatted for calculating Bruvo's distance 
    - Typha_Mean_Data.csv contains morphological data used in randomForest analysis



The extent of non-native cattail in the estuary continues to be investigated. For an up to date map of field-verified cattail please visit this [link](https://www.google.com/maps/d/u/0/edit?mid=1Gxm6n921sl6ph-dF6LTEKDhTrqaUaCoK&ll=49.137229809022216%2C-123.15205739999999&z=11).

Should you have any inquiries, please feel free to email [Daniel Stewart](mailto:daniel.stewart@asarum.org) or [Gracy Buckholtz](mailto:gracybuckholtz@gmail.com).
