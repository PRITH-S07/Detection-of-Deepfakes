# Deepfake-face-detection

In this repository, I have worked on deepfake image detection using MTCNN and InceptionResnetV3.<br>
The links to the weights file and the google colab code has been provided in this repository.<br>

Here, a frame extraction was performed on the training data from the Deepfake Detection Challenge from Kaggle. <br>
Then MTCNN was used for face extraction and each cropped frame was saved as an image based on the label.<br>
Following this, I built the InceptionResnetV3 network and used the pre-trained Imagenet weights.

This model gave me a 99.73% training accuracy and a 93.58% validation accuracy.<br>

The loss and accuracy graphs are given below:

![yoyo](https://user-images.githubusercontent.com/58857629/139583625-0ad65768-ddda-46ff-897c-6e0792a1dc4b.JPG)

<br>
The output for every frame is a 2d vector which indicates how close each frame is to being a real or fake image.<br>
This can help us decide whether the video as a whole is a fake or real.
