# Image Classification using Convolutional Neural Network (CNN) for flower photos
## If you also have problem dealing with overfitting, this notebook is for you!

### What does the project do
This code is about building a classification model for classifying the images of five type of flowers  **daisy**, **dandelion**, **roses**, **sunflowers**, **tulips**.
The Convolutional Neural Network as a deep learning algorithm was used for building the model.
In the first stage, the model was built on 3600 dataset. The results if the accuracy and loss showed that the training accuracy is linearly increasing over time,
whereas validation accuracy stalls around 60 % in the training process. This is a sign of overfitting where the difference between training and validation accuracy is noticeable.
Overfitting can happen due to several reasons. One of them which is the case in this example is the small number of training dataset. 
It caused the model learn from noises or unwanted details of the training dataset. In this case, the model has a difficult time generalizing on a new dataset. 
![image](https://github.com/shahrbanou90/Flower-photos-classification/assets/52621939/21672cfa-093d-4b50-883d-50fcd7f76ac4)

**Solution**
There are multiple solutions to deal with overfitting in the training process. One of them is data augmentation and add dropout to the model which we adopted in this project.
After implementing these two solutions, a new model has been built and evaluated. The results of the evaluation are shown below.
![image](https://github.com/shahrbanou90/Flower-photos-classification/assets/52621939/8a342739-a722-4cdd-b0f7-2cc45b932054)

### How can you get started with the project
All of the stages of the project have headings that makes it staigtforward for you to use it. 

### Can you make it better?
It seems that there is still a sign of overfitting in the results shown above. Can you make it better? 

