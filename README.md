# Voice Start-Stop Detection using MFCC and SVM

This GitHub repository contains a machine learning project for detecting voice segments that say "start" and "stop" using Mel-Frequency Cepstral Coefficients (MFCC) for voice preprocessing and Support Vector Machine (SVM) for classification.

## Project Overview

Voice start-stop detection is a crucial component in various applications such as voice-controlled systems and audio transcription. This project aims to accurately identify whether 'start' or 'stop' was spoken in a audio.

## Dataset

The dataset consists of 20 different voices, each saying "start" and "stop" in various intonations and styles. The audio samples are preprocessed using MFCC, a common technique for extracting features from audio signals. Principal Component Analysis is applied on the MFCC feature to reduce the dimensions serve as input to the SVM classifier.

## Workflow

1. **Data Preprocessing**: Audio samples are converted to MFCC feature vectors, which capture essential characteristics of the voices while reducing dimensionality.

2. **Feature Extraction**: MFCC features are extracted using libraries like Librosa, enabling efficient analysis of audio data.

3. **SVM Classification**: The SVM classifier is trained on the MFCC features of the "start" and "stop" audio segments. SVM is chosen for its ability to handle non-linear decision boundaries effectively.

4. **Model Evaluation**: The trained SVM model is evaluated using cross-validation techniques to assess its accuracy and generalization capabilities.

## Conclusion

This project showcases the use of MFCC preprocessing and SVM classification for voice start-stop detection. By leveraging machine learning techniques, accurate identification of "start" and "stop" segments in audio recordings can be achieved. This repository provides a comprehensive example for implementing voice detection systems in real-world applications.

For any questions or contributions, feel free to open an issue or submit a pull request.
