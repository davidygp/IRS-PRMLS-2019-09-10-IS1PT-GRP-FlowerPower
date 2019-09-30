# SECTION 1 : PROJECT TITLE
FlowerPower
<img width="812" alt="welcome" src="https://user-images.githubusercontent.com/31118924/65893066-ee7ba600-e3d9-11e9-951d-e1dbe93790c9.PNG">

# SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
The team has chosen to work on the problem of differentiating between flowers and non-flowers type images, with the goal of training a model that can classify at a high accuracy on  whether an input image is a flower or non-flower type. In order to better measure the performance of each model, we created a baseline model that was able to get 85% accuracy rate. After evaluating the baseline model we looked at the State-of-the-Art (SOTA) models for similar problem sets (such as CIFAR 10) and attempted to understand and subsequently implement the architectures suggested. We conducted a series of experiments following popular architectures - Deep CNN, VGG, AlexNet, ResNet, Inception V4, Inception-ResNet V2 and SE Inception-ResNet V2. All images (Data_V1 and Data_V2) used were scraped from the Internet, and were subsequently resized and stored in .npz format for different models to load. After rounds of parameter tuning, Deep CNN, VGG and AlexNet were able to reach around 90-92% accuracy using Data_V1. In comparison, ResNet, Inception V4, Inception-ResNet V2 and SE Inception-ResNet V2 reached around 94-95% using Data_V2. In the end, we put all the results together and managed to get a further optimal model using a voting approach.

# SECTION 3 : CREDITS / PROJECT CONTRIBUTION
| Official Full Name | Student ID (MTech Applicable)| Work Items (Who Did What) | Email (Optional) |
| :---: | :---: | :---: | :---: |
| DAI YIRUI | A0195167U | Business idea generation, Image downloading, AlexNet, VGG16, Project report | e0384798@u.nus.edu |
| DONG MEIRONG | A0195346W | Business idea generation, CNN Base Models, Project report | e0384977@u.nus.edu |
| LIM CHONG SENG HERMANN | A0195392U	| Business idea generation, Image downloading, Image resizing, Project report	| e0385023@u.nus.edu |
| YAM GUI PENG DAVID | A0195315A	| Business idea generation, Image Downloading, Image Resizing, ResNet, Inception V4, Inception-ResNet V2, Squeeze Excitation, Project report | e0384946@u.nus.edu |


# SECTION 4 : USER GUIDE
See Pattern Recognition CA2 User Guide

# SECTION 5 : PROJECT REPORT / PAPER
https://github.com/davidygp/IRS-PRMLS-2019-09-10-IS1PT-GRP-FlowerPower/ProjectReport/Report.pdf

Recommended Sections for Project Report / Paper:
- Abstract
- Environment Setup
- Data Set
- Baseline Model
- Approach Towards VGG16 Structure
- Approach Towards AlexNet Structure
- Approach Towards ResNet Structure
- Approach Towards Inception V4 Structure
- Approach Towards Inception-ResNet V2 Structure
- Approach Towards Squeeze Excitation Inception-ResNet V2 Structure
- Combining various Neural Network Architectures
- Conclusion
- References

# SECTION 6 : MISCELLANEOUS
CNN Base Models
- CNN Base Model codes and html save files

intermediary_codes
- Intermediary codes

intermediary_htmls
- Intermediary HTML save files

model_saves
- Saved hdf5 weight files of the best models with their accuracy values

readings
- Some of the readings referenced in the project
