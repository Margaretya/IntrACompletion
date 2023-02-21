# Multi-Scope Feature Extraction for Intracranial Aneurysm 3D Point Cloud Completion
This is the IntrACompletion dataset for "Multi-Scope Feature Extraction for Intracranial Aneurysm 3D Point Cloud Completion". It can be download from [Google Drive](https://drive.google.com/file/d/17vk5jrtvBw8xaEKag5-CJo5D4w6Kmun-/view?usp=share_link).  

![examlple](https://github.com/Margaretya/IntrACompletion/blob/main/Dataset/angles.png)
## BibTex
Please cite our work as follows if you are using our IntrACompletion dataset.
```
@Article{cells11244107,
AUTHOR = {Ma, Wuwei and Yang, Xi and Wang, Qiufeng and Huang, Kaizhu and Huang, Xiaowei},
TITLE = {Multi-Scope Feature Extraction for Intracranial Aneurysm 3D Point Cloud Completion},
JOURNAL = {Cells},
VOLUME = {11},
YEAR = {2022},
NUMBER = {24},
ARTICLE-NUMBER = {4107},
URL = {https://www.mdpi.com/2073-4409/11/24/4107},
PubMedID = {36552872},
ISSN = {2073-4409},
DOI = {10.3390/cells11244107}
}
```
## Dataset
IntrACompletion dataset organized as follows:
```
INtrACompletion data
    |-- train
        |-- partial
        |-- complete
    |-- test
        |-- partial
        |-- complete
    |-- val
        |-- partial
        |-- complete
    |-- IntrACompletion.json
```
## Acknowledgement
We follow [PCN](https://github.com/wentaoyuan/pcn) generatre IntrACompletion dataset from [IntrA](https://github.com/intra3d2019/IntrA).  
