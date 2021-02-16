FACE MASK DETECTION USING PYTHON. 

AIM:
Face Mask Detection using Python involves the usage of the Haar
cascade, cascade classifiers and other related appendages to aid in
the detection of masks on a person’s face.
The main objective of the project is to identify whether the
person is wearing a mask or not. Since the COVID 19 epidemic
hit, public safety and hygiene is number one priority.


Libraries and Files Required:
1. OpenCV (version 2.7.10)
2. Haar cascade for frontal face
3. Haar cascade for eye
4. pandas 
5. numpy


Working:

The basic idea behind the project is to detect if a person is wearing a
mask or not. If a person is wearing a mask then ideally the mask
should cover the person’s mouth and nose. If he is not wearing a mask
then his mouth and nose should be visible.
So instead of looking for the mask, we can use the haar cascades to
check if the person’s mouth and nose is visible or not. Hence, we have
used 2 haar cascades files in the current project. One is the classifier
for the frontal face, second is the classifier for the eyes.
Using the concepts of deep learning and haar cascades discussed
above, we find if the person’s mouth is visible. If the mouth is not
visible then that means the person is wearing a mask. Second case is
if the eyes are not detected the output will be no face found.
