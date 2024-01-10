# Project Name
> MelanomaDetection case study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Built a CNN based model which can accurately detect melanoma. 
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
- The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The accuracy of test set is around 90%
- Accuracy of validation dats set is around 87%
- We may run extra epochs to see if the model performs better. But, in such case there could be a problem of overfitting as well.
- The model with the above accuracy shows an increased performace of the model when we train with dataset where number of images in each class is balanced.
- We can see that the model performed better on augmented data. 
- Even there is no much significant difference in training loss and validation loss as well and they tend to follow same trend.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.9.7

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was done as part of Machine Learning module in ML and AI program conducted by IIITB and upgrad. I thank all the mentors, coworked and faculty at UpGrad and IIIT Banglore for their continuous guidance throughtout this course.

## Contact
Created by [@panderuchika] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
