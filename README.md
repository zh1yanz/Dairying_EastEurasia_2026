# Dairying_EastEurasia_2026
This repository documents the data and scripts for metaproteomic analysis in the paper by Zhang et al.

## Dairying Shaped Dietary Boundaries in Ancient East Eurasia
### Original publication

### Authors
Zhiyan Zhang, Yueguang Yang, Dexin Cong, Minghui Wang, Lipeng Lu, Qiurong Ruan, Jie Zhang, Alipujiang Niyazi, Jianjun Yu, Wenying Li, Xingjun Hu, Yongqiang Wang, Guoke Chen, Yishi Yang,  Shuicheng Li, Jianing He, Ruilin Mao, Qiang Ma, Xiaoli Qin, Qian Han, Xuesong Pei, Jing Shao, Zhouyong Sun, Ruitong Yao, Yan Pan, YiHsien Lin, Yao Zhang, Christina Warinner*, Chao Ning*, Xiaohong Wu*
*Corresponding authors: wuxh@pku.edu.cn (X.H.W.); cning@pku.edu.cn (C.N.); warinner@fas.harvard.edu (C.W.).

### Abstract
The emergence of pastoralism profoundly transformed ancient societies across East Eurasia1-3. Yet it remains unclear to what extent early lactase non-persistent (LNP) East Asian communities adopted dairying, and how milk consumption intersected with biological and cultural factors. Here, we analyzed dietary and microbial proteins preserved in the dental calculus of 123 individuals (ca. 2500 BCE to 200 CE) spanning 24 archaeological sites along the proto-Silk Road, a pivotal conduit for early pastoral exchange4. Our results reveal an association between dairying and pastoral economies, but not with agriculture, despite this being typical in West Eurasia5. Ruminant milk was routinely consumed in the Inner Asian Mountain Corridor and Hexi Corridor, but was limited or absent among contemporaneous agrarian communities on the Loess Plateau, who maintained a persistent "non-milking attitude"6 since the first introduction of pastoralism. Comparative metaproteomics demonstrates that milk consumers displayed elevated levels of oral microbial proteins involved in lactose and galactose metabolism, suggesting a functional adaptation of the microbiome to dairy intake. We propose that while milk use among LNP pastoralists may have been facilitated by microbial plasticity in the gastrointestinal tract7-10, persistent milk avoidance among agrarian communities is more plausibly explained by cultural factors than biological constraints. This divergence established enduring dietary boundaries between herding and farming communities, revealing how cultural choice and microbial flexibility have jointly shaped dietary adaptations in East Eurasia. 

### Raw LC-MS/MS data repository
The mass spectrometry data and the MaxQuant and MSFragger protein output files are deposited in the ProteomeXchange Consortium (https://proteomecentral.proteomexchange.org) via the iProX partner repository with the dataset identifier PXD065252.

## Repository files
### * metadata: 
Input data for analysis derived directly from MaxQuant LFQ results.
### * Script: 
R and Python scripts coded under R version 4.4.2 and Python 3.7.0.
### * Database and raw outputs: 
Reference oral microbiota proteome database (HOMD retrieved Sep 2022 and reduced database) and raw outputs from MaxQuant and MSFragger.

### Libraries
#### R Packages

| Package | Version |
| :--- | :--- |
| `dplyr` | 1.2.0 |
| `ggplot2` | 4.0.2 |
| `ggrepel` | 0.9.6 |
| `grid` | 4.4.2 |
| `imputeLCMD` | 2.1 |
| `limma` | 3.62.2 |
| `patchwork` | 1.3.2 |
| `readr` | 2.1.5 |
| `readxl` | 1.4.3 |
| `scales` | 1.4.0 |
| `stringr` | 1.5.1 |
| `tibble` | 3.3.0 |
| `tidyr` | 1.3.1 |
| `vegan` | 2.6.8 |

#### Python Packages

| Package | Version |
| :--- | :--- |
| `matplotlib` | 3.1.0 |
| `numpy` | 1.21.6 |
| `pandas` | 1.1.5 |
| `scipy` | 1.7.3 |
| `seaborn` | 0.11.2 |
| `statsmodels` | 0.13.5 |

## Licence 

## Contact
For questions about the code, contact zhiyan_zhang@stu.pku.edu.cn.
