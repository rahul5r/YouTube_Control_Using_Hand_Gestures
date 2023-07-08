# YouTube_Control_Using_Hand_Gestures
**Project Title:** Youtube Control using Hand Gestures

**Project Description:**

This project allows users to control YouTube videos using hand gestures. The project uses a webcam to capture the user's hand movements, and a machine learning model to identify the hand gestures. The machine learning model was trained on a dataset of hand gesture images, and can identify 8 different gestures: "v_up", "v_down", "right", "left", "max", "min", "stop", and "free_hand".

When the user makes a hand gesture, the project sends a corresponding keyboard command to YouTube. For example, if the user makes the "v_up" gesture, the project will send a keyboard command to increase the volume of the YouTube video. The project also supports a "free_hand" gesture, which means that the user is not making any specific gesture. In this case, the project will not send any keyboard commands to YouTube.

The project is implemented using Python and the OpenCV library. The machine learning model was trained using the Teachable Machine platform.

The following controls are done with their respective gestures:
**Start or Stop :** ![stop_start](https://github.com/racker9r/YouTube_Control_Using_Hand_Gestures/assets/111962760/39487be2-97e1-4fb5-9e90-fe975c411e8f)
**Volume Up :** ![volume_up](https://github.com/racker9r/YouTube_Control_Using_Hand_Gestures/assets/111962760/8ef8f366-c5cc-4702-8ef4-3a6465b8c980)
**Volume Down :** ![volume_down](https://github.com/racker9r/YouTube_Control_Using_Hand_Gestures/assets/111962760/c1339709-8e0d-455e-a14d-6df9cbc6cd98)
**Full-Screen Mode :** ![max](https://github.com/racker9r/YouTube_Control_Using_Hand_Gestures/assets/111962760/4c96c203-fd3c-4dc8-bc88-8cdfe46c9c02)
**Exit Full-Screen Mode :** ![min](https://github.com/racker9r/YouTube_Control_Using_Hand_Gestures/assets/111962760/8c27a493-33b0-4846-b262-1e8421de3d9e)
**Skip Right by 5 sec :** ![right](https://github.com/racker9r/YouTube_Control_Using_Hand_Gestures/assets/111962760/e1ee6b30-f3d1-44f5-b980-e59f0654fc35)
**Skip Left by 5 sec :** ![left](https://github.com/racker9r/YouTube_Control_Using_Hand_Gestures/assets/111962760/b748e28e-64aa-42f1-a38c-c9fd6b233392)

**Project Benefits:**

This project can be used to make YouTube more accessible to people with disabilities. For example, people with limited mobility may find it difficult to use a keyboard or mouse to control YouTube videos. This project can allow them to control YouTube videos using their hands, which can be much easier and more natural.

The project can also be used to make YouTube more fun and engaging. For example, users can use hand gestures to play games, control music playback, or interact with other users.

**Project Challenges:**

One challenge of this project is that it requires a webcam to capture the user's hand movements. This may not be possible in all situations, such as when the user is watching YouTube on a mobile device.

Another challenge is that the machine learning model may not be able to identify all hand gestures perfectly. This can lead to false positives, where the project sends a keyboard command when the user did not intend to make a gesture.

**Project Future Work:**

One possible future work for this project is to improve the accuracy of the machine learning model. This could be done by training the model on a larger dataset of hand gesture images.

Another possible future work is to add support for more hand gestures. This could allow users to control YouTube videos in more ways.

Finally, it would be interesting to explore ways to make this project more accessible to people with disabilities. For example, the project could be adapted to work with a touchscreen device.
