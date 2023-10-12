## Presentation: [Slides](https://docs.google.com/presentation/d/1sPMz38P73mUkgJ6v_nm7Hpm6KUa3pVnSuL3Z5iRm6Ro/edit?usp=sharing)

## Coding session:

- HandPose

## Examples

- New ml5js next gen handpose ([ml5 next gen](https://github.com/ml5js/ml5-next-gen), [All examples](https://github.com/ml5js/ml5-next-gen/tree/main/examples))

  - [handpose start and stop](https://editor.p5js.org/yining/sketches/PLf5QNeFA)
  - [handpose keypoints](https://editor.p5js.org/yining/sketches/H7qZS8iMF)
  - [handpose parts](https://editor.p5js.org/yining/sketches/2WwwqrhNl)
  - [handpost image](https://editor.p5js.org/yining/sketches/624wmm2X5)
  - New body pose blaze pose [Blazepose-keypoints-ml5-next-gen](https://editor.p5js.org/yining/sketches/2WEyiBBNq) (more points, more stable)

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

## Assignment 5

### Reading & Video

- [ml5.js: Pose Classification with PoseNet and ml5.neuralNetwork()](https://www.youtube.com/watch?v=FYgYyq-xqAw)
- [Face and hand tracking in the browser with MediaPipe and TensorFlow.js](https://blog.tensorflow.org/2020/03/face-and-hand-tracking-in-browser-with-mediapipe-and-tensorflowjs.html)

### Coding exercise

- [ml5js-next-gen template](https://editor.p5js.org/yining/sketches/naAUksCCh)
- [handpose keypoints](https://editor.p5js.org/yining/sketches/3_ZAxFgM8)
- [handpose-rect](https://editor.p5js.org/yining/sketches/oOdpbcLbT)

Use the HandPose model, and following the examples and [ml5.js documentation](http://learn.ml5js.org/) experiment with controlling elements of a p5.js sketch (color, geometry, sound, text) with the output of the model. (You may also choose a ml5.js model not covered here if you like!)

Document your p5.js sketch in a blog post and add a link to the post / your p5 sketch on the [homework wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F23/wiki/Assignment-5). In your blog post, include visual documentation such as a recorded screen capture / video / GIFs of your sketch.
