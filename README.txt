Baohua Zhu <bz22@uw.edu>

Android App: GesturesAccel - Be careful, the phone might explode when you shake it. 

Introduction

This is an Android App that detect "wing" gesture performed by the smartphone and captured with the accelerometer sensor.
The "wing" gesture is detected based on the model trained by convolutional neural network. The "wing" gesture looks like
the picture below. User can press Predict button and start doing different gestures, once the "wing" gesture has been detected,
the result will show 0 with corresponding confidence, otherwise, the result will show 1 with corresponding confidence. User can
press Clear button to clear the previous result and start a new detection process.

Functions
1. Predict button: Press predict to start gesture detection process.
2. Clear button: Press clear to clear the previous result.
