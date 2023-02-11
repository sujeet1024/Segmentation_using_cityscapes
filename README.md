# Segmentation_using_cityscapes



This reposiratory contains codes for both the networks: SegFast and the U-net used for the project, and training data (`CityScapes`) can be downloaded from [kaggle](https://www.kaggle.com/datasets/dansbecker/cityscapes-image-pairs) or [the official dataset website](https://www.cityscapes-dataset.com/)
  The data from both websites needs to be processed differently

### The `coptfk.ipynb` file
  - This file contains the SegFast architecture trained through the cityscapes data using tensorflow
  - The dataset downloaded from kaggle is preprocessed here
  
example of results:

![image](https://user-images.githubusercontent.com/79794208/215322345-dda0bd73-4908-4157-85ec-17d979884acc.png)


### The `torch2unet.ipynb` file
  - This file contains the U-net architecture used, built with pytorch
  - This architecture uses the dataset from the official website and is preprocessed within the file (low resolution images were used to satisfy the GPU compute)
  - You can implement the architecture and relevant code by installing the modules required
  
  
segmented example:

![image](https://user-images.githubusercontent.com/79794208/218240966-24e98c0e-af66-4154-a154-65f8277c8288.png)
