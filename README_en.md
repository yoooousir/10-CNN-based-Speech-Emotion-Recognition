## Project Overview

A project that developed and trained a speech-based emotion recognition model using Convolutional Neural Networks (CNN). It involved data preprocessing, feature extraction and processing, and model training, creating a comprehensive pipeline for consistent audio file processing. The model's performance was evaluated using metrics such as Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.

### Features and Workflow

- **Dataset Integration**: Incorporates multiple emotional speech datasets (e.g., RAVDESS, CREMA-D, SAVEE, TESS).
- **Preprocessing**: Processed audio data augmentation with "noise injection", "pitching", and "stretching". We also handled "null" processing and duplication deletion.
- **Emotion Classification**: Classifies emotions into the following categories: 'angry', 'calm', 'disgust', 'fear', 'happy', 'neutral', 'sad', and 'surprise'.
- **Feature Engineering**: Audio features such as "Mel Frequency Cepstral Coefficients", "Root Mean Square", and "Zero Crossing Rate" were extracted. 
- **Model Building and Structure**: A 10-layer CNN model with 1D convolutional layers, batch normalization, and max pooling is implemented. The model includes multiple Conv1D layers with ReLU activation, followed by dense layers for classification. It achieves efficient feature learning for emotion classification with approximately 6.15 million trainable parameters.

### Usage Instructions

1. Prepare the audio dataset in the specified directory.
2. Run the preprocessing and feature extraction scripts.
3. Train the model and evaluate its performance using the provided training and evaluation scripts.
