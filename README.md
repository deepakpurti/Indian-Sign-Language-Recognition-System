# Indian-Sign-Language-Recognition-System
Sign Language Recognition System using Computer Vision techniques and Deep Learning,  
based on https://github.com/EvilPort2/Sign-Language .

## Changes from original repository
* This system is for recognition of Indian Sign Language which uses both hands for most gestures,  
  while the original repo was for American Sign Language in which only one hand is used.
* This system uses Adaptive Thresholding instad of Local Thresholding while tracing the contour of the hand,
  which allows it to detect edges of individual fingers even when placed on the other hand.
