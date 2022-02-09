# Sign Language Detection

## Introduction
The objective of this project is to be able to classify hand made sign language gestures into their respective alphabets in realtime and use them as input.

![Sign Language Chart1](/assets/amer_sign2.png)

![Sign Language Chart2](/assets/american_sign_language.PNG)

## Dataset
ASL Alphabet
- Image data set for alphabets in the American Sign Language
- The data set is a collection of images of alphabets from the American Sign Language, separated in 29 folders which represent the various classes.
- The training data set contains 87,000 images which are 200x200 pixels. There are 29 classes, of which 26 are for the letters A-Z and 3 classes for SPACE,DELETE and NOTHING.
- Dataset: [Kaggle](https://www.kaggle.com/grassknoted/asl-alphabet) or [Drive](https://drive.google.com/file/d/1W0IUGuRW6iY3ID5D0ZCxCISS5avVVgnJ/view?usp=sharing)

## Code and Model
The final code, `Sign Language Detection V7.ipynb` can be found in the [code](/code/) directory and final model, `sign_lang_detect_model.h5` can be found in the [models](/models/) directory.

The architecture of the model is given below:

![Model Architeture](/assets/model.png)

## Results
We obtain an image classification accuracy of __98.37%__.

![Results1](/saved_frames/1_L.jpg)
