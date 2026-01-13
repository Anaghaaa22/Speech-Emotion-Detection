# Speech Emotion Detection

## Project Overview
This project focuses on detecting human emotions from speech signals using machine learning techniques.  
The system analyzes audio features extracted from speech samples and classifies them into different emotional categories such as happy, sad, angry, neutral, and others.

The project was developed and executed using Google Colab.

---

## Objectives
- To extract meaningful audio features from speech data
- To train a machine learning model capable of classifying emotions
- To analyze and visualize speech emotion patterns
- To evaluate model performance on speech emotion datasets

---

## Technologies and Tools Used
- Python
- Google Colab
- Librosa
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## Dataset
The project uses speech emotion audio files for training and testing.

Additional and larger speech emotion datasets can be downloaded from Kaggle, such as:
- RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
- TESS (Toronto Emotional Speech Set)
- SAVEE (Surrey Audio-Visual Expressed Emotion)

Kaggle link for datasets:
https://www.kaggle.com/datasets

Due to size constraints, datasets are not included in this repository.

---

## Files in the Repository
- `Speech_Emotion_Detection.ipynb`  
  Contains the complete implementation including data preprocessing, feature extraction, model training, evaluation, and result visualization.

---

## Methodology
1. Audio files are loaded and preprocessed
2. Feature extraction is performed using MFCCs and other spectral features
3. Extracted features are used to train machine learning classifiers
4. Model predictions are evaluated using appropriate metrics
5. Results are visualized for better interpretation

---

## How to Run the Project
1. Download or clone this repository
2. Open the notebook in Google Colab or Jupyter Notebook
3. Install the required dependencies
4. Upload or link the dataset
5. Run all cells sequentially

---

## Results
The model is capable of identifying emotions from speech with reasonable accuracy depending on the dataset and feature set used.

---

## Future Enhancements
- Use deep learning models such as CNN or LSTM
- Improve accuracy with larger and more diverse datasets
- Implement real-time speech emotion detection
- Deploy the model as a web application

---

## Author
Anagha Bhattad
