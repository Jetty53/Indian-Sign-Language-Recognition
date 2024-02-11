# Indian Sign Language Recognition and Sentence Generation

This project aims to develop a robust system for recognizing and interpreting Indian Sign Language (ISL) gestures using advanced deep learning techniques. Leveraging Long Short-Term Memory (LSTM) networks and the Mediapipe library, the project will empower communication for individuals with hearing impairments by providing an efficient and accurate means of translating sign language into text or spoken language. By combining the power of LSTM networks and the convenience of the Mediapipe library, this project aims to create an effective and accessible tool for Indian Sign Language recognition, contributing to enhanced communication opportunities for the hearing-impaired community.

## WorkFlow model of the project
![alt text](https://github.com/Jetty53/Indian-Sign-Language-Recognition/blob/master/Sample_Images/ISL_WorkFlow_no_color.jpg)

Please go thorugh the included project report for detailed explaination.

## Final Classification Result
![alt text](https://github.com/Jetty53/Indian-Sign-Language-Recognition/blob/master/Sample_Images/Final_prediction_chart.png)

## Working Demo of the Project
![alt text](https://github.com/Jetty53/Indian-Sign-Language-Recognition/blob/master/Sample_Images/Project_demo.png)

## Future Works
- Gather more datasets from different people.
- Use image augmentation, image transformation, and image scaling for better real-life prediction.
- Try to decrease the final prediction time so that the prediction can happen more quickly.
- Find a way to predict two of the same expressions consecutively.
- ISL expressions include not only hand gestures but also facial expressions and poses. This project is done using only the hand and pose. Working on facial expressions is still in progress.
- Without using shift characters for model shifting, we can use model calibration algorithms like temperature scaling to calibrate the model to give a more realistic confidence score, and model shift can happen based on that confidence score.
