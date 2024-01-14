# SoC2k21_Complete_Work

# Task 1 (A1)

Pandas Exercises : <br>
Learnt about pandas and numpy libraries and utilized the library functions to extract the information about the dataset.

# Task 2 (A2)

Matplotlib Exercies : <br>
Managed to get the statistical info about different columns of the dataset, and plotted various kinds of graphs for the data such as histograms and box-and-whiskers plots.

# Task 4 (B3)

Live Age and Gender Detection : <br>
build a Jupyter-based Age and Gender detection model using pre-trained deep learning Caffe models. This Jupyter code can detect one's gender and age bracket from live webcam feed.

In the path of achieving this goal, firstly learnt about the "**OpenCV**" and made some mini-projects also. And here are links to the notebooks :
- [Basics of Computer Vision and OpenCV](https://drive.google.com/drive/folders/17gzt3Q3oSPazu3HCJQ8qDS6j1pIQeF_9?usp=sharing)
- [Image Manipulations Processing](https://drive.google.com/drive/folders/15JnwKC6APfhTJPv3xDHg6B7aWtHhe5lw?usp=sharing)
- [Image Segmentation Contours](https://drive.google.com/drive/folders/13a0Pl5BxRUhW-24vkp8AMdK3m2TKJwR4?usp=sharing)

Also got a hands-on experience with the Deep learning library - "**PyTorch**", build Deep Learning and Neural Networks model from skretch, trained the network, then tested to estmiate the accuracy, for each of the following :
- [Handwritten Digit Recognition](https://drive.google.com/file/d/1QWp-EMybRCUuMxHTKHsMPKGFPfguXJxz/view?usp=sharing) with an accuracy of **98%**
- [Distinction between Cats and Dogs](https://drive.google.com/file/d/1sEyuZuFoGWRq7UQUGM81YbCwUUxAHzlw/view?usp=sharing) with an accuracy of **76%**

# Task 5 (B4)

Age and Gender Detection on YouTube Videos : <br>
Tried a variation of previous model on colab in which instead of giving live webcam feed we can give a youtube video link, the code then can process the video, identify age and gender of as many people as there are in the youtube video.

# Task 6 (C1)

Making Android App for Gender + Age Detection : <br>
Got to know about TFLite and Android Studio, and utilizing previously learnt concepts to give "Jupyter-based Live Age and Gender detection model" a shape of "Android App".

# Task 7 (C2)

Making Colab Based Face Detection + Recognition + Cluster Project : <br>
Built a Colab based Web-App to Detect the faces of people in the frame provided and then Recognition them using the priviously feeded data(basically fair number of photos for each person, to be recognized, with name). Also added a feature for Clutering the photos of different people from a pool of images (makes a Group of photos of a single person).

Working :
- First we recognize the face from a photo using the facial_recognition model developed by Adam Geitgey.
- Then we extract 128-d encodings of the face using Histogram of Oriented Gradients (HOG) method.
- For the recognition of a face in new image, we computing the Euclidean distance between the candidate embedding and all faces in our dataset : <br>
  - If the distance is below some tolerance, this indicates the faces match.
  - Otherwise, if the distance is above the tolerance threshold, indicates faces do not match.
- Then we group similar faces together for clustering task using DBSCAN
# facial-recognition-app
