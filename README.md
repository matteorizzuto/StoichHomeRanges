# Stoichiometry of Consumer Space Use
This repository contains code, data, and results for Rizzuto et al. Forage stoichiometry predicts the home range size of a small terrestrial herbivore.

Code contains the R notebooks necessary to replicate our analyses

* *SupportingCode.Rmd* contains the load statement for all R packages needed to run our analyses; it is also a modular notebook that compiles into the Supporting Code document for our paper
* *1_TriangulationError.Rmd* performs analyses to quantify the triangulation error of two of the observers who collected the telemetry data
* *2_razimuthTriangulation.Rmd* performs triangulation of our snowshoe hare telemetry data using package [razimuth](https://github.com/cppeck/razimuth)
* *3_aKDEHomeRangeEstimation.Rmd* uses package ctmm to estimate the utilization distribution (UD) of our study animals, estimate home range size from the UD, and extract stoichiometric data from two preferred forage plant species from within the home range
* *4_HomeRangeOverlap.Rmd* investigates UD overlap among four snowshoe hares sampled for more than one year
* *5_ModelStoichHR.Rmd* models the relationship between plant stoichiometry and snowshoe hare home range size estimated at the 50% UD isopleth
* *6_75kUDHRModels.Rmd* and *7_90kUDHRModels.Rmd* repeat our modeling using snowshoe hare home range size estimated at the 75% and 90% UD isopleths, respectively
* *8_AdditionalPlots.Rmd* produces the manuscript figures as well as a suite of supporting visual materials
* *function-plotOutlier.R* and *function-plotVariograms.R* are scripts containing custom functions developed by [Amanda Droghini](https://github.com/adroghini), used in our razimuth workflow

Data contains all data necessary to replicate our analyses

* *VHF_CleanData_2017.csv*, *VHF_CleanData_2018.csv*, and *TelemetryPoints_VHF_2019.csv* contain the raw snowshoe hare triangulation data from three consecutive years of sampling
* *Plant_Browse.csv* contains data on snowshoe hare and moose plant browsing within our snowshoe hare live-trapping grid, used to produce Figure S7 in the Supplementary Information
* *MR_ErrorReduction.csv* and *BS_ErrorReduction.csv* contain the triangulation data from triangulation error reduction exercises and are used in TriangulationError.Rmd
* *ErrorTrials_trueLocs.csv* contains the true locations of the radiocollars using the the triangulation error reduction exercises and in TriangulationError.Rmd to estimate average error for two observers
* *../Data/StDMS_Rasters/* is a folder containing raster files of the ecelogical stoichiometry of lowland blueberry (VAAN) and red maple (ACRU) used in our analyses

Results contains the output of the more time-consuming and computationally intensive steps of the analyses, for ease of replication
* *razimuth_lsfits.rds*, this file contains the results from fitting the azimuthal telemetry model from package [razimuth](https://github.com/cppeck/razimuth) to our triangulation data and is called in the razimuthTriangulation.Rmd notebook to speed up the triangulation process
* *razimuth_errorT_lsfits.rds*, contains the results from fitting the aimuthal telemetry model to the error reduction exercises data to estiamte mean telemetry error of two observers
* *harestelemclean_final.rds* and *haresfite_final.rds*, contain the final telemetry dataset after outlier removal and final ctmm fits to our telemetry dataset
*   *finalmodelse.rds*, contains the ctmm models that best fit our telemetry dataset
