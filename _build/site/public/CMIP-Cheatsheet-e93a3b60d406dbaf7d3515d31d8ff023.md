---
title: "CMIP Cheatsheet"
---

# Basic Vocabulary

CV: controlled vocabulary

	- Global attributes are used to describe the source of the data, the imposed experiment conditions, the contents of the file, licensing restrictions, and other information useful to those analyzing the data. CVs define the global attributes that should appear in CMIP6 files
	- https://github.com/WCRP-CMIP/CMIP6_CVs?tab=readme-ov-file 

MIP: model intercomparison project

	- There are 21 CMIP6-endorsed MIPs
	- https://www.wcrp-climate.org/modelling-wgcm-mip-catalogue/cmip6-endorsed-mips-article?start=20 

DRS: data reference syntax

	- Defines the structure and location of data files

CF Conventions: climate and forecast model metadata conventions

	- Defines the formatting of .netcdf files and attributes
	- https://cfconventions.org/ 

# Data reference syntax (DRS)

	- https://docs.google.com/document/d/1h0r8RZr_f3-8egBMMh7aqLwy3snpD6_MrDz1q8n5XUk/edit 

| Dataset Name| Description | 
|:------------|:------------|
| CMIP6       | mip_era     | 
| CMIP       | activity_id  |
| MOHC       | institution_id |
| UKESM1-0-LL       | source_id     |
| historical       | experiment_id     |
| r1i1p1f2       | member_id     |
| Lmon       | table_id     |
| cVeg       | variable_id     |
| gn       | mip_era     |
| v20190627       | version     |
| .nc       | .nc     |

# Activity Id

The various MIPs that are part of the CMIP6 framework. Each activity ID corresponds to a specific MIP, focusing on different aspects of the climate system, processes, and scientific questions.

| Acronym   | Full Name                                                                      |
|:----------|:-------------------------------------------------------------------------------|
| CMIP      | Coupled Model Intercomparison Project                                          |
| DAMIP     | Detection and Attribution Model Intercomparison Project                        |
| DCPP      | Decadal Climate Prediction Project                                             |
| GeoMIP    | Geoengineering Model Intercomparison Project                                   |
| HighResMIP| High Resolution Model Intercomparison Project                                  |
| ISMIP6    | Ice Sheet Model Intercomparison Project for CMIP6                               |
| LUMIP     | Land Use Model Intercomparison Project                                         |
| OMIP      | Ocean Model Intercomparison Project                                            |
| PAMIP     | Polar Amplification Model Intercomparison Project                              |
| PMIP      | Paleoclimate Modelling Intercomparison Project                                 |
| RFMIP     | Radiative Forcing Model Intercomparison Project                                |
| ScenarioMIP| Scenario Model Intercomparison Project                                        |
| SIMIP     | Sea Ice Model Intercomparison Project                                          |
| VIACSAB   | Vulnerability, Impacts, Adaptation and Climate Services Advisory Board         |
| VolMIP    | Volcanic Forcings Model Intercomparison Project                                |
| C4MIP     | Coupled Climate-Carbon Cycle Model Intercomparison Project                    |
| FAFMIP    | Flux-Anomaly-Forced Model Intercomparison Project                              |
| LS3MIP    | Land Surface, Snow and Soil Moistures Model Intercomparison Project            |
| GMMIP     | Global Monsoons Model Intercomparison Project                                  |
| CORDEX    | Coordinated Regional Climate Downscaling Experiment                            |
| CFMIP     | Cloud Feedback Model Intercomparison Project                                   |
| AerChemMIP| Aerosols and Chemistry Model Intercomparison Project                           |
| DynVarMIP | Dynamics and Variability Model Intercomparison Project                         |
| CDRMIP    | Carbon Dioxide Removal Model Intercomparison Project                           |



