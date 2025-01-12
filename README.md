# Project Name
> # melanoma_detection_assignment
Implementing a multiclass classification model on Skin cancer dataset using a custom model in Tensorflow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Problem Statement**: To build a CNN-based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, formed from the International Skin Imaging Collaboration (ISIC). The images cover diseases such as Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion.
- All images were sorted and subsets divided evenly, with melanoma and mole images being slightly dominant.

## Conclusions
- **Training Accuracy**: Steadily improved, reaching **55.56%** at epoch 20 and **84.38%** at epoch 30.
- **Validation Accuracy**: Fluctuated but improved to stabilize around **67.74%** at epoch 30.
- **Training Loss**: Decreased consistently from **1.53** to **0.50**, indicating the model's ability to fit training data effectively.
- **Validation Loss**: Varied significantly, ending at **4.19**, suggesting some overfitting.

### Key Observations:
1. **Slight Overfitting**: Training loss decreased steadily while validation loss fluctuated, indicating mild overfitting.
2. **Moderate Generalization Gap**: Training accuracy (84.38%) exceeded validation accuracy (67.74%) by a notable margin.
3. **Signs of Underfitting**: Overall accuracy remains modest, indicating the need for deeper patterns to be learned.
4. **Validation Fluctuations**: Significant variations in validation performance highlight instability in generalization.

## Technologies Used
- TensorFlow - version 2.x
- NumPy - version 1.x
- Matplotlib - version 3.x

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the need for automated melanoma detection to assist dermatologists.

## Contact
Created by [@omkard3] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
