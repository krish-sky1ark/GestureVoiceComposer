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

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the main script: `python main.py`.

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

## Contributing

Contributions are welcome! If you have ideas for improvements or would like to fix a bug, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Happy GestureVoiceComposing!
