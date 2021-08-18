# mit_calvin
Code for Calibration Value INtegration (CalVIN) project at the Engineering Systems Laboratory (ESL). Tools for analysis include the Google Earth Engine (GEE) Javascript and Python APIs, [NASA SeaDAS software](https://seadas.gsfc.nasa.gov/), and ArcGIS Pro. The results were incorporated into my undergraduate thesis, which will be available on the MIT DSpace and can be sent upon request. 

## Abstract
Earth Observation through satellites enables decision makers to assess situations near
real-time with unprecedented spatial coverage. The data-value added products from
radiometric satellite images often use indices derived from the unique spectral properties
of materials and are sensitive to the relative gains of the different bands of the
satellite sensor. However, satellite sensors are susceptible to degradation from the
space environment, leading to drift in band response. For well-calibrated satellites
such as Landsat 8, these drifts are well characterized and can be corrected for during
processing—however, for satellites lacking on-board calibration (such as CubeSats),
these trends can be difficult to detect and require novel methods combining cross
calibration with machine learning. Given that satellite data often undergoes several
levels of processing prior to use, there is a need to quantify the relationship between
calibration errors and the errors of the final data-valued added product. This study
investigates two applications of Earth Observation data: crop classification and Harmful
Algal Bloom detection, and quantifies the impact of induced radiometric error on
the final data product.
## Case 1: Crop Classification

### Google Earth Engine Scripts

#### Background modules
- Band Perturbations: https://code.earthengine.google.com/0bedffd12b7460f45f90ace6186a8823
- Compositing: https://code.earthengine.google.com/e8a1e04b768a68969a052f6e9ae3ca0b
- Classification: https://code.earthengine.google.com/b3eb2917ef576e41cbb626776a3224c1

#### Specific Study Sites
- California: https://code.earthengine.google.com/72fc181029796c59b8fe1f5b33c70251
- Illinois: https://code.earthengine.google.com/adec337ee52c15379cc0cc6e72dd0835
- North Carolina: https://code.earthengine.google.com/89881ad525c399ca2ca5a47e469e

## Case 2: Harmful Algal Bloom (HABs) Detection

### Google Earth Engine Scripts

#### Specific Study Sites:

- Lake Erie: https://code.earthengine.google.com/66b901dc7141f481fb69d356f1b0aa07
- Lake Okeechobee: https://code.earthengine.google.com/aa83f7c82c6073866d84d6f0fbd234ec
