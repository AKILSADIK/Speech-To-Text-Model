# Speech to Text Model using Keras

This repository contains a simple implementation of a speech to text model using Keras, trained on the LibriSpeech dataset for English speech recognition.

## Requirements
- Python 3
- Keras
- TensorFlow
- LibriSpeech dataset

## Installation
1. Clone this repository to your local machine:

```
git clone https://github.com/AKILSADIK/Speech-To-Text-Model.git
```

2. Download and preprocess the LibriSpeech dataset. You can find the dataset and preprocessing scripts at [LibriSpeech website](http://www.openslr.org/12/).


## Model Architecture
The model architecture used in this implementation is a simple recurrent neural network (RNN) with Long Short-Term Memory (LSTM) units. The input to the model is Mel-frequency cepstral coefficients (MFCCs) extracted from the audio signal.

## References
- LibriSpeech dataset: http://www.openslr.org/12/
- Keras documentation: https://keras.io/
- TensorFlow documentation: https://www.tensorflow.org/

## Credits
This project is inspired by various tutorials and implementations available online, and it's created for educational purposes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
