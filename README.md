# VSNet: Vessel Structure-aware Network for Hepatic and Portal Vein Segmentation

This repository contains the implementation, dataset, and documentation for the paper:

	“VSNet: Vessel Structure-aware Network for Hepatic and Portal Vein Segmentation”
Authors: Jichen Xu, Anqi Dong, Yang Yang, et al.
Published in: Medical Image Analysis, 2025
DOI: 10.1016/j.media.2025.103458

![alt text](https://github.com/XXYZB/VSNet/blob/main/mask.png)

## Introduction

VSNet is a multi-task learning model designed for accurate segmentation of hepatic and portal veins from CT images. Key innovations include: 

- A vessel-growing decoder to preserve connectivity in minor vessels.
- Auxiliary tasks for centerline regression and edge segmentation.
- Evaluation on the largest public dataset for hepatic and portal vein segmentation (revised MSD dataset, 303 cases).

This repository provides:
- The source code for training and evaluation.
- The re-annotated dataset.
- Pretrained models and example predictions.


## Dataset

Description

The re-annotated dataset includes:
- 303 CT volumes with hepatic and portal vein annotations.
- Thin-slice dataset: 61 volumes with slice thickness ≤ 2mm.
- Thick-slice dataset: 242 volumes with slice thickness > 2mm.

Access

The dataset is available for download:
- Dataset link: http://medicaldecathlon.com/

The corresponding reannotated masks are in the zip file reannotated.zip


## Citation

If you use this repository, please cite:

```
@article{dong2025vsnet,
  title={VSNet: Vessel Structure-aware Network for Hepatic and Portal Vein Segmentation},
  author={Jichen Xu, Anqi Dong, Yang Yang, et al.},
  journal={Medical Image Analysis},
  year={2025},
  doi={10.1016/j.media.2025.103458}
}
```

## License

This project is licensed under the MIT License. See LICENSE for more details.


## Contact

For any questions or issues, feel free to contact:
- Jichen Xu: branrafa95@gmail.com
- Anqi Dong: anqid@kth.se
- Bo Wang: bow@hust.edu.cn
 
