# SignSense-AI (Project from the UCSC Cosmos 2023 AI program)
## **Overview**
Over 500,000 people across the U.S and Canada use American Sign Language (ASL) as their primary form of communication and are normally unable to easily communicate with the majority of the population who don't speak ASL. This deep learning model is designed to convert ASL FingerSpelling to Text, facilitating more efficient communication for ASL users when interacting with others.

## **Dataset**
The dataset used in this project was obtained from the Kaggle competition called "ASL FingerSpelling," which can be found at the following link: [ASL FingerSpelling Kaggle Competition]([URL](https://www.kaggle.com/competitions/asl-fingerspelling/data)). The dataset provides a valuable resource for training and evaluating the performance of our model.

![image](https://github.com/25eliu/SignSense-AI/assets/45324290/a1092d98-0775-4cd5-a3b2-c7bc6c932817)

## **Pre-processing**
To prepare the data for training, we utilized MediaPipe, a popular deep-learning framework for processing multimedia data. MediaPipe helped us extract relevant features and information from the ASL FingerSpelling dataset, ensuring that the input to our model was formatted correctly for effective learning.

![image](https://github.com/25eliu/SignSense-AI/assets/45324290/d9258153-d4d2-4db7-8d7e-295381e71c08)

## **Model**
We implemented our deep learning model using TensorFlow, a powerful and widely-used open-source machine learning library. We took inspiration from the following Kaggle notebook by Gusthema, which significantly contributed to the foundation of our work:[ ASL Fingerspelling Recognition with TensorFlow]([URL](https://www.kaggle.com/code/gusthema/asl-fingerspelling-recognition-w-tensorflow)).

## **Post-processing**
The post-processing step, which is crucial for refining the output of our model, was made possible by leveraging the capabilities of GPT-3.5. This advanced language model helped us fine-tune and improve text conversion accuracy, ensuring smoother and more accurate communication for ASL users.

## **Project Development**
This ASL FingerSpelling to Text deep learning model was developed as part of the UCSC Cosmos 2023 program. The collaboration and dedication of the team members made this project a reality, and we are proud to contribute to enhancing communication accessibility for the ASL community.
