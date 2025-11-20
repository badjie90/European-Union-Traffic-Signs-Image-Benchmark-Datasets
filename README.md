# Description-of-European-Union-Traffic-Sign-Recognition-Benchmark-Datasets

This repository contains Traffic Sign Recognition and detection image datasets, which are a multi-class image classification benchmark in the domain of advanced driver assistance systems and autonomous driving. However, it would be a privilege if you wanted to add to this README file if you know of any European Union country or countries that use a different traffic sign and its related statistics. Contact me at bbadjie@fc.ul.pt.


Road signs, usually referred to as traffic signs, are posted along the sides of roadways to advise road users of important information about the driving environment. In order to promote international travel where language limitations might cause hurdles and, generally, to lessen the dangers of driving, countries are increasingly adopting pictorial signs or other ways to harmonize and streamline traffic signals. Such graphic signs, which often follow international standards, substitute symbols for words. These signs were first created in Europe and have subsequently been adopted, in varying degrees, by the majority of countries worldwide. However, in the context of autonomous driving, it aids the machine learning algorithm in making autonomous driving decisions in order to enable the vehicle to navigate safely without the possibility of causing fatal accidents while driving.


## 1. Description of the German Traffic Sign Recognition Benchmark (GTSRB) Dataset
GTSRB is a dataset containing images of German traffic signs and can be used to train deep learning image classification models for autonomous vehicles. It is the common traffic sign used across the member states of the European Union except for few member states.The dataset comprises 12,630 test images and 39,209 training images from 43 classes of traffic signs (speed limit, crossing, stop, traffic signals, etc.). The number of datapoints in each class varies, resulting in some classes having a small number of images while others have a huge number, as seen in the graph and in Table 1 below. With a file size of around 314.36 MB, downloading the dataset does not require a lot of time or memory space. It has two distinct folders: train and test. The train folder is divided into sub-folders, each representing a particular class, and each class has a variety of traffic sign images. It was first published at IJCNN 2011 [link](https://ieeexplore.ieee.org/abstract/document/6033395). 


GTSRB database link https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html

### A visual representation of the number of classes in the GTSRB dataset and their corresponding datapoints.
![GTSRB](https://user-images.githubusercontent.com/73148658/200136910-d7304c73-7df3-4126-bebc-19c0586605a8.png)

The graphical representation of this dataset shows that each class has an uneven distribution of images. Approximately 2500 images are used in certain classes, whereas just 250 images are used in others. Because of this, it might be best to use data augmentation when using this dataset to train a deep learning model to avoid making a model that is biased. 

| Dataset | No. of classes |            Class Names             |  Dimension  | Language    |                       Cited                   | Year   |
| ------- | -------------- | ---------------------------------- | ------------| ----------- |-----------------------------------------------|--------| 
|         |                |                                    |             |             |                                               |        |
|  GTSRB [Dataset](https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html)  |       43       |   0:  Speed limit (20km/h)         |  32x32x3    | English     |[Detection of traffic signs in real-world images: The German traffic sign detection benchmark](https://ieeexplore.ieee.org/abstract/document/6706807)                                                    |  2013  |
|         |                |   1:  Speed limit (30km/h)         |  32x32x3    |             |  [Man vs. computer: Benchmarking machine learning algorithms for traffic sign recognition](https://www.sciencedirect.com/science/article/pii/S0893608012000457)                               |   2012 |
|         |                |   2:  Speed limit (50km/h)         |  32x32x3    |             | [Traffic sign recognition with multi-scale Convolutional Networks](https://ieeexplore.ieee.org/abstract/document/6033589)                                                                            |  2011  | 
|         |                |   3:  Speed limit (60km/h)         |  32x32x3    |             | [Vision-Based Traffic Sign Detection and Analysis for Intelligent Driver Assistance Systems: Perspectives and Survey](https://ieeexplore.ieee.org/abstract/document/6335478)                      |  2016  | 
|         |                |   5:  Speed limit (80km/h)         |  32x32x3    |             | [Traffic-Sign Detection and Classification in the Wild](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Zhu_Traffic-Sign_Detection_and_CVPR_2016_paper.pdf)                      | 2012   | 
|         |                |   6:  End of speed limit (80km/h)  |  32x32x3    |             | [Real-Time Detection and Recognition of Road Traffic Signs](https://ieeexplore.ieee.org/abstract/document/6287592)                                                                                     |  2015  |  
|         |                |   7:  Speed limit (100km/h)        |  32x32x3    |             | [Towards Real-Time Traffic Sign Detection and Classification](https://ieeexplore.ieee.org/abstract/document/7296660)                                                                      |   2014 | 
|         |                |   8:  Speed limit (120km/h)        |  32x32x3    |             | [Real-time traffic sign recognition in three stages](https://www.sciencedirect.com/science/article/pii/S0921889012001236)                                                                       | 2018   |                                      
|         |                |   9:  No passing                   |  32x32x3    |             |[Traffic Sign Recognition Using a Multi-Task Convolutional Neural Network](https://ieeexplore.ieee.org/abstract/document/7959631)                                                                      | 2018   |                                             
|         |                |   10: No passing veh over 3.5 tons |  32x32x3    |             | [Traffic sign detection and recognition based on random forests](https://www.sciencedirect.com/science/article/pii/S1568494616000028)                                                               | 2016   |
|         |                |   11: Right-of-way at intersection |  32x32x3    |             | [Lightweight deep network for traffic sign classification](https://link.springer.com/article/10.1007/s12243-019-00731-9)                                                                              | 2020   |
|         |                |   12: Priority road                |  32x32x3    |             | [Traffic Sign Recognition via Multi-Modal Tree-Structure Embedded Multi-Task Learning](https://ieeexplore.ieee.org/abstract/document/7551141)                                                        | 2017   |
|         |                |   13: Yield                        |   32x32x3
|         |                |   14: Stop                         |   32x32x3
|         |                |   15: No vehicles                  |   32x32x3
|         |                |   16: Veh > 3.5 tons prohibited    |   32x32x3
|         |                |   17: No entry                     |   32x32x3
|         |                |   18: General caution              |   32x32x3
|         |                |   19: Dangerous curve left         |   32x32x3
|         |                |   20: Dangerous curve right        |   32x32x3
|         |                |   21: Double curve                 |   32x32x3
|         |                |   22: Bumpy road                   |   32x32x3
|         |                |   23: Slippery road                |   32x32x3 
|         |                |   24: Road narrows on the right    |   32x32x3
|         |                |   25: Road work                    |   32x32x3
|         |                |   26: Traffic signals              |   32x32x3
|         |                |   27: Pedestrians                  |   32x32x3
|         |                |   28: Children crossing            |   32x32x3
|         |                |   29: Bicycles crossing            |   32x32x3
|         |                |   30: Beware of ice/snow           |   32x32x3
|         |                |   31: Wild animals crossing        |   32x32x3
|         |                |   32: End speed + passing limits   |   32x32x3
|         |                |   33: Turn right ahead             |   32x32x3
|         |                |   34: Turn left ahead              |   32x32x3
|         |                |   35: Ahead only                   |   32x32x3
|         |                |   36: Go straight or right         |   32x32x3
|         |                |   37: Go straight or left          |   32x32x3
|         |                |   38: Keep right                   |   32x32x3
|         |                |   39: Keep left                    |   32x32x3
|         |                |   40: Roundabout mandatory         |   32x32x3
|         |                |   41: End of no passing            |   32x32x3
|         |                |   42: End no passing veh > 3.5 tons|   32x32x3



## 2. Belgium Traffic Sign Classification (BTSC) Dataset

One of the EU nations with distinctive traffic signs from the other EU nations is Belgium. For the classification of traffic signs, the BTSC dataset was created to help both human drivers and autonomous driving. This dataset is composed of a training and test set containing 4591 and 2534 traffic sign images, respectively, with 62 distinct classes of traffic signs. The splitting of the  BTSC dataset comes after the breakup with Belgium-TS. For each physically separate traffic sign, there are often three images or annotations. This dataset was originally collected and designed by GeoAutomation, which records the data in urban settings in the Flanders area of Belgium. The sizes of the BTSC training and testing sets are 171.3 MB and 76.5 MB, respectively. In the context of self-driving vehicles, this dataset was created to develop models for improved driver support systems and autonomous driving. However, this dataset has the issue of signs with identical meanings. We therefore highly advise using exploratory data analysis approaches to find the identical traffic signs and eliminate them from the dataset. The classes in the dataset have a varying amount of datapoints; for instance, some classes have 200 images or less, while others have more than 350 images. As a result, to avoid the model's predictions being biased while using this dataset to train it, we advise using data augmentation.
 
 
 

BTSC Database Link https://btsd.ethz.ch/shareddata/

| Dataset | No. of classes |            Class Names                                   | Dimension| Language|                      Cited        | Year   |
| ------- | -------------- | ---------------------------------------------------------| ---------|---------|-----------------------------------|--------| 
|  BTSC [Dataset](https://btsd.ethz.ch/shareddata/)   |       62       |0 : Warning for a bad road surface                        | 59x89x3  | English |[Multi-view traffic sign detection, recognition, and 3D localisation](https://link.springer.com/article/10.1007/s00138-011-0391-3)                                                 | 2014   |
|         |                |1 : Warning for a speed bump                              | 59x89x3  |         |[Traffic Sign Recognition – How far are we from the solution?](https://people.ee.ethz.ch/~timofter/publications/Mathias-IJCNN-2013.pdf)                                                   | 2013   |
|         |                |2 : Warning for a slippery road surface                   |  59x89x3 |         |[Multi-view traffic sign detection, recognition, and 3D localisation](https://people.ee.ethz.ch/~timofter/traffic_signs/Timofte-WACV-2009.pdf)                                     | 2009   |
|         |                |3 : Warning for a curve to the left                       | 59x89x3  |         |[Combining Traffic Sign Detection with 3D Tracking Towards Better Driver Assistance](https://people.ee.ethz.ch/~timofter/publications/Timofte-BOOK-2011-preprint.pdf)                    | 2011   |
|         |                |4 : Warning for a curve to the right                      | 59x89x3  |         |[Integrating Object Detection with 3D Tracking Towards a Better Driver Assistance System](https://people.ee.ethz.ch/~timofter/traffic_signs/Prisacariu-ICPR-2010.pdf)                | 2010   |
|         |                |5 : Warning for a double curve, first left then right     | 59x89x3  |         |[Performance of Different Optimizers for Traffic Sign Classification](https://ieeexplore.ieee.org/abstract/document/8944578)                                                            | 2019   |            
|         |                |6 : Warning for a double curve, first left then right     | 59x89x3  |         |[Robust Traffic Signs Classification using Deep Convolutional Neural Network](https://ieeexplore.ieee.org/abstract/document/9806122)                                                      | 2022   |
|         |                |7 : Watch out for children ahead                          | 59x89x3  |         |[A Traffic Sign Recognition Model with Only 140 KB](https://dl.acm.org/doi/abs/10.1145/3366715.3366723)                                                                                    | 2019   |
|         |                |8 : Watch out for  cyclists                               |59x89x3   |         |[Real-Time Traffic Sign Detection and Recognition Using GPU](https://ieee-hpec.org/2014/CD/index_htm_files/FinalPapers/109.pdf)                                                      | 2014   |
|         |                |9 : Watch out for cattle on the road                      | 59x89x3  |         |[A pipeline architecture for traffic sign classification on an FPGA](https://ieeexplore.ieee.org/abstract/document/7168792)                                                              | 2015   |
|         |                |10: Watch out for roadwork ahead                          | 59x89x3 
|         |                |11: Traffic light ahead                                   | 59x89x3 
|         |                |12: Watch out for railroad crossing with barriers ahead   | 59x89x3 
|         |                |13: Watch out ahead for unknown danger                    | 59x89x3 
|         |                |14: Warning for a road narrowing                          | 59x89x3 
|         |                |15: Warning for a road narrowing on the left              | 59x89x3 
|         |                |16: Warning for a road narrowing on the right             | 59x89x3 
|         |                |17: Warning for side road on the right                    | 59x89x3 
|         |                |18: Warning for an uncontrolled crossroad                 | 59x89x3 
|         |                |19: Give way to all drivers                               | 59x89x3 
|         |                |20: Road narrowing, give way to oncoming drivers          | 59x89x3 
|         |                |21: Stop and give way to all drivers                      | 59x89x3 
|         |                |22: Entry prohibited (road with one-way traffic)          | 59x89x3 
|         |                |23: Cyclists prohibited                                   | 59x89x3 
|         |                |24: Vehicles heavier than indicated prohibited            | 59x89x3 
|         |                |25: Trucks prohibited                                     | 59x89x3 
|         |                |26: Vehicles wider than indicated prohibited              | 59x89x3 
|         |                |27: Vehicles higher than indicated prohibited             | 59x89x3 
|         |                |28: Entry prohibited                                      | 59x89x3  
|         |                |29: Turning left prohibited                               | 59x89x3   
|         |                |30: Turning right prohibited                              | 59x89x3 
|         |                |31: Overtaking prohibited                                 | 59x89x3 
|         |                |32: Driving faster than indicated prohibited (speed limit)| 59x89x3 
|         |                |33: Mandatory shared path for pedestrians and cyclists    | 59x89x3 
|         |                |34: Driving straight ahead mandatory                      | 59x89x3 
|         |                |35: Mandatory left                                        | 59x89x3 
|         |                |36: Driving straight ahead or turning right mandatory     | 59x89x3 
|         |                |37: Mandatory direction of the roundabout                 | 59x89x3 
|         |                |38: Mandatory path for cyclists                           | 59x89x3 
|         |                |39: Mandatory divided path for pedestrians and cyclists   | 59x89x3 
|         |                |40: Parking prohibited                                    | 59x89x3 
|         |                |41: Parking and stopping prohibited                       | 59x89x3 
|         |                |42: Sppe limit                                            | 59x89x3 
|         |                |43: Stop                                                  | 59x89x3 
|         |                |44: Road narrowing, oncoming drivers have to give way     | 59x89x3 
|         |                |45: Parking is allowed                                    | 59x89x3 
|         |                |46: parking for handicapped                               | 59x89x3 
|         |                |47: Parking for motor cars                                | 59x89x3 
|         |                |48: Parking for goods vehicles                            | 59x89x3 
|         |                |49: Parking for buses                                     | 59x89x3 
|         |                |50: Parking only allowed on the sidewalk                  | 59x89x3 
|         |                |51: Begin of a residential area                           | 59x89x3 
|         |                |52: End of the residential area                           | 59x89x3 
|         |                |53: Road with one-way traffic                             | 59x89x3 
|         |                |54: Dead end street                                       | 59x89x3 
|         |                |55: Ben-curve                                             | 59x89x3 
|         |                |56: Crossing for pedestrians                              | 59x89x3 
|         |                |57: Crossing for cyclists                                 | 59x89x3 
|         |                |58: Parking exit                                          | 59x89x3 
|         |                |59: Information Sign : Speed bump                         | 59x89x3 
|         |                |60: End of the priority road                              | 59x89x3 
|         |                |61: Begin of a priority road                              | 59x89x3 
  
  
  
## Indian Traffic Sign Benchmark (ITSB) Dataset
We consider it vital to provide this dataset in this README file even though it is beyond the scope of our PhD thesis's data for developing a reliable deep learning image classification model for autonomous vehicles. This will allow us to validate the robustness of our suggested model. ITSB is a multi-class image dataset containing 85 classes. There are in all 7210 images of traffic signs, 4,438 of which are in the training set and 2,772 in the test set.

ITSB Database Link https://www.kaggle.com/datasets/sarangdilipjodh/indian-traffic-signs-prediction85-classes/download?datasetVersionNumber=1
  

| Dataset | No. of classes |    Dimension        |      Language        |          Cited                |                            Year  |
| ------- | -------------- | --------------------|----------------------|-------------------------------|----------------------------------| 
| ITSB [Dataset](https://www.kaggle.com/datasets/sarangdilipjodh/indian-traffic-signs-prediction85-classes/download?datasetVersionNumber=1)    |    85          |     1920x1080x3     |     English          |[Detection and Recognition of Traffic Signs based on RGB to RED Conversion](https://ieeexplore.ieee.org/abstract/document/8282728)                                                                           |   2017 |
|         |                |                     |                      |[INDIAN TRAFFIC SIGN BOARD RECOGNITION AND DRIVER ALERT SYSTEM USING CNN](https://ieeexplore.ieee.org/abstract/document/9315260)                                                                           | 2020   |
|         |                |                     |                      |[Indian traffic sign detection and recognition](https://link.springer.com/article/10.1007/s13177-019-00178-1)                                                                    | 2020   |
|         |                |                     |                      |[Indian traffic sign detection and recognition using deep learning](https://www.sciencedirect.com/science/article/pii/S2046043022000557)                                                             | 2022   |
|         |                |                     |                      |[VISION  BASED  ADVANCED  DRIVER  ASSISTANCE  SYSTEM  USING  DEEPLEARNING](https://ieeexplore.ieee.org/abstract/document/8944842)                                                                           | 2019   |
|         |                |                     |                      |


