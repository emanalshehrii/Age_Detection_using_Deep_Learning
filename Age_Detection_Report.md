# Age Detection Final Report


## Abstract 
Recently, many applications using biometrics to extract information from face images such as age, gender, and emotional state. 
So, in this project we used **UTKFace dataset** to estimate the age from facial features analysis. The main objective of this project is to use deep-learning algorithms in order to estimate the age from facial images.

## Data Description 

- In this project we choose the [UTKFace Dataset](https://www.kaggle.com/jangedoo/utkface-new)
- This dataset contains about **27000** images <br/>
 **The features are:**
- [age] is an integer from 0 to 116, indicating the age
- [gender] is either 0 (male) or 1 (female)
- [race] is an integer from 0 to 4, denoting White, Black, Asian, Indian, and Others (like Hispanic, Latino, Middle Eastern).
- [date&time] is in the format of yyyymmddHHMMSSFFF, showing the date and time an image was collected to UTKFace

## Preprocessing 
The labels of each image is embedded in the file name, formated like [age][gender][race][date&time].jpg. So, we extracted each feature to diffrent arrays to deal with it easly.

## Algorithms

Six models have been applied, which are: **Logistic Regression**, **Simple NN**, **CNN**, and **Transfer learning with VGG16, MobileNetV2 and EfficientNetB0**.

Accordingly, we choose __EfficientNetB0__ because it has the best accuracy score. 

#### Training
__Score__: <br/>

#### Validation
__Score__:  <br/>

#### Testing
__Score__:  <br/>

## Tools
Here the basic tools we used in our project: <br/>
Technologies: python, and Jupyter Notebook with python libraries:

- pandas
- matplotlib
- numpy
- seaborn
- scikit-learn
- ploty
- keras
- tensorflow
- cv2

## Conclusion 
We aim to improve age estimation to be more accurate by building more models with different hyperparameters, that is doing by using Neural Network as a part of deep learning.
