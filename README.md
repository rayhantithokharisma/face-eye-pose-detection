# Face-Pose Change and Eye Gaze Detection

This project detect when user (via webcam) looking other than the screen/webcam.

## File List
This project is made simply in Jupyter Notebook. Consists of 2 files:

- fastapi-backend.ipynb - Run this Notebook to Deploy FastAPI in Localhost.
- inference-frame-by-frame.ipynb - Inference example using the deployed API.

## Methods
- This project utilize [retinaface model](https://github.com/serengil/retinaface) to calculate Yawl and Pitch of the face. 
- To calculate eye gaze, we utilize face landmarks from Mediapipe.
## Demo

![Demo GIF](./demo.gif)