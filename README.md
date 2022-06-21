# Melanoma Detection Assignment
> Build CNN based Model which can evaluate images and classify w.r.t 9 classes and evaluate images and alert the dermatologists about the presence of melanoma .

## Table of Contents
* [Problem statement and Goal](#general-information)
* [Overview of Data Analysis Approach](#technologies-used)
* [Summary of Analysis](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential 
to reduce a lot of manual effort needed in diagnosis.
- Goal : Build a CNN based model which can accurately detect melanoma
- Dataset : CNN_assignment.zip

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1 (Base Model) - Observed Overfitting 
- Model 2 (With Data Augmentation + Dropouts) - Fixed Overfit but observed underfit 
- Model 3 (Fixed Class Imbalance by adding 500 images to each class using Augmentor + BN + 50 epochs (as recommended in notebook) + FC = 256) - 
Class Rebalance helped to increase the Train and Validation accuracy but could be further improved by increasing the parameters of Dense layer to 512 as below. 
- Model 3 (Fixed Class Imbalance by adding 500 images to each class using Augmentor + BN + 50 epochs (as recommended in notebook) + FC = 512) -
has better Train and Validation accuracy


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Google Collab + jupyter Notebook
- python 3.9
- Keras, TensorFlow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Thanks to Upgrad Instructors and Live Sessions


## Contact
Created by [@skmdesai] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
