# TL_RS
Multisource Transfer Learning for Remote Sensing Image Classification

This repository contains code and data for the paper "Multisource Transfer Learning for Remote Sensing Image Classification." 
Deep Learning (DL) has gained popularity in recent years for various applications. However, Remote Sensing (RS) poses unique challenges due to the scarcity of well-annotated training data from multiple sources such as satellites,
airplanes, and drones.

Data Description


Our dataset comprises two subsets derived from satellite images acquired by S2 and L9, encompassing seven spectral bands (blue, green, red, near-infrared, shortwave infrared 1,
shortwave infrared 2), along with calculated indices: NDVI (Normalized Difference Vegetation Index) and NDWI (Normalized Difference Water Index).

S2 Data: Collected in 2023 using a single raster image, along with a cloud mask to detect and mask cloudy areas.

L9 Data: Gathered over three years, from 2021 to 2023, using a series of five raster images, and it also incorporates a cloud mask for the identification and exclusion of cloudy regions.
