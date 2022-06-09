# Motion-Detection-using-frame-differencing-with-opencv

As the name suggests, we can detect any moving object in a video using this technique. Basically, the main motive here is to do motion detection in videos.

Moving object detection has a range of use cases ranging from surveillance to security. So, finding a technique that can be easily used in low computation devices is crucial.

### Frame Differencing and Summing Technique in Computer Vision

We know that a video consists of multiple consecutive frames. And these frames are made up of pixels which consist of colors (red, green, and blue). And these pixels are just values in the range of 0 to 255. 0 is completely black and 255 is white.

So, suppose that we take any two consecutive frames from a video. Now, let’s subtract the current frame from the previous frame. If they contain the same information (RGB color values), then the resulting frame will be completely black. But if the current frame consists of some newer information or pixel values, then we will see some sort of white patches after the subtraction. This tells us that something in the video has moved or changed position. This is a very simple concept. Yet we will use this as the basis for moving object detection in videos.

For more details, you can visit this [website](https://debuggercafe.com/moving-object-detection-using-frame-differencing-with-opencv/)
