
# Speech Command Recognition using Artificial Neural Networks

**Name**: Fares Hazem Mohamed Shalaby  
**ID**: 20221443356  

## Project Objective
The objective of this project is to build and evaluate a speech command recognition model using Artificial Neural Networks (ANNs). This model is designed to recognize specific spoken commands from audio input and classify them into predefined categories.

## Dataset Information and Preprocessing Steps
This project uses a dataset containing labeled audio samples for various spoken commands. Each audio file represents a single spoken command, and these are divided into categories such as "yes," "no," "up," "down," and other basic instructions.

### Preprocessing Steps:
1. **Loading and Resampling**: Audio files are loaded and resampled to a consistent frequency to standardize input.
2. **Feature Extraction**: Audio features, such as Mel-frequency cepstral coefficients (MFCCs), are extracted to provide the model with meaningful patterns in the audio.
3. **Normalization**: The extracted features are normalized to ensure uniformity across the dataset and to aid the model's performance.
4. **Splitting**: The dataset is split into training, validation, and test sets to allow for model evaluation and avoid overfitting.

## Instructions for Viewing the Code
You can access and run this notebook directly on Kaggle, which offers a more streamlined experience without requiring local installation. You can view it here: [Kaggle Notebook - Speech Command Recognition](https://www.kaggle.com/code/fareshazem/notebookb3153ff14a/edit#Define-and-Apply-Data-Augmentation-Functions-for-Audio).

Alternatively, if you prefer running the notebook locally:
1. Clone the repository:
    ```bash
    git clone https://github.com/FaresHazem/Speech-Command-Recognition-using-ANNs
    ```
2. Open the Jupyter Notebook in any environment supporting Jupyter, such as Jupyter Lab or Jupyter Notebook.

## Dependencies
- Jupyter Notebook
- Python 3.7+
- TensorFlow
- NumPy
- Librosa
- Scikit-learn

These dependencies can be installed using:
```bash
pip install tensorflow numpy librosa scikit-learn
```

## Project Structure
- `Speech Command Recognition using ANNs Assignment.ipynb`: Jupyter notebook containing the complete code for preprocessing, training, and evaluating the model.
