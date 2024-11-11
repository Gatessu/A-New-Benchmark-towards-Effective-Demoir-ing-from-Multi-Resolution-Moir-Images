# Multiresolution and Target Alignment Demoiréing Dataset (MTADM)

## Overview
The Multiresolution and Target Alignment Demoiréing Dataset (MTADM) is a novel dataset designed to support research in the field of ultra-high-resolution image demoiréing. This dataset was constructed to address challenges in real-world scenarios where source image resolutions vary, and moiré patterns differ based on capture devices.

**Key Features of MTADM:**
- **4K Moiré Images with Multi-resolution Sources**: The dataset includes 4K moiré images generated from various source resolutions, reflecting the diversity found in real-world applications.
- **Original Moiré Preservation**: By aligning target images to moiré images, the dataset maintains original moiré information and minimizes aliasing issues.
- **Diverse Real-world Scenes**: Captured from different environments, the dataset includes scenes such as landscapes, portraits, and text, presenting diverse perspectives and practical applications.

## Access
This dataset is currently in the pre-release phase as the associated paper is under review for publication. Upon acceptance and publication of the paper, the dataset will be made publicly available.

**Planned Release Platform**: The dataset download link will be provided through a Baidu Netdisk link on this GitHub page.

**License**: The dataset will be shared under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/), allowing users to use, distribute, and adapt the dataset with proper attribution for non-commercial purposes.

## Dataset Composition
- **Total Image Pairs**: 3,000
- **Training Pairs**: 2,500
- **Validation Pairs**: 500
- **Image Resolutions**: Ranging from 480p to 4K
- **File Format**: JPEG (.jpg)

## Structure
The dataset will be organized as follows:
```
MTADM/
|-- train/
|   |-- 0001_shoot.jpg
|   |-- 0001_gt.jpg
|   |-- 0002_shoot.jpg
|   |-- 0002_gt.jpg
|   ...
|-- val/
|   |-- 2501_shoot.jpg
|   |-- 2501_gt.jpg
|   |-- 2502_shoot.jpg
|   |-- 2502_gt.jpg
|   ...
```

## How to Use
1. Check this GitHub page for the Baidu Netdisk link once the dataset is released.
2. Follow the provided instructions to download the dataset.
3. Refer to the documentation for best practices on loading and using the data.

## Citation
If you use the MTADM dataset in your research, please cite our paper (citation details will be updated after publication).

**Note**: This README will be updated with the Baidu Netdisk link and citation information once the associated paper is published.

