<!-- # face-recognition -->
# Face Recognition using Deep Learning CNN
CNNs are regularized versions of multilayer perceptrons. Multilayer perceptrons usually mean fully connected networks, that is, each neuron in one layer is connected to all neurons in the next layer.

CNNs use relatively little pre-processing compared to other image classification algorithms. This means that the network learns to optimize the filters (or kernels) through automated learning, whereas in traditional algorithms these filters are hand-engineered. This independence from prior knowledge and human intervention in feature extraction is a major advantage.

CNN boils down every image as a vector of numbers, which can be learned by the fully connected Dense layers of ANN. More information about CNN can be found [here](https://thinkingneuron.com/data-science-interview-questions-deep-learning/#What-is-a-Convolutional-Neural-Network(CNN)).

Below diagram summarises the overall flow of CNN algorithm.
![CNN-face-recognition-case-study](https://user-images.githubusercontent.com/77064772/201739240-defd1705-d5df-4122-8c58-b532eb653c83.png)

[Data Set used](https://thinkingneuron.com/wp-content/uploads/2020/10/Face-Images.zip)

The data contains cropped face images of 16 people divided into Training and testing. We will train the CNN model using the images in the Training folder and then test the model by using the unseen images from the testing folder, to check if the model is able to recognise the face number of the unseen images or not.

#### Reference
https://thinkingneuron.com/face-recognition-using-deep-learning-cnn-in-python/
