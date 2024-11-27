# HighRes_BurnedArea

## What does this repository record?
> A collection of high-resolution burned area datasets
> Method for burned area segmentation 

## Updating logs
[24-11-25] - Version 0.0.1 Begin data preparation (paper 1-4, dataset 1-2, )
[24-11-27] - add new data

### Papers with public datasets  (from Deepseek)  
- **Paper 1**: Cambrin, D. R., Colomba, L., & Garza, P. (2023). CaBuAr: California burned areas dataset for delineation. IEEE Geoscience and Remote Sensing Magazine, 106-112.
  - [数据获取地点] California  
  - [训练数据] 340 images, 340 samples  
  - [训练数据大小] 未提及  
  - [训练数据来源] 自己勾绘  
  - [数据来源] Sentinel-2  
  - [数据年份] 2015 to 2022  
  - [数据时长] 8年  
  - [数据获取地址] https://huggingface.co/datasets/DarthReca/california_burned_areas  
  - [数据内容] burned area  
 
- **Paper 2**: Gaveau, D. L. A., Descals, A., Salim, M. A., Sheil, D., and Sloan, S. Refined burned-area mapping protocol using Sentinel-2 data increases estimate of 2019 Indonesian burning. Earth System Science Data 13, 5353–5368 (2021).  
  - [数据获取地点] Indonesia  
  - [训练数据] 988 independent training pixels, 317 burned points, 671 unburned points  
  - [训练数据大小] 未提及  
  - [训练数据来源] 自己勾绘  
  - [数据来源] Sentinel-2  
  - [数据年份] 2019  
  - [数据时长] 1年内  
  - [数据获取地址] https://thetreemap.users.earthengine.app/view/burn-area-validation-simplified  
  - [数据内容] burned area  

- **Paper 3**: Colomba, L., Farasin, A., Monaco, S., Greco, S., Garza, P., Apiletti, D., Baralis, E., and Cerquitelli, T. A Dataset for Burned Area Delineation and Severity Estimation from Satellite Imagery. In Proceedings of the 31st ACM International Conference on Information and Knowledge Management (CIKM '22), October 17–21, 2022, Atlanta, GA, USA. ACM, New York, NY, USA, 5 pages. https://doi.org/10.1145/3511808.3557528  
  - [数据获取地点] Europe  
  - [训练数据] 73 satellite images, 957 tiles  
  - [训练数据大小] 未提及  
  - [训练数据来源] Copernicus Emergency Management Service (EMS) annotations  
  - [数据来源] Sentinel-2 L2A and Sentinel-1 GRD missions  
  - [数据年份] 2017 to 2019  
  - [数据时长] 2 months (1 month before and 1 month after the activation date of each wildfire)  
  - [数据获取地址] https://doi.org/10.5281/zenodo.6597139  
  - [数据内容] burned area  

- **Paper 4**: Fodor, G. & Conde, M.V. Rapid Deforestation and Burned Area Detection using Deep Multimodal Learning on Satellite Imagery. H2O.ai, Mountain View, CA (2023).  
  - [数据获取地点] Amazon rainforest, South America  
  - [训练数据] 未提及具体数量  
  - [训练数据大小] 未提及  
  - [训练数据来源] 自己勾绘  
  - [数据来源] Sentinel-1, Sentinel-2, Landsat 5, Landsat 8, VNP09H1, VNP13A1, MCD15A2H, FIRMS, Fire CCI  
  - [数据年份] 2002-2021  
  - [数据时长] 19年内  
  - [数据获取地址] https://github.com/h2oai/cvpr-multiearth-deforestation-segmentation  
  - [数据内容] burned area/active fires  

- **Paper 5** Sdraka, M. et al. FLOGA: A machine learning ready dataset, a benchmark and a novel deep learning model for burnt area mapping with Sentinel-2. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (2024).  
  - [数据获取地点] Greece  
  - [训练数据] 326 events  
  - [训练数据大小] 未提及具体数量  
  - [训练数据来源] Hellenic Fire Service officials  
  - [数据来源] Sentinel-2 and MODIS satellite imagery  
  - [数据年份] 2017-2021  
  - [数据时长] 5 years  
  - [数据获取地址] https://github.com/Orion-AI-Lab/FLOGA  
  - [数据内容] burned area
 
- **Paper 6** Pinto, M.M. et al. A deep learning approach for mapping and dating burned areas using temporal sequences of satellite images. ISPRS Journal of Photogrammetry and Remote Sensing 160, 260–274 (2020).  
  - [数据获取地点] California  
  - [训练数据] 64 images, 2000 sequences  
  - [训练数据大小] 未提及  
  - [训练数据来源] VIIRS Level 1B product, VIIRS Active Fires data, MCD64A1C6  
  - [数据来源] VIIRS  
  - [数据年份] 2012–2018  
  - [数据时长] 6年  
  - [数据获取地址] https://github.com/mnpinto/banet  
  - [数据内容] burned area/active fires




### Public datasets (from Kimi)
- **Dataset 1**: Prabowo, Y. et al. Dataset of Deep Learning from Landsat-8 Satellite Images for Estimating Burned Areas in Indonesia. Mendeley Data, 6 June 2022. DOI: 10.17632/fs7mtkg2wk.5.  
  - [数据获取地点] Indonesia  
  - [训练数据] 227 images  
  - [训练数据大小] 512x512 pixels  
  - [训练数据来源] Landsat-8 satellite images  
  - [数据来源] Landsat-8  
  - [数据年份] 2019 and 2021  
  - [数据时长] 2 years  
  - [数据获取地址] https://data.mendeley.com/datasets/fs7mtkg2wk/5  
  - [数据内容] burned area  


- **Dataset 2**: Al-Dabbagh, A. & Ilyas, M. Deep Learning and Remote Sensing Dataset For Turkey's Wildfire 2021 Multispectral Sentinel-2 Satellite Imagery. Mendeley Data, 12 August 2022. DOI: 10.17632/hgctmx9y6c.1.
  - [数据获取地点] Turkey
  - [训练数据] 25,563 images
  - [训练数据大小] 128x128 pixels
  - [数据来源] Sentinel-2
  - [数据年份] 2021
  - [数据时长] 未提及
  - [数据获取地址] https://data.mendeley.com/datasets/hgctmx9y6c/1
  - [数据内容] burned area


- **Dataset 3** Zhang, Z., He, G., Long, T., & Wei, M. Global 30-m burned area distribution in 2020 (GBA30_2020), Beijing: International Research Center of Big Data for Sustainable Development Goals (CBAS), 2022. doi: 10.12237/casearth.62ff4d13819aec75a535cbea.  
  - [数据获取地点] Global  
  - [训练数据] 504 tiles, each with approximately 40,000 × 40,000 pixels  
  - [训练数据大小] 30m resolution  
  - [训练数据来源] Time series satellite data, machine learning algorithm, and cloud computing platform  
  - [数据来源] Not specified, but generated using time series satellite data  
  - [数据年份] 2020  
  - [数据时长] Single year  
  - [数据获取地址] https://data.casearth.cn/thematic/cbas_2022/162  
  - [数据内容] burned area  
--- 
