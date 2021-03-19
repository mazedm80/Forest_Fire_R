Lionshead WildFire burn severity map and data preperation using Satellite and LiDAR data for Machine Learning
================
Mir Mazedur Rahaman
2/7/2021

## Project Objectives
This repo houses an R Markdown Document that has code chunks for
- Pre Processing of Landsat images of Pre fire and Post fire.
- Calculating pre and post NBR and dNBR.
- Classification of dNBR.
- Process LiDAR data
- Produces LiDAR metrics
- Merge LiDAR metrics and burn severity and export the dataframe as csv file
This script is currently used for my Practicle Research project masters course. Since this script has not been fully vetted, caution should be taken if used for research.

## Input files stored in the /data folder
* Since the Landsat file is too big the **/data** folder is ignored

## Output files stored in the /output folder
* Due to big files the **/output** folder is also ignored

## Requirements
This project is developed suing the following packages:
* R version 4.0.3
* `RStoolbox` 0.2.6
* `rgdal` 1.5
* `ggplot2` 3.3.2
* `viridis` 0.5.1
* `LidR` 3.0.4
* `dplyr` 1.0.2
* `viridis` 0.5.1
* `devtools` 2.3.2
* `data.table` 1.13.2
* `future` 1.21.0
