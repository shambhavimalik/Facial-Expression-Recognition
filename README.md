# Facial-Expression-Recognition

The objective is to build a real time face expression recognition model that can classify each face based on the emotion shown into one of seven categories:
- 0=Angry
- 1=Disgust 
- 2=Fear
- 3=Happy
- 4=Sad
- 5=Surprise
- 6=Neutral

![](https://baileyb.pbworks.com/f/PSA-2011-05-matsumoto-fig1_tcm7-115934.jpg)

## Data

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image.

train.csv contains two columns, "emotion" and "pixels". The "emotion" column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. The "pixels" column contains a string surrounded in quotes for each image. The contents of this string a space-separated pixel values in row major order. The training set consists of 28,709 examples.

test.csv contains only the "pixels" column.

This dataset was prepared by Pierre-Luc Carrier and Aaron Courville, as part of an ongoing research project. It can be found [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
After training, saving, and exporting the CNN,  directly serve the trained model predictions to a web interface and perform real-time facial expression recognition on video and image data.

**Used Keras, OpenCV and JSON.**

## References
- Challenges in Representation Learning: Facial Expression Recognition Challenge [Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/overview)

- Goodfellow, I.J., et.al. (2013). Challenged in representation learning: A report of three machine learning contests. Neural Networks, 64, 59-63. [doi:10.1016/j.neunet.2014.09.005](https://arxiv.org/pdf/1307.0414.pdf)

