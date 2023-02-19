# Head-Pose-Estimation
In this project I've worked on AFLW2000-3D dataset which is a dataset of 2000 images that have been annotated with image-level 68-point 3D facial landmarks, with various head poses for humans and animations.
By using mediapipe to extract faces landmarks which are 468 points in 3D, but we used x-axis & y-axis.
The regression model of predicting the 3 angles (pitch - yaw - roll) of head pose estimation was SVR model.

## Data
 You can download from http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip 
 This data contains different pictures for human faces with different poses.
 
 ## Steps:
  1) Preparing data for model training ( we used MediaPipe and CV2 libraries for extracting points and for face detection from pictures).
  2) Spliting the data to training and testing.
  3) Using SVR model.
  4) Detecting a random pic to validate the model from dataset.
  
  ![Trump-pose-estimation](https://github.com/NourhanNabil/Head-Pose-Estimation/blob/main/trump.gif)

  ![Messi-pose-estimation](https://github.com/NourhanNabil/Head-Pose-Estimation/blob/main/Messi.gif)
  
  ![Dog-pose-estimation](https://github.com/NourhanNabil/Head-Pose-Estimation/blob/main/dog.gif)

  ![Joe-pose-estimation](https://github.com/NourhanNabil/Head-Pose-Estimation/blob/main/joe.gif)

