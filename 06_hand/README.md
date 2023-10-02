## Presentation: [Slides](https://docs.google.com/presentation/d/1sPMz38P73mUkgJ6v_nm7Hpm6KUa3pVnSuL3Z5iRm6Ro/edit?usp=sharing)

## Coding session:

- HandPose

## Examples

- [Handpose_Image](https://yining1023.github.io/machine-learning-for-the-web/face-hand/Handpose/Handpose_Image)
- [Handpose_Webcam](https://yining1023.github.io/machine-learning-for-the-web/face-hand/Handpose/Handpose_Webcam)
- Training hand pose model
- Hand pose tracking + KNN Classification, [p5 web editor code](https://editor.p5js.org/yining/sketches/uUwg0z9Z5), [demo video](https://www.loom.com/share/f81cf908e5b7404ba0071902019d67c2)
- Hand pose tracking + Neural Network, [demo video](https://www.loom.com/share/420fa5941dea411491af817011622c86)
  - [Collect data](https://editor.p5js.org/yining/sketches/dCoPm-Opb)
  - [Train the model](https://editor.p5js.org/yining/sketches/IrBFfXbSF)
  - [Run the model](https://editor.p5js.org/yining/sketches/6cFF9-L-Z)
- Multiple hands detection:
- [Handpose multiple hands with mediapipe](https://editor.p5js.org/yining/sketches/cME_7BnLW) If the webcam video is not loading, try open a incognito window, or set the camera access for the browser.
- [KNN Classifier on multiple hands](https://editor.p5js.org/yining/sketches/C91TLtexi): Change `HAND_NUM = 2` if you would like to detect other hand numbers. Once clicking on "Add example" button, it will start collecting data in 5 seconds for 5 seconds.

# Resource

- [ml5js - handPose source](https://github.com/ml5js/ml5-library/blob/development/src/Handpose/index.js)
- [tfjs - handPose](https://github.com/tensorflow/tfjs-models/tree/master/handpose)

# Projects

- [fingerspelling](https://fingerspelling.xyz/)

## Assignment 7

### Reading

- [Face and hand tracking in the browser with MediaPipe and TensorFlow.js](https://blog.tensorflow.org/2020/03/face-and-hand-tracking-in-browser-with-mediapipe-and-tensorflowjs.html)
- [face-api.js — JavaScript API for Face Recognition in the Browser with tensorflow.js](https://itnext.io/face-api-js-javascript-api-for-face-recognition-in-the-browser-with-tensorflow-js-bcc2a6c4cf07)

### Coding exercise

Pick one of the models (Face api, Face mesh or Hand pose), and following the examples and [ml5.js documentation](http://learn.ml5js.org/) experiment with controlling elements of a p5.js sketch (color, geometry, sound, text) with the output of the model. (You may also choose a ml5.js model not covered here if you like!)

Document your p5.js sketch in a blog post and add a link to the post / your p5 sketch on the [homework wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F23/wiki/Assignment-6). In your blog post, include visual documentation such as a recorded screen capture / video / GIFs of your sketch.
