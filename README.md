# Tensorflow Speed Estimation

Tensorflow speed estimation from dashcam optical flow

# Data

https://github.com/commaai/speedchallenge

- data/train.mp4 is a video of driving containing 20400 frames. Video is shot at 20 fps
- data/train.txt contains the speed of the car at each frame, one speed on each line.

Included `data/train_flow.txt` has the first value removed, as frame 0 will not have a generated optical flow image.