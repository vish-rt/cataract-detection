# Cataract-Detection-and-Classification

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/48744487/119628159-77a2e480-be2a-11eb-8557-eb8186d6fe04.png">
</p>

Our system works on the detection of cataracts and type of classification on the basis of severity namely; mild, normal, and severe, in an attempt to reduce errors of manual detection of cataracts in the early ages.

The phase 1 implementation has successfully classified images as cataract affected or as a normal eye with an accuracy of 96% using combined feature vectors from the SIFT-GLCM algorithm applied to classifier models of SVM, Random Forest, and Logistic Regression. The effect of using SIFT and GLCM separately has also been studied which leads to comparatively lesser accuracies in the model trained. 

The phase 2 implementation which deals with the type classification, has obtained the maximum validation acurracy of 97.66% using deep convolutional neural network models, in particular SqueezeNet, MobileNet, and VGG16.

The results have been made accessible using web and Flask based user interface.

Algorithms used

PHASE 1

1. SIFT 
2. GLCM
3. SVM
4. LOGISTIC REGRESSION
5. RANDOM FOREST
6. KNN

PHASE 2
1. HOUGH CIRCLE TRANSFORM
2. VGG-16
3. MOBILENET V2
4. SQUEEZENET

## Set-up

Move to the frontend folder a.k.a GUI:
```bash
cd GUI
```

Run the project via it's flask framework:
```bash
python app.py
```

In case of any dependency errors:
```bash
pip install
```