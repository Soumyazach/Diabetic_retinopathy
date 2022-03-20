The aim of the project is to detect Diabetic retinopathy (DR), a medical condition in which damage occurs to the retina due to diabetes mellitus.
It is detected by the presence of microaneurysms, small saccular outpouching of capillaries, retinal hemorrhages, ruptured blood vessels—among other features—on the fundoscopic images
Manual grading by ophthalmologists is done by  identifying diabetic retinopathy in retinal fundus photographs, which requires skilled labor and is time consuming. 
A chronic eye disease that affects 80% of those who had diabetics for 20 years or more.
Nearly 415 million diabetic patients at risk worldwide.
Deep learning artificial neural network approach, can achieve high sensitivity and specificity in detecting the referable diabetic retinopathy, defined as moderate or worse diabetic retinopathy. 

We used 3 types of Convolutional Neural Network models to train the data and develop the classification model :- Resnet, VGG, Inception 
RESULTS
* Resnet model produced an accuracy of 63% with 30 epochs. The accuracy increased with every epoch. Resnet produced better specificity and sensitivity.
* After training the model on 10 epochs and tuning hyperparameters the testing accuracy came out to be 62%But, the problem with VGG was as the epochs increases the loss was also increasing instead of decreasing. Also, the VGG16 architecture is very heavy and takes lot of computation power. So it was difficult to train VGG again and try to improve accuracy.
* Inception model accuracy did not improve with epochs The model predicted all the image levels as 0
* The accuracy produced by the above models are not good enough due to the presence of large data imbalance and the poor quality of the images. 
