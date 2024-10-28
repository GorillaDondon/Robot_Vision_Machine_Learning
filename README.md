# Robot_Vision_Machine_Learning

This project implements a machine learning model for depth perception in robotic vision. By analyzing the pixel position of an object in a camera frame, the model predicts the object's distance from the robot. This application uses linear regression models in Python (PyTorch, TensorFlow, or Scikit-Learn) to provide accurate depth predictions based on camera-mounted data.

## Project Description
Depth Perception: Defined as the distance of an object from the camera on a robot, factoring in the angle of the robot's field of view.

Linear Perspective: The model leverages linear perspective techniques to project 3D objects onto a 2D plane, where depth can be inferred based on object position and the robot's known viewing angle.

Input Variables:
 - X (Independent): Height of the object in the camera frame.
 - Y (Dependent): Real-world distance measurement between the robot and the object.

Using this data, the project trains a linear regression model to predict the distance, with model options including PyTorch, TensorFlow, and Scikit-Learn implementations.

## Features
 - Multi-Framework Model Training: Options to build the model in PyTorch, TensorFlow, or Scikit-Learn.
 - Depth Prediction: Predicts the real-world distance based on pixel height data.
 - Empirical Depth Learning: Utilizes an empirical approach to tune and test model accuracy.
 - Accuracy Evaluation: Compares the accuracy of each framework’s linear regression model.

## Model Architecture
This project uses a Linear Regression Model:
 - Input: Object height in the camera frame (X).
 - Output: Predicted real-world distance (Y).
Each model in PyTorch, TensorFlow, or Scikit-Learn is trained to fit a linear relationship between the input (pixel height) and the target (distance).

## Contributors
Asser Moustafa - Computer Science and Engineering

Diego Esquivel - Computer Science and Engineering

Jo Ishizaki - Computer Science and Engineering

Nestor Gutierrez - Mechanical and Electrical Engineering
