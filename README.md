This repository is dedicated for coding Face Swapping.

Following are the dependencies for getting it executed:
1. dlib (http://dlib.net) with it's python bindings
2. OpenCV(latest version)
3. Pretrained model for shape prediction(http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2)

Instructions for execution:
1. change `PREDICTOR_PATH` to refer to the unzipped location forÖ shape_predictor_68_face_landmarks.dat.bz2
2. do ./faceswap.py <head image> <face image>
3. Controlling COLOUR_CORRECT_BLUR_FRAC, you can control swapping and color correction for swapping facial features in the <head image> with the ones in the <face image>
4. check the output image with name output.jpg inside the current working directory


Sample output below:

Head image:
[[https://github.com/ashutoshmishra1014/swapface/ronaldo-statue.jpg]]

Face image:
[[https://github.com/ashutoshmishra1014/swapface/tom-cruise.jpg]]

Output:
[[https://github.com/ashutoshmishra1014/swapface/output-1.9.jpg]]