# ImageClassifier

⚙️ A Convolutional Neural Network (CNN) based Image Classifier Using Machine Learning

Problem Statement
==================

 The problem statement as below was for Blockchain technology.

The problem statement was a part of [TECHGIG](https://www.techgig.com)'s hackathon held from 18th July to 2nd Sepember 2018. The hackathon [Springer Nature Pune Hack Day: Decoding Scientific Content](https://www.techgig.com/hackathon/springernature-pune) – Hosted by Springer Nature Pune on decoding scientific content, is a challenge designed to inspire creative and dynamic technology professionals to put their skills to the test. Spread over four weeks, Springer Nature Pune Hack Day: DSC is a platform that allows aspiring tech experts to display their technical prowess in new technologies including ML, NLP, AI.

Every publisher aspires to automate the identification, classification, enhancing, etc. of images using computer vision, which has a large variety of practical applications. Since this task of recognizing a visual concept is relatively trivial for a human to perform and is worth considering the challenges involved are from the perspective of a computer vision model. This problem statement talks about the need to automate the identification of the images as color or grey, which would help the publisher in decision making.

Background Information
==================

The manuscripts submitted by authors have many images inside it. These images can be either colour or grey or both. As part of the business services, the author submitted images will be processed by the publisher before publication. The processing of images differs for color and grey scale images. The identification of this helps to further automate their processing.


Use Case Description - What we have tried to build
=====================

1. The Image Colourfulness Identification system
2. The system to identify whether the image is grey or colour (with good sensitivity)
3. Use Cases:
    * Use Case #1: Verify whether the image is grey or colour along with the percentage of confidence
    * Use Case #2: Must identify an image is colour even if the respective image has a small, clear and distinct colour information on it
    * Use Case #3: Must identify an image is grey even if the respective image has very extremely small degree of colour artefacts in it (not noticeable visually but will/may be computationally)
4. It automates the identification of the images as colour or grey, which would help the publisher in decision making


Problem Being Solved
=====================

1. Avoid the manual verification of the images as colour or grey
2. Fully automate the current partial automated process to identify images as colour or grey
3. Reduce the probability of image misclassification
4. Reduce the additional cost that an author has to bear due to faulty processing of images
5. Avoid an additional manual visual checking of each image which would also save the time
6. Help the publisher in decision making
7. Help to further automate publishers processing
8. Classify images with good percentage of confidence


Technology/Tool/Cloud Stack
=====================

* Machine Learning, Deep Learning
* Convolutional Neural Network (CNN)
* TensorFlow
* Python
* OpenCV
* Softmax
* Shape function


Hardware Specifications
=====================

* CPUs
* GPUs


Solution Approach and Architecture
=====================

The Open Auction Approach - Trust And Transparency

![alt text](https://github.com/sachinjegaonkar/ImageClassifier/blob/master/Architecture.jpg)


Demonstration Video/Prototype Demo
=====================

[![Watch the Demo](https://github.com/sachinjegaonkar/ImageClassifier/blob/master/Demo.jpg)](https://youtu.be/yo_97h_pUqE)


Why This Solution Should be Considered
=====================

* Platform Independent - Runs on verity of platforms - from desktops to clusters of servers to mobile and edge devices
* Easy deployment - can run on multiple CPUs, GPUs and TPUs (Tensor processing unit)
* System identifies an image is colour or grey along with confidence factor
* System identifies grey images with extremely small colour artefacts also as grey with good percentage of confidence
* System identifies even images with small, distinct/clear colour information on it as colour with good percentage of confidence
* Solution is based on Training Data, Validation Data and Test Data


Challenges Faced
=====================

* Selecting the solution approach
* Deciding the solution model which fits the requirements


Possible Improvements
=====================

* Select better network design to get more accurate output\predictions
* Improve Predictions
* Improve Optimizations


References
=====================

* [Machine Learning, Deep Learning](https://cv-tricks.com/tensorflow-tutorial/training-convolutional-neural-network-for-image-classification/amp/)
* [Convolutional Neural Network (CNN)](https://www.tensorflow.org/tutorials/images/deep_cnn)
* [TensorFlow](https://www.tensorflow.org/)
* [Python](http://www.learnpython.org/)
* [OpenCV](https://www.learnopencv.com/image-classification-using-convolutional-neural-networks-in-keras/)
* [Machine Learning Crash Course (MLCC)](https://developers.google.com/machine-learning/crash-course/)
