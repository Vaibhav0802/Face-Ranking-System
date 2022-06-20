# Face-Ranking-System
Face Ranking System

Hi, this is the repository of the face ranking system made by me. First I will explain you, what it does and then I will explain you how to run it properly. So, first what we do is, improve the quality of images, then we do facial landmark detection using Dlib, which needs a pre trained model to work. Here we do facial landmark detection two times on the same image, using two different models, one model 68 detects facial landmarks and the other detects 81 facial landmarks, using the combination of both models we extracted all the features ( that are defined by different scientists for a person to have a perfect and beautiful face) of a person's face. Then I applied a technique called topsis on it, which ranks the faces on basis of the features and returns us a csv file containing the ranks of the images.
Now let us see, how to run the code. The file is uploaded in the form of a colab notebook. This code needs both models to be uploaded onto your drive, as this code needs both models to work. Also, you can change the number of images you are ranking by changing the value of n in the first block of colab notebook. Aft
