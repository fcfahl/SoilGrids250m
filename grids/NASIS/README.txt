Preliminary predictions for USDA Great Groups (see NASIS domain name: "taxonomic_great_group") and PSCS classes (texture determination on field; see NASIS domain name: "taxonomic_family_particle_size")

Points prepared by: T. Nauman (tnauman@usgs.gov) and D. Beaudette (debeaudette@ucdavis.edu)
Model fitting and predictions by: T. Hengl (tom.hengl@isric.org)

Inputs: National Soil Information System (NASIS) and NCRS National Soil Characterisation DB; about 350,000 points in total; as covariates we use global SoilGrids250m covariates (https://github.com/ISRICWorldSoil/SoilGrids250m/blob/master/grids/covs1t/SoilGrids250m_COVS250m.csv) ca 160 layers;
Outputs: Predicted probabilities per class based on randomForest predictions (fitted using the 'ranger' software)
Lineage: Preparation of point data is documented at: https://github.com/naumi421/nasis_prep and model fitting at: https://github.com/ISRICWorldSoil/SoilGrids250m/tree/master/grids/NASIS. To request access to point data please contact T. Nauman (tnauman@usgs.gov). NASIS domains can be found at: http://www.nrcs.usda.gov/wps/PA_NRCSConsumption/download?cid=stelprdb1247050&ext=pdf

Disclaimer: These are preliminary (unvalidated) results subject to constant updates. Please, do NOT distribute these maps without consulting the authors (use only for testing purposes). See also: http://www.isric.org/content/disclaimer-soilgrids. Final maps will (most likely) be made publicly available under the Open Data Base License (http://opendatacommons.org/licenses/odbl/summary/) in mid 2016. To report a bug or artifact in the map please use: https://github.com/ISRICWorldSoil/SoilGrids250m/issues.