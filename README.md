# DEM
Discrete element modeling using MUSEN package

This repository contains programs used for post-processing results of DEM-based modelling of rocks breakdown

Data obtained from MUSEN: Object ID, Object geometry, Material, Activity interval, Coordinate

## defect_processor

Generates file with parameters of broken bonds: coordinates, break time point, material

## defect_cluster

Generates clusters formed by broken bonds and using output of **defect_processor** in 2 ways:

- Clusters formed from experiment start till exact time point
- Clusters formed during mentioned time period
