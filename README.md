# SECTION 1 : PROJECT TITLE
FlowerPower


# SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT

...

# SECTION 3 : CREDITS / PROJECT CONTRIBUTION
| Official Full Name | Student ID (MTech Applicable)| Work Items (Who Did What) | Email (Optional) |
| :---: | :---: | :---: | :---: |
| DAI YIRUI | A0195167U | Business idea generation, Image downloading, AlexNet, VGG16, Project report | e0384798@u.nus.edu |
| DONG MEIRONG | A0195346W | Business idea generation, CNN Base Models, Project report | e0384977@u.nus.edu |
| LIM CHONG SENG HERMANN | A0195392U	| Business idea generation, Image downloading, Image resizing, Project report	| e0385023@u.nus.edu |
| YAM GUI PENG DAVID | A0195315A	| Business idea generation, Image Downloading, Image Resizing, ResNet, Inception V4, Inception-ResNet V2, Squeeze Excitation, Project report | e0384946@u.nus.edu |


# SECTION 4 : USER GUIDE
[ 1 ] To run using Jupyter Notebook with tensorflow-gpu

$ git clone https://github.com/davidygp/IRS-PRMLS-2019-09-10-IS1PT-GRP-FlowerPower

  (Ensure Anaconda is installed)
  
$ conda create --name tf-gpu

$ conda activate tf-gpu

(tf-gpu) $ conda install -c aaronzs tensorflow-gpu

(tf-gpu) $ conda install -c anaconda cudatoolkit==9.0

(tf-gpu) $ conda install -c anaconda cudnn==7.1.4

(tf-gpu) $ cd ./IRS-PRMLS-2019-09-10-IS1PT-GRP-FlowerPower/

(tf-gpu) $ jupyter notebook

(open up Download-ImageNet.ipynb - To re-download the iamges)

(open up Reshape_Resize_Images.ipynb - To re-size the images)

To re-create train/test set Input: resized images in .npz format, Output=train/test split in .npz format
(open up Create_Train_Test_Set.ipynb)
  
(open up Image_Classification_Neural_Network_Final.ipynb - To run Neural Network models)

# SECTION 5 : PROJECT REPORT / PAPER
https://github.com/davidygp/IRS-PRUPR-2019-06-22-IS1PT-GRP-CyberSecurity-NSL-KDD/ProjectReport/Report.pdf

Recommended Sections for Project Report / Paper:
- Executive Summary
- Introduction into Dataset
- Description of Dataset
- Data Processing
- Results
- Limitations of datasets 
- Conclusion
- Appendix

# SECTION 6 : MISCELLANEOUS
Attack Types.csv
- The Attack Types and the corresponding Attack Category

Field Names.csv
- The Field Names and the corresponding Data Type (continuous/ symbolic)

KDDTrain+.txt
- The NSL-KDD Train Dataset

KDDTest+.txt
- The NSL-KDD Test Dataset

NSL-KDD-Multiclass_Classification.html/NSL-KDD-Multiple_Binaryclass_Classification.html
- HTML saved files of the jupyter notebook outputs

Cyber Dataset.csv/Cyber Dataset.hdf5
- Artifacts of the NN Training Model
