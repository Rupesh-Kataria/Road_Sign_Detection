# Road_Sign_Detection

We categorized road signs into four distinct categories using the YOLOv4 model. To fasten the training process, we employed transfer learning, leveraging pre-trained YOLOv4 weights that had already undergone training for 137 convolutional layers. Subsequently, we utilized these pre-trained model weights to classify road signs in images and videos by analyzing each frame individually with our YOLOv4 model. Moreover, we successfully incorporated our YOLOv4 model into a Flask website, enabling road sign detection from images, videos, and even webcam streams.
