# Smart-EduInnovators
<p align="center">
  <img src="https://github.com/Prajwal2001532/Smart-EduInnovators/blob/main/eduinnovaors%20logo.png" width="400" alt="Image 1">
  <img src="https://github.com/Prajwal2001532/Smart-EduInnovators/blob/main/oneapi%20logo.jpg" width="400" alt="Image 2">
</p>


Welcome to Smart EduInnovators on GitHub! Our project features an AI Trained Bot for advanced speech interaction, efficient information retrieval, and personalized voice recognition. Join us in revolutionizing education through cutting-edge technology.

## Problem Statement
Teachers always have to attend class. On some odd day, if they are absent, the university has to appoint their replacement for that duration. In this process workload on teachers is increasing day by day, and universities also have to pay extra money for the same. So here we are with the machine learning model, which is encrypted with the teacher’s voice, and the teacher can upload their content here.
So that it will explain the whole content to the student for a flexible duration. The text conversion module offers three functionalities as 

Personalization: allow users to create and save personalized voice profiles.
Batch processing: implement the ability to process a large number of texts in one go.
Online/offline mode: offer both online and offline modes.

The task of the teacher here is to upload content here and they just have to mention their time duration here, so it will explain the whole content for that duration.

## Architecture Design
![alt_text](https://github.com/Prajwal2001532/Smart-EduInnovators/blob/main/Achitecture%20Diagram%20-%20EduInnovators%20(1).png)

## Methodology
A web app profile is created. It contains individual profiles for each teacher. The profile is unlocked by the teacher's voice using the voice recognition model. After entering the profile, the teacher has the option to upload the prepared presentation for the upcoming lecture on which they have planned to take a leave. Once the ppt is uploaded, the slides are fetched using nltk package in Python. Then using the chatGPT API, explanations are fetched and appended into a .docx file.
This document is used for generating the final audio output using text to speech conversion model.

## What we Offer
1. Usage of user's voice for an encryption

2. Text-to-speech conversion using personalized voice 

3. Batch processing for converting bullet into the paragraphs

4. Conversion will be according to specific time duration

## Features

1. User can log in and register

2. Document/audio files can be uploaded
  
3. Convert the bullets into paragraphs
  
4. Paragraphs can be converted according to time duration

5. User can logout


