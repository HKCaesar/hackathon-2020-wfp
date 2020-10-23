# better-hackathon-2020-wfp


## Run the notebook on Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ec-better/hackathon-2020-wfp/master?urlpath=lab)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/WFP-VAM/hackathon-2020-wfp/master?urlpath=Crop-Type-Classification.ipynb)

## Enhancing Agricultural Mapping with BETTER Pipelines

The UN World Food Programme is the world's largest humanitarian organization, assisting 100 million people in 88 countries. Timely and accurate mapping of agricultural activity using EO satellite data provides valuable information to improve the livelihood of vulnerable people and to respond to emergencies effectively.


Various factors can make agricultural mapping challenging:

- Accessibility constraints due to conflict and hazards
- Limited availability of ground-truth data
- Frequent cloud cover
- Predominance of small-holder agriculture


## Exercise Description

The exercise will evaluate the impact of using and combining various types of data streams provided by the BETTER pipelines over a region of interest in Adamawa, Nigeria.

The dataset provided to the participants include:

- Filtered and unfiltered Sentinel-2 time-series data
- SAR Sentinel-1 backscatter time-series data
- Crop type information for a set of training points

The data is provided in an analysis-ready format for point locations sampled from delineated agricultural fields acquired during a recent data collection campaign.

After a short introduction, participants develop their classification models based on the training data and subsequently apply them to a validation data set for inter-comparison of the quality of the crop type mapping outputs. The exercise can be performed using Binder or locally, after downloading the datasets.


## Computing resources

Binder runs the experiments for free with computing resources provided by Google Cloud, OVH, GESIS Notebooks and the Turing Institute.
The notebook must target a computing environment with 2 GB of RAM

After some inactivity, the docker container is culled. 
