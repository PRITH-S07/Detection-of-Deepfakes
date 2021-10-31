# Deepfake-face-detection

In this repository, I have worked on deepfake image detection using MTCNN and InceptionResnetV3.<br>
The links to the weights file and the google colab code has been provided in this repository.<br>

Here, a frame extraction was performed on the training data from the Deepfake Detection Challenge from Kaggle. <br>
Then MTCNN was used for face extraction and each cropped frame was saved as an image based on the label.<br>
Following this, I built the InceptionResnetV3 network and used the pre-trained Imagenet weights.

This model gave me a 99.73% training accuracy and a 93.58% validation accuracy.<br>

The loss and accuracy graphs are given below:

<img src='https://drive.google.com/file/d/1GRv2J_li_-KUmgx-oVqO9QKZd6Y7cQyB/view?usp=sharing'></img>
