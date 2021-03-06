# sanjeevani
Imaginea 2020 Inifnity Idea

Medical image processing and modeling:
- Segmentation
- Regression
- Classification
- Generation/Reconstruction
- Representation learning

# Open Source Libraries
- https://niftynet.io/
- https://itk.org/
- https://vtk.org/
- https://www.kaggle.com/schlerp/getting-to-know-dicom-and-the-data/data
# [Papers](papers)

# Format
- Dicom
 - https://www.kaggle.com/schlerp/getting-to-know-dicom-and-the-data/data
- Nii
 - http://paulbourke.net/dataformats/nii/
 
# Datasets

- **Realated to Lung**
  * http://networkrepository.com/lung-cancer.php
  * https://archive.ics.uci.edu/ml/datasets/Lung+Cancer
  * https://lndb.grand-challenge.org/Home/
    - https://kits19.grand-challenge.org/data/
    - https://arxiv.org/pdf/1904.00445.pdf
  * http://biogps.org/dataset/tag/lung%20cancer/
  * https://www.cancerimagingarchive.net/ Needs to raise request for the dataset with a reason
    - https://wiki.cancerimagingarchive.net/display/Public/TCGA-LUAD 20GB
    - https://wiki.cancerimagingarchive.net/display/Public/ACRIN-FLT-Breast 70GB
  
- **Breast Cancer**
 - https://wiki.cancerimagingarchive.net/display/Public/The+VICTRE+Trial%3A+Open-Source%2C+In-Silico+Clinical+Trial+For+Evaluating+Digital+Breast+Tomosynthesis 1TB
   - [Download utils](https://wiki.cancerimagingarchive.net/display/NBIA/Downloading+TCIA+Images)
   - https://github.com/DIDSR/VICTRE
   - https://github.com/DIDSR/VICTRE_DM_ROIs
 
 - **Eye**
   - https://www.kaggle.com/paultimothymooney/kermany2018 5GB JPEG image classification 
   - https://www.kaggle.com/benjaminwarner/resized-2015-2019-blindness-detection-images 17GB image classification **Base dataset**
  
 - **Chest**
   - https://www.kaggle.com/c/rsna-pneumonia-detection-challenge 4GB Dicom **possible 2nd dataset**

# Deep Learning

- Covulutional Network References
  - http://cs231n.stanford.edu/
  - http://cs231n.github.io/
  
- UNet
  - https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47
  - https://heartbeat.fritz.ai/deep-learning-for-image-segmentation-u-net-architecture-ff17f6e4c1cf
  
# Papers
- Image PRocessing Pipelines:
- [Nifty Pipeline](https://www.sciencedirect.com/science/article/pii/S0169260717311823) [PDF](papers/ScienceDirect_articles_26Dec2019_16-47-45.687/NiftyNet--a-deep-learning-platform-for-_2018_Computer-Methods-and-Programs-i.pdf)
  - https://niftynet.io/
  
- UNet
  - https://arxiv.org/abs/1505.04597
  - https://github.com/zhixuhao/unet
  
  
# Pipeline Components
- Data loading 
  - Load 3D images from different image formats
  - Anistropic voxels and special spatial information and patient information
- Data prepration as test/test/validation
- Image data loading and sampling
- Data augmentation
- DL Model Architecture
- DL framewok
- Metrics to evaluate
- Prediction

- https://towardsdatascience.com/object-oriented-machine-learning-pipeline-with-mlflow-for-pandas-and-koalas-dataframes-ef8517d39a12


# Our choice of Tools
- AWS
  - S3
  - EMR
- Apache Spark
- MLFLOW
  - https://github.com/mlflow/mlflow/tree/master/examples/flower_classifier
- Tensorflow
- Kubernets (?)
