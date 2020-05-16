# DermaVision - A Skin Disease Diagnostic System

### This is a automatic skin disease diagnostic system built for the Microsoft code.fun.do Contest held at the Indian Institute of Technology in 2017. 

It is a web application that has an interactive chat-like interface.
It attempts to diagnose skin diseases based on images of the person's skin.
The project employs the django web development framework, and the tensorflow library for deep learning. 

A dataset was created by scraping annotated images of diseased skin as well as healthy skin from the web. 
The Inception network, the then state-of-the-art convolution neural network for image classification, was fine-tuned on these annotated images to create out skin disease classification system in the backend. 


### To run the web application:
Run:
```
python manage.py runserver
```
And, go to http://127.0.0.1:8000/
