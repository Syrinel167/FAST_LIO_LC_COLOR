# Code Sources
- [FAST-LIO-LC](https://github.com/yanliang-wang/FAST_LIO_LC)  
- [FAST-LIO-COLOR-MAPPING](https://github.com/YWL0720/FAST-LIO-COLOR-MAPPING)

This repository integrates the color mapping functionality from **FAST-LIO-COLOR-MAPPING** into **FAST-LIO-LC**, enabling the generation of colored point clouds in real time.

## Generating Colored PCD Files
To create colored PCD files, implement a ROS node that subscribes to the `"/color_pc"` topic. The node will then process the incoming data and output `.pcd` files that include color information. See [this](https://github.com/Syrinel167/color_mapping_pcd_file_saving).
