# The-Workaholics
Senior Design Project 

Background
--------------------------------
For this project, we'll be using Deep Learning. I believe we'll have to use a CNN, or a convolutional neural network, which is used to analyze visual imagery. It's often used for image recognition and motion detection. To train a model we'll have to gather training data (images) and then split that data into training and testing sets. Normally, it's split to 90% training and 10% testing. 80% training and 20% testing is also a popular split. For example, say you have 1000 images. Out of those 1000, 900 will be for training and 100 for testing. We will train our model on that training data, and then we'll give it the test data to see how well we've trained it. Gathering a large (or large-ish) pool of data is important, because the amount of data you train on directly affects how well the model does. It's also important to make sure your data is distinct (don't have a lot of the same images) and consistent (try to make sure you don't have any text or other objects in your images) because it affects the performance of the model. The construction of the model is also very important. If you construct a bad model, you might experience overfitting, which is when the model becomes too accustomed to the training data and has high accuracy (usually 100 percent) but tests poorly on the test data. 

Basically it goes like this: Imagine you want a model to differentiate between different kinds of dogs. So you gather your data of different kinds of dogs, feed it to the model, test it, and then it spits out what it thinks it is.

Training data (pictures of dogs)==Feed into model==> CNN==> Test model=====>Model spits out what it thinks it is==>This is a dog.

Some libraries that we will probably use are Tensorflow, Keras (it's part of Tensorflow), OpenCV, and probably some other libraries. Tensorflow and Keras are both used to construct deep learning models, and OpenCV is a library for computer vision. We might use others as required. One Youtube channel that has a great many videos on Deep Learning and Neural Networks in general is Deep Lizard. She uses plenty of diagrams and she explains things in a very easy-to-understand way. There are also numerous other videos on YouTube covering this subject, so don't be afraid to look around.

This is by no means an exhaustive explaination. I'm NOT an expert on Deep Learning, despite taking the class, so you guys will have to do your own research on the subject if you don't understand something completely. Or just ask me and I'll see if I can help. 
