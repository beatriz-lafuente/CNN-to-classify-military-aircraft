# Military-Aircraft
This work identifies military aircrafts on images and classify the identified aircrafts into several aircraft types.

# Introduction

Military aircraft identification in images using deep learning and convolutional neuronal networks (CNN) is a crucial task in modern defense systems. 
With the increasing  number of aircrafts in the sky, the need for efficient and accurate identification methods has become paramount. 
The use of deep learning and CNN has shown to be an effective approach for aircraft identification in images. 

In this project, a method is proposed for military aircraft identification and classification in images using deep learning and CNN. 
These kinds of networks are used to find features in images and recognize patterns between them.

## Data used

[Link to Kaggle dataset of military aircraft.](https://www.kaggle.com/datasets/a2015003713/militaryaircraftdetectiondataset)

The original dataset contains 40 models of military aircraft.
The 40 models will be grouped into 7 classes, these are: 
- Ataque (Attack)
- Bombardeiro (Bomber)
- Busca e salvamento (Search and Rescue)
- Caça (Fighter)
- Caça-Bombardeiro (Fighter-Bomber)
- Reconhecimento (Recognition)
- Transporte (Transport)

<div align="center">
  <img width="800px" src="https://aeroin.net/wp-content/uploads/2021/11/KC-390-FAB-Embraer-1024x683.jpg">
</div>

# What's in this repository?

+ [1_data_preparation](https://github.com/beatriz-lafuente/Military-Aircraft/blob/main/1_data_preparation.ipynb): Normalize the images.
+ [2_plane_detector](https://github.com/beatriz-lafuente/Military-Aircraft/blob/main/2_plane_detector.ipynb): Identify images with military aircrafts.
+ [3_plane_classifier_scratch](https://github.com/beatriz-lafuente/Military-Aircraft/blob/main/3_plane_classifier_scratch.ipynb): CNN made from scratch to classify military aircraft.
+ [4_plane_classifier_TL](https://github.com/beatriz-lafuente/Military-Aircraft/blob/main/4_plane_classifier_TL.ipynb): CNN to classify military aircraft using transfer learning.
+ [5_final](https://github.com/beatriz-lafuente/Military-Aircraft/blob/main/5_final.ipynb): Video that demonstrates the workflow of the project.
