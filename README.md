# Emotion Detector
# Midterm Assignment (Build an AI Startup)

The production deployment of the app: https://emotion-detector.onrender.com/

## Team members:
## 1. jmjayashree32@gmail.com (Jayashree)
## 2. choudhury.michael@gmail.com (Michael Choudhury)
## Classification service for identifying emotions on human faces using a simple web app programmed in Python-3.
## ML/DL frameworks used: Fastai computer vision; PyTorch
## How to use the web app?
- ### Choose an image of a happy, sad, or an angry face or use google or take a photo using a smart phone
- ### Save the image to your PC
- ### Upload the image to the app
- ### Click the 'Analyze' button
- ### Read the result

<br> <br> <br>

# https://emotion-detector.onrender.com/

![ ](emotionClassifierPNG.PNG)


# Emotion Detector
<br>
## Prototype
<br>
### About the application
<br>
### The user have to upload a image of a person with having a smile, angry and sad emotion type then the model will predict its percentage for each emotion class. Our model consists of 3 classes happy, angry and sad.
<br>
### 1. Authentication Process: A login page will be shown in the user side once a donation has been made. You have to login if your account exists otherwise you have to create an account by navigating to the payment page and there you have create an account. Then you can login in after creating getting credentials.
### 2. User Interface: It contains a section where you have to upload your picture and click the predict button to get your result.
### 3. Payment Process: During the signup for the page a payment option will be there which is PayPal we only create an account in stripe and get some access tokens which we will use in our signup JavaScript code.
### 4. Model used: For training we have use  convolution neural network and a pre-trained model vgg16 (also a Convets)which was already  trained on millions of images so its weights were used to train our model.
### 5.Future scope: It can predict a better result than a psychologist can predict about a emotion of a human being. For that we can collect different images from the uploads and will be stored in a database so that further we can use it for training.
<br>
## Technology Stack
<br>
#### Frontend-Flask, HTML,CSS,Javascript
#### Deployment –Render
#### IDE used-Google Colaboratory, Kaggle Kernels
#### Languages-Python, JavaScript
