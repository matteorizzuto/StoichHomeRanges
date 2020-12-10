Forage stoichiometry predicts the home range size of a small terrestrial herbivore	
	
This dataset contains data used in the meta-analysis we performed to investigate the relationship between elemental content and macromolecule content of food.	
The dataset comprises two different sheets:	
* LitRev, which contains qualitative data on n = 101 studies we selected and reviewed from the Champagne et al. (2020) J Chem Ecol and Felton et al. (2018) Ecosphere	
* Data, which contains quantitative data extracted from tables and figures of n = 40 studies selected among those listed in LitRev, based on their reporting of both elemental and macromolecular food content data	
	
Here is a list of the fields populated in each sheet, with a brief description of each	
	
**LitRev - Fields**	
| ID                | unique numberic identifier assigned to the study for our meta-analysis                      |
|-------------------|---------------------------------------------------------------------------------------------|
| Reference         | abbreviated reference, include authors, year, and journal                                   |
| OrigStudy         | the dataset in which we found the study, either "Champagne" or "Felton"                     |
| OrigStudyID       | the ID the study had in the dataset in which it was originally listed                       |
| Accessed          | date of first access to the study                                                           |
| Group             | grouping variable based on study species, either "Bunny" for leporids or "Deer" for cervids |
| Herbivore 1       | species name (latin) of main herbivore study species                                        |
| Herbivore 2       | species name (latin) of secondary herbivore study species                                   |
| Herbivore 3       | species name (latin) of tertiary herbivore study species                                    |
| PlantGroup        | which Family do the plant study species belong to                                           |
| Plant species     | list of species names (latin) of plant included in the study                                |
| # plant species   | total number of plant species included in the study                                         |
| Study type        | type of study, one of more of Cafeteria trial, Field obs(ervation), or Field test           |
| Stoichiometry?    | did the study record ecological stoichiometry (i.e. elemental) data?                        |
| Nitrogen          | did the study record nitrogen content                                                       |
| Phosphorus        | did the study record phosphorus content                                                     |
| Carbon            | did the study record carbon content                                                         |
| Macronutrients    | did the study record macromolecular data?                                                   |
| Protein           | did the study record protein content                                                        |
| Carbohydrate      | did the study record carbohydrates content                                                  |
| Fibre             | did the study record fibre content                                                          |
| Ash               | did the study record ash content                                                            |
| Fat               | did the study record fat content                                                            |
| Conversion factor | did the study used a conversion factor to estimate protein from nitrogen                    |
| PSM               | did the study record plant secondary metabolites (PSM)                                      |
| Notes             | any additional notes                                                                        |
	
**Data - Fields**
| ID                        | unique numberic identifier assigned to the study for our meta-analysis                 |
|---------------------------|----------------------------------------------------------------------------------------|
| Herbivore                 | herbivore study species the data collected refer to                                    |
| Herbivore Scientific Name | latin name for the herbivore the data collected refer to                               |
| Plant Species             | plant species the data collected refer to                                              |
| Plant Scientific Name     | latin name for the plant species the data collected refer to                           |
| Plant group               | which Family do the plant study species belong to, if possible to ascertain            |
| N                         | nitrogen content                                                                       |
| P                         | phosphorus content                                                                     |
| C                         | carbon content                                                                         |
| StoichUnits               | units of measurement for elemental content data                                        |
| Protein                   | protein content                                                                        |
| Carbohydrate              | total non-structural carbohydrates content                                             |
| UnspFiber                 | unspecified fiber content, fiber that is not otherwise identifed in the original study |
| NDF                       | Neutral Detergent Fiber (NDF) content                                                  |
| ADF                       | Acid Detergent Fiber (ADF) content                                                     |
| Cellulose                 | cellulose content                                                                      |
| Hemicellulose             | hemicellulose content                                                                  |
| Lignin                    | lignin content                                                                         |
| ADL                       | Acid Detergent Lignin (ADL) content                                                    |
| Fat                       | lipid content                                                                          |
| Ash                       | ash content                                                                            |
| MnUnits                   | units of measurement for macronutrient data                                            |
| Terpenoids                | terpenoids content                                                                     |
| TerpUnits                 | units of measurement for terpenoids data                                               |
| Tannins                   | tannins content                                                                        |
| TannUnits                 | units of measurement for tannin data                                                   |
| Phenolics                 | phenolics content                                                                      |
| PhenUnits                 | units of measurement for phenolics data                                                |
| Resins                    | resins content                                                                         |
| ResUnits                  | units of measurement for resins data                                                   |
| Monterpenes               | monoterpenes content                                                                   |
| MoneTerpUnits             | units of measurement for monoterpenes data                                             |
| SourceInPaper             | did the data come from a table, figure, or supplementary information?                  |
| Notes                     | any additional notes                                                                   |
| Ref                       | full citation for the original source of the data                                      |