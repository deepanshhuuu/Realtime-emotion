# Emotion_detection_with_CNN

![image](https://user-images.githubusercontent.com/107347869/235224666-17c7c730-908d-4856-a09f-11c0ac0e376d.jpg)


### Packages need to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

### download FER2013 dataset
- You can download the FER 2013 dataset from the link given below 
- https://www.kaggle.com/msambare/fer2013

### Train Emotion detector
- You can train your model by running this file "TranEmotionDetector.py"

The model is trained for 50 epochs it took several minutes, it depends on your processor. (On i5 11400 H processor with 8 GB RAM and RTX 3050 it took me around 5 minutes) after Training the model, you will find the trained model structure and weights are stored in your project directory.

### run your emotion detection test file
python TestEmotionDetector.py
