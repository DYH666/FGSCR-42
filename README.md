# FGSCR-42
A public Dataset for Fine-Grained Ship Classification in Remote sensing images

# Dataset
Our Dataset are downloadable at https://pan.baidu.com/s/1Bke-qT88vcf7sjvUgGRTZg  password:il7v

# Features
We collect remote sensing images from Google Earth , and popular remote sensing imaged atasets like DOTA , HRSC2016, NWPUVHR-10, etc. containing warships and civilian ships of various scales. The whole dataset contains about 9,320 images which are divided into 42 categories(FGSCR-42).
![image](https://github.com/DYH666/FGSCR-42/blob/master/shipdemo.png)
![image](https://github.com/DYH666/FGSCR-42/blob/master/categories.eps)

# Evaluations
We first evaluated common image classification networks to perform simple test on FGSCR-42. For the comprehensiveness of the results, we eventually select VGG, ResNet, ResNext, DenseNet, as our testing algorithms for verifying the validity of FGSCR-42. Second, in order to apply FGSCR-42 to fine-grained ship classification task in remote sensing images, we selected 4 popular fine-grained recognition algorithms, namely B-CNN, RA-CNN, DCL, TASN, for verification, that the results are also very promising.
![image](https://github.com/DYH666/FGSCR-42/blob/master/results.png)

# Acknowledgment
This work was supported in part by the National Natural Science Foundation of China, the National Key Research and Development Program of China, and the Fundamental Research Funds for the Central Universities.
