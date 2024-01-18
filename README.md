# GestureVoiceComposer

Welcome to GestureVoiceComposer, a project that combines the power of speech recognition and hand gestures. This interactive application uses a combination of MediaPipe Holistic and a trained LSTM model to recognize and respond to both spoken words and hand gestures.

## Features

- **Speech Recognition**: Utilizes gTTS (Google Text-to-Speech) to vocalize recognized words.
- **Real-time Visualization**: Provides a graphical interface with visual cues for detected gestures and recognized words.
- **Dynamic Predictions**: Utilizes a trained LSTM model for accurate predictions based on a sequence of detected keypoints.

## Gesture Reference

Below are the hand gestures used in GestureVoiceComposer:

1. **Gesture for Action 1**
   ![Hello](images/hello.png)

2. **Gesture for Action 2**
   ![Bye](images/bye.png)

3. **Gesture for Action 3**
   ![Thanks](images/thanks.png)

4. **Gesture for Action 4**
   ![Love](images/love.png)

5. **Gesture for Action 5**
   ![Shoot](images/shoot.png)

## Getting Started

To get started with GestureVoiceComposer, follow these simple steps:

1. Clone the repository to your local machine: git clone https://github.com/krish-sky1ark/GestureVoiceComposer.git
3. Install the required dependencies mentioned below
4. The Training dataset is present in the directory name Training_Dataset
5. To build a new model Run the GestureVoiceComposer.ipynb file.
6. To just test a model in real time run RealTimeTesting.ipynb mentioning path of the model.
7. GVCmodel.h5 is the pre-trained model trained on training dataset provided.
8. While testing make hand gestures like those displayed above. The model predicts the action and speaks it.

## Dependencies

- Python 3.x
- OpenCV
- MediaPipe
- gTTS (Google Text-to-Speech)
- NumPy
- TensorFlow
- Pygame
- Keras
- matplotlib


## Conect with me:
- LinkedIn: [LinkedIn Profile]( https://www.linkedin.com/in/krish-khadria-034401271/)
- GitHub: [GitHub Profile](https://github.com/krish-sky1ark)


Happy GestureVoiceComposing!
