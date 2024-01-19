## Multisource Transfer Learning for Remote Sensing Image Classification

## Overview

This repository contains the code and data for the  paper titled "Improving Remote Sensing Classification with Transfer Learning: Exploring the Impact of Heterogeneous Transfer Learning," presented at the 4th International Electronic Conference on Applied Sciences. 

The paper delves into the challenges of applying deep learning (DL) in remote sensing (RS) due to the scarcity of well-annotated training data from multiple sources such as satellites, airplanes, and drones. The proposed solution involves the use of transfer learning (TL) to adapt models trained on one source to perform well on data from other sources.

## Data Description

Our dataset comprises two subsets derived from satellite images acquired by (Sentinel-2) S2 and (Landsat-9) L9, covering seven spectral bands (blue, green, red, near-infrared, shortwave infrared 1, shortwave infrared 2) and calculated indices: NDVI (Normalized Difference Vegetation Index) and NDWI (Normalized Difference Water Index).

- **S2 Data:** Collected in 2023 using a single raster image, accompanied by a cloud mask to detect and mask cloudy areas.
  
- **L9 Data:** Gathered over three years, from 2021 to 2023, utilizing a series of five raster images. It also incorporates a cloud mask for the identification and exclusion of cloudy regions.

## Research Paper

The research paper is available at [Improving Remote Sensing Classification with Transfer Learning: Exploring the Impact of Heterogeneous Transfer Learning](https://doi.org/10.3390/ASEC2023-15505). The paper was presented at the 4th International Electronic Conference on Applied Sciences on October 27–November 10, 2023. You can find it online at [asec2023.sciforum.net](https://asec2023.sciforum.net/).

## Repository Structure

- **code:** Contains the code for the transfer learning approach implemented in the paper.
  
- **Data:** Includes the datasets used in the research, facilitating replication and further experimentation.

## Abstract

Deep learning has gained traction in various fields, including remote sensing (RS). However, the high cost of acquiring and labeling RS data hinders the development of DL models in this domain. The repository addresses this challenge by proposing a transfer learning approach. RS data, sourced from satellites, airplanes, and drones, can have different characteristics. Training DL models on data from one source may not yield optimal results on data from other sources. Transfer learning mitigates this issue, allowing models to adapt to new sources with fewer training data. The paper evaluates homogenous and heterogeneous TL approaches, measuring transfer gain through statistical metrics such as precision, kappa, recall, and F1-score. Positive gains are empirically shown in the majority of cases, particularly on the challenging task of Multispectral RS image (MSI) classification. The paper explores the social, economic, and environmental consequences of this work and suggests potential future research directions.

## Contact

For inquiries or collaboration opportunities, please reach out to Maria Roubamaria at [roubamaria645@gmail.com](mailto:roubamaria645@gmail.com).
