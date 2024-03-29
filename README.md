> Instructor: [Dr. M. M. Ebadzadeh](https://scholar.google.com/citations?user=080Y_lUAAAAJ&hl=en)

> Semester: Spring 2022

# CIFAR-10
In this issue, we want to manipulate 10-CIFAR database images. This database is a smaller version of the CIFAR-100 database, which is limited to images from 10 different categories The dimensions of the images in this database are **32 (length (in 32) width (in 3)** RGB color channels. One of the most important steps in teaching artificial intelligence models is to prepare and pre-process the data so that it enters the model in the appropriate format. In this regard, a more complete explanation is given below. Here, we first need to convert the grayscale color images to gray in a step after processing, after which we will have 32 by 32 images. The input layer of the network has 32 * 32 = 1024 neurons, each of which shows the brightness of a pixel as an int number from 0 to 255. Here, to reduce the computational volume, we use only the images of the first 4 classes of this database. As a result, our output layer will contain 4 neurons. The neuron with the highest amount of activation is selected as the hand detected by our model. For this neural network, we consider two hidden layers, each of which has 16 neurons. So the structure of our neural network will be as follows:


<img width="383" alt="Screen Shot 1401-04-12 at 00 56 12" src="https://user-images.githubusercontent.com/71961438/177015353-c0b32e68-321e-4cc7-8dc9-cb33922db58d.png">
