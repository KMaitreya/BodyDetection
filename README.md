# BodyDetection

This is a Palm tracking python program. It uses machine learning to track the movements of your body using 32 reference points. It is made with the help of mediapipe(https://google.github.io/mediapipe/solutions/pose) a library built by google.

Download mediapipe with the following command- pip install mediapipe

The body is tracked using 32 reference points. These reference points are predefined. The reference points are as follows-

![image](https://user-images.githubusercontent.com/47482433/123534918-27c38000-d73e-11eb-8cc4-97c8c77bdbe1.png)

After executing the program a camera window will open up, you will be able to see your body being tracked in this camera window. This program also shows the frame rate in the top left corner of the camera window once the program is executed.

Libraries used-> opencv(cv2), mediapipe, time.
