<!-- # face-recognition -->
# Face Recognition using Deep Learning CNN
Convolutional Neural Networks(CNN) changed the way we used to learn images. It made it very very easy! CNN mimics the way humans see images, by focussing on one portion of the image at a time and scanning the whole image.

CNN boils down every image as a vector of numbers, which can be learned by the fully connected Dense layers of ANN. More information about CNN can be found here.

Below diagram summarises the overall flow of CNN algorithm.
![CNN-face-recognition-case-study](https://user-images.githubusercontent.com/77064772/201739240-defd1705-d5df-4122-8c58-b532eb653c83.png)

[Data Set used](https://thinkingneuron.com/wp-content/uploads/2020/10/Face-Images.zip)

The data contains cropped face images of 16 people divided into Training and testing. We will train the CNN model using the images in the Training folder and then test the model by using the unseen images from the testing folder, to check if the model is able to recognise the face number of the unseen images or not.

The CNN algorithm has helped us create many great applications around us! Facebook is the perfect example! It has trained its DeepFace CNN model on millions of images and has an accuracy of 97% to recognize anyone on Facebook.
