# MOUSE_CONTROL_USING_HAND_GESTURES
Controlling  mouse using hand gestures

*Project Overview :This project implements a real-time, touch-free mouse control system utilizing hand gesture prediction. By combining computer vision and deep learning, it enables users to control mouse movements and clicks through hand gestures captured from a webcam.

*Key Features: 
  Hand Tracking: Detects and tracks hand movements in real time using OpenCV and MediaPipe.

  Gesture Recognition: Employs a Convolutional Neural Network (CNN) to accurately classify gestures for mouse actions (move, click, drag).

  High Accuracy & Low Latency: Achieves over 90% gesture recognition accuracy, with response times under 100 milliseconds.

  Cross-Platform Automation: Integrates PyAutoGUI and Pynput to translate recognized gestures into mouse events for seamless, OS-level interaction.

*Technology Stack
  Languages: Python

  Libraries/Frameworks: OpenCV, MediaPipe, PyAutoGUI, Pynput, NumPy, TensorFlow/Keras (for gesture recognition model)

*How it Works
  Webcam Input: Captures live video frames from the webcam.

  Hand Landmark Detection: Uses MediaPipe to identify landmarks of the user's hand.

  Feature Extraction & Prediction: Processes landmark data and feeds it to a trained CNN for gesture classification.

  Mouse Event Mapping: Maps detected gestures to mouse events (move, left/right click, drag) through PyAutoGUI or Pynput.

*Usage Instructions
  Install dependencies:

  bash
  pip install opencv-python mediapipe numpy pyautogui pynput
  (If needed) Install additional packages for your platform—see project documentation.

  Run the main Python script. The webcam will activate; start using hand gestures in front of the camera to control the mouse.


Demo :

<img width="802" height="494" alt="Screenshot 2025-07-18 at 1 37 41 AM" src="https://github.com/user-attachments/assets/19564d7e-1066-494a-9a28-2d1c6990b9ed" />


Applications:
  Accessibility tools for users with limited mobility

  Touch-free interfaces for public kiosks

  Innovative controls for gaming or creative software
