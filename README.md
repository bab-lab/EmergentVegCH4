This README file was generated on 2026-02-10 by Kelsey McGuire and updated on 2026-08-14 by Kelsey McGuire. 

**STUDY**: Aquatic vegetation and CH4 emission and production responses 

**DESCRIPTION/SUMMARY**
Our study was conducted in the summer of 2025 in Kaska Ancestral Territory (Northern British Columbia, Canada) and our main objectives were to **(1)** understand how emergent vegetation influences overall methane flux and **(2)** how benthic vegetation influences potential methane production. 

Our field study was mainly to address objective 1, where we collected data across 18 sampling points, 9 vegetated and 9 open (i.e., non-vegetated). We sampled for both bubble and diffusive/plant-mediated flux using bubble traps and floating chambers respectively. Alongside flux measurements, we measured environmental conditions during each measurement, this included water temperature, % DO, and pH. The data from this sampling can be found in [DATA FILE]. 

Objective 2 was addressed through a laboratory incubation, where we collected sediment, benthic vegetation, and lake water samples during our field study and proceeded to run an incubation 6 months later. This incubation was run over the course of two-weeks where we collected headspace concentrations, and then nutrient and organic matter information post-hoc. The data from this experiment can be found in [DATA FILE].

This repository contains the data and code to reproduce the results from chapter 2 of Kelsey McGuire's thesis (2026): A little sedge goes a long way: .

**RESEARCH METHODOLOGY**
Environmental soil samples were collected from green spaces in Toronto and used to evaluate several commonly used adsorption isotherm equations, including the Langmuir, Freundlich, Temkin and Toth equations, to determine their applicability in lightly managed and non-fertilized soils. We then compare ammonia emission potentials (a quantity predicting the propensity of ammonia to volatilize from a liquid reservoir) determined using a conventional high-salt extraction procedure to determine the soil ammonium content to that modelled using the Temkin and Langmuir equations and demonstrate that conventional approaches may overestimate emission potentials from soils by a factor of 5–20.

**SOFTWARE/TOOLS USED**
- R version TBD
- R packages used:

**DOI/PERSISTENT IDENTIFIERS**
Hyperlinked DOI for this dataset: TBD

**LICENSE INFORMATION**
The terms under which this dataset may be used follows the CC BY-SA 4.0 license. 

**AUTHOR/CREATOR INFORMATION**
Position: Author
Name: Kelsey McGuire
Institution: University of British Columbia
Address: https://sites.chem.utoronto.ca/murphygroup/content/matthew-davis
Email: m.davis@utoronto.ca

Position: Principal investigator, corresponding author
Name: 
ORCID:
Institution: University of Toronto
Address: https://sites.chem.utoronto.ca/murphygroup/pi
Email: jen.murphy@utoronto.ca

Position: Author
Name: Kevin Yan
ORCID:
Institution: University of Toronto
Address: https://sites.chem.utoronto.ca/murphygroup/content/kevin-yan
Email: k.yan@utoronto.ca

All experimental results can be reproduced using the code and data in this repository. Feel free to contact Jennifer Murphy (corresponding author) by email at jen.murphy@utoronto.ca if you have any questions about our work. 

RELATED PUBLICATIONS
Journal article citation for this dataset: Davis, M. G., Yan, K., and Murphy, J. G. Evaluating adsorption isotherm models for determining the partitioning of ammonium between soil and soil pore water in environmental soil samples, Biogeosciences, 21, 5381–5392, https://doi.org/10.5194/bg-21-5381-2024, 2024.

Citation for Matthew Davis's thesis:  Davis, M. G. (2024). An investigation of local and regionally significant non-agricultural sources of ammonia in Toronto and the Great Lakes Region. [Doctoral dissertation, University of Toronto]. University of Toronto TSpace. http://hdl.handle.net/1807/140872 

FILE LIST/DIRECTORY
- `src/` contains source code for the adsorption curves and environmental soils analysis. This contains Rmd files to generate the models and plots in the paper.
- `data/` contains all the data used in this project. This subdirectory contains a data dictionary. 

ACKNOWLEDGEMENTS 
We thank our colleagues Myrna Simpson and Jenny Oh (University of Toronto) for their helpful discussions. We also thank the University of Toronto ANALEST facility staff for their technical assistance.
This research has been supported by the Natural Science and Engineering Research Council (NSERC) Discovery grant (grant no. RGPIN-2022-05241) and a grants and contributions agreement GCXE19S016 with Environment and Climate Change Canada held by Jennifer Murphy. Matthew Davis held a Walter C. Sumner Memorial Fellowship while conducting this research. An undergraduate summer research award from NSERC supported Kevin Yan during this work.
