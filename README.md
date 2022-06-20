# SiamFly - A Novel Pre-Trained Architecture for Large-Scale Fine-Grained Butterfly Classification

Paper accepted for Poster Presentation at **CVPR2022 - CV4Animals Workshop** (20 June 2022) https://www.cv4animals.com/

Our preprint submitted for IJCV Journal can be accessed here https://github.com/Theivaprakasham/siamfly/blob/main/preprint/SiamFly-preprint.pdf
Our poster presented at CVPR 2022 here https://github.com/Theivaprakasham/siamfly/blob/main/CVPR_poster/CVPR22_final_poster_Siamfly.pdf

# Authors

Hari Theivaprakasham (cb.en.p2cen20026@cb.students.amrita.edu), V Sowmya (v_sowmya@cb.amrita.edu), Vinayakumar Ravi (vravi@pmu.edu.sa), EA Gopalakrishnan (ea_gopalakrishnan@cb.amrita.edu) and KP Soman (kp_soman@amrita.edu).

1. Center for Computational Engineering and Networking (CEN), Amrita School of Engineering, Amrita Vishwa Vidyapeetham, Coimbatore, India.
2. Center for Artificial Intelligence, Prince Mohammad Bin Fahd University, Khobar, Saudi Arabia.

# Abstract

Butterfly classification is a fine-grained classification problem due to highly complex features and variability between inter-species and intra-species levels. In this study, we introduce a large-scale, research-grade, fine-grained butterfly image dataset comprising 62,287 images corresponding to 686 butterfly species. We also propose SiamFly - a novel pre-trained architecture to facilitate the deep learning model to extract more relevant features pertinent to the butterfly dataset. The experimental results show that the proposed method can achieve better performance on a low-data regime and also surpasses the ImageNet-based transfer-learning performance by a larger margin. We validate our findings by achieving 88.2% top-1 accuracy on the dataset with ConvNeXt model when trained on our proposed approach.


# Dataset:

We propose a new large-scale, fine-grained, research-grade butterfly image dataset with 1,27,724 butterfly images belonging to 686 species of butterflies from India. Most of the images were collected from internet sources (Google Images, Bing and Flickr), few of the images were collected from the iNaturalist GBIF dataset filtered over the Indian sub-continent, and the rest of the images were contributed by the first author.


# Proposed Architecture

**SiamFly**

![image](https://user-images.githubusercontent.com/44334254/174580122-5c3ecc22-06bc-4279-b44f-4cd17a57b506.png)


# Demo

Gradio Demo of SiamFly based model training: https://huggingface.co/spaces/Theivaprakasham/indianbutterflyidentification


# Training Codes

Will be released soon. Keep following us!