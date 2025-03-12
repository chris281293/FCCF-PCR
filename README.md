# FCCF-PCR
Feature-Consistent Coplane-Pair Correspondence- and Fusion-Based Point Cloud Registration (2023) by  Kuo-Liang Chung, Pei-Hsuan Hsieh, and Chia-Chi Hsu. For more information, please refer to our paper:
- K. L. Chung,  C. C. Hsu and P. H. Hsieh. Feature-consistent coplane-pair correspondence- and fusion-based point cloud registration. Pattern Recognition Letters 2024. ([Paper Link](https://www.sciencedirect.com/science/article/abs/pii/S0167865524002332))

<div align=center>
<img src="https://github.com/chris281293/FCCF-PCR/blob/main/Fig/office_result.png">
</div>

The left figure is the testing set "Office" selected from the [ETH](https://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration) dataset, and the right one is the registration result using our method.
## Usage
Compiling the codes of our method in the project directory
```
mkdir build; cd build
cmake ..; make;
```
using the execution code of our method to estimate the registration solution
```
./FCCF {PATH_TO_SRC_CLOUD} {PATH_TO_TAR_CLOUD} {VOXEL_GRID_SIZE}
```
## Testing environment
* Windows Subsystem Linux (Ubuntu 20.04.6 LTS)
* ISO C++ 14

## Acknowledgement
The programming implementation of our method is based on the following resources: 
```
【1】李建微, 占家旺. 三维点云配准方法研究进展[J]. 中国图象图形学报, 2022, 27(02): 349-367. 
【2】Jianwei Li, Jiawang Zhan, Ting Zhou, Virgílio A. Bento, Qianfeng Wang. 
Point Cloud Registration and Localization Based on Voxel Plane Features [J]. 
ISPRS Journal of Photogrammetry and Remote Sensing.
```
We appreciate the authors for sharing their codes.
## Contact
If you have any questions, please email us via   
Chia-Chi Hsu: m11115040@mail.ntust.edu.tw  
Kuo-Liang Chung: klchung01@gmail.com

