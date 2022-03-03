<div align="center">
<h1>Classification of 9 types of Fish using VGG-16</h1>
</div>

<h1>Project Objectives</h1>
To implement a Convolutional Neural Network using the VGG-16 model to classify images in a dataset consisting of 9 different varities of fish using Tensorflow and Keras libraries.


<h2>Data Split</h2>
The project requires 80% of the data to be considered for training purposes and 20% for testing purposes.The command used to split the images into training and test sets are test_imgs, train_labels, test_labels = train_test_split(img_arr, categories,test_size = .2) to split up the data into training and test data.

<h2>Class Labels</h2>
Labels of 0-8 are assigned for the 9 different types of seafood. A label binarizer is used to assign the assign the class for which the model outputs the highest confidence.

<h2> Model Architecture</h2>
<p float="left">
<img src="https://github.com/jayesh68/CATS-VS-DOGS-CLASSIFICATION/blob/main/architecture.png"/>
</p>

<h2>Training</h2>
The model is trained for 10 epochs using the Adam optimizer which is a stochastic gradient descent method based on adaptive estimation of first and second order movements. The loss function used is the categorical cross entropy loss since there are two or more classes to predict.

<h2>Training Results</h2>
<p float="left">
<img src="https://github.com/jayesh68/CATS-VS-DOGS-CLASSIFICATION/blob/main/Training.png"/>
</p>
<p float="left">
<img src="https://github.com/jayesh68/CATS-VS-DOGS-CLASSIFICATION/blob/main/Loss.png"/>
</p>

<h2>Results on test dataset</h2>
The test accuracy obtained was around 96%. 
<p float="left">
<img src="https://github.com/jayesh68/CATS-VS-DOGS-CLASSIFICATION/blob/main/predict.png"/>
</p>
