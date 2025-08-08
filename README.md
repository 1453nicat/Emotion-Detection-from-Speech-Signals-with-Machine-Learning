# Emotion-Detection-from-Speech-Signals-with-Machine-Learning
This project implements a CNN &amp; BiLSTM model for speech emotion recognition using the CREMA-D dataset.

## Overwiev
Furthermore, it implements a deep learning model for classifying human emotions from speech signals using the [CREMA-D](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio) dataset. The model combines a 1D Convolutional Neural Network (CNN) and a Bidirectional LSTM to capture both local acoustic patterns and long-term temporal dependencies in audio.

## Emotions Detected
- Angry, Disgust, Fear, Happy, Neutral, Sad

## Model Architecture
- **Input**: MFCC, Chroma, Mel-spectrogram, and ZCR features (combined)
- **Layers**: Conv1D → BatchNorm → MaxPooling → Bidirectional LSTM → Dense
- **Output**: 6-class softmax for emotion classification
- **Accuracy**: ~53% (due to data imbalance and complexity of emotional expression)


## Dataset
[CREMA-D: Crowd-Sourced Emotional Multimodal Actors Dataset](https://doi.org/10.1109/TAFFC.2014.2336245)

MIT License
Copyright (c) 2025 *1453nicat*
## Author
[Your Name]  
*Speech Emotion Recognition Project – Academic Study*
