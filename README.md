# Bathymetry Prediction Using Sentinel-2 Imagery with Prithvi Foundational Model

This repository is used for submitting the final project for the Urban Computing course in 2024.

## Abstract

Accurate bathymetric mapping is essential for applications such as navigation, coastal management, and environmental monitoring. Traditional methods, such as acoustic sounding and LiDAR, are expensive and face challenges in shallow waters. Recent advances in remote sensing and deep learning, particularly with datasets like MagicBathyNet, have demonstrated the potential to leverage satellite imagery for bathymetry prediction.

In this study, we explore the use of the Prithvi foundational model, pretrained on geospatial tasks, to develop a cost-effective bathymetry prediction framework using only Sentinel-2 RGB data. Unlike the multimodal approaches in MagicBathyNet, our method focuses on Sentinel-2 imagery to improve accessibility and scalability. We compare the performance of native resolution (18x18) and upscaled resolution (~200x200) image patches, resized using nearest-neighbor interpolation. Furthermore, we evaluated the generalizability of the model in geographically distinct regions, Agia Napa and the Puck Lagoon, through cross-location validation and mixed-location training.

Our preliminary results indicate that Prithvi outperforms baseline models like U-Net in terms of RMSE and MAE by approximately X% (assumption). Mixed-location training improves generalization across locations, while upscaled resolutions demonstrate marginal performance gains. These findings highlight the potential of foundational models such as Prithvi for scalable, accurate, and cost-effective bathymetry prediction using globally available data.

## Authors 
Group 15
- Vinson Ciawandy
- Sasank Amavarapu

## Dataset

The dataset used in this study is available at: MagicBathyNet Dataset.
