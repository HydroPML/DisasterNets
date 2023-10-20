# DisasterNets
# Overview of the proposed DisasterNets
![image](https://github.com/HydroPML/DisasterNets/blob/main/Figures/fig1.png)
# Applications: earthquake-triggered landslide mapping using DisasterNets
![image](https://github.com/HydroPML/DisasterNets/blob/main/Figures/fig2.png)
# Details
| Categories  | Descriptions | Methods |
| ------------- | ------------- | ------------- |
| Supervised Learning | The corresponding labeled disaster training samples are available in the study area  | [MFFENet](https://link.springer.com/article/10.1007/s10346-022-01847-1?awc=26429_1686916238_e947d0c7807a9c3dd12b0a292dd2461c&utm_medium=affiliate&utm_source=awin&utm_campaign=CONR_BOOKS_ECOM_DE_PHS) |
| Semi-supervised Learning  | Few  labeled disaster training samples are available in the study area | [SSCDNet](https://www.mdpi.com/2072-4292/14/11/2641), [FixMatch](https://github.com/google-research/fixmatch)  |
| Unsupervised Change Detection  |  There are no corresponding labeled samples in the research area, but there are pre-disaster remote sensing images | [UCDFormer](https://ieeexplore.ieee.org/abstract/document/10144178), [DCVA](https://github.com/sudipansaha/dcvaVHROptical)  |
| Unsupervised Domain Adaptation with Source Data | Domain adaptation with source data module problem by leveraging the adversarial learning behaviors of GANs to perform distribution alignment in the pixel, feature, and output spaces | [ADANet](https://link.springer.com/article/10.1007/s10346-022-01847-1?awc=26429_1686916238_e947d0c7807a9c3dd12b0a292dd2461c&utm_medium=affiliate&utm_source=awin&utm_campaign=CONR_BOOKS_ECOM_DE_PHS), [CaGAN](https://ieeexplore.ieee.org/abstract/document/9262039)  |
| Unsupervised Domain Adaptation without Source Data  | Domain adaptation without source data problem by generating a reliable synthetic source domain | [SGD-MA](https://ieeexplore.ieee.org/abstract/document/10043671)|
# Implementation on Google Earth Engine

# Reference
Xu Q, Shi Y, Zhu X X. DisasterNets: Embedding Machine Learning in Disaster Mapping[J]. arXiv preprint arXiv:2306.09815, 2023.
