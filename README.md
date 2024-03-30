# CodeAlpha_Emotion_Recognition_from_Speech

## Overview:

Excited to announce the completion of task 2 during my CodeAlpha Machine Learning Internship! In this task, I embarked on a journey to build a cutting-edge model capable of recognizing emotions in speech audio. Harnessing the power of deep learning and advanced speech processing techniques, the goal was to classify spoken sentences into a spectrum of emotions, from the jubilant tones of happiness to the fiery depths of anger or the somber echoes of sadness.

## Dataset:

For this endeavor, I leveraged the formidable SAVEE (Surrey Audio-Visual Expressed Emotion) dataset, a treasure trove of audio recordings encapsulating a diverse range of emotional expressions.

## Approach:

1. **Data Augmentation:** As the first step towards unleashing the potential of our model, I delved into the realm of data augmentation. Through clever manipulations such as injecting noise, shifting time, and altering pitch and speed, we synthesized a rich tapestry of data, imbuing our model with the resilience and adaptability needed to thrive in the face of real-world variability.

2. **Feature Extraction:** With the stage set, it was time to extract the essence of emotion from the audio data. We meticulously captured the nuances of each utterance through features such as:
   - Zero Crossing Rate: Capturing the dynamics of waveform changes.
   - Chroma_stft: Unveiling the harmonic structure of sound.
   - MFCC (Mel Frequency Cepstral Coefficients): Unlocking the spectral characteristics of speech.
   - RMS (Root Mean Square) value: Gauging the intensity of sound.
   - MelSpectogram: Revealing the frequency content of audio signals.

3. **Data Preprocessing:** Armed with a treasure trove of features, we embarked on the journey of data preprocessing. One-Hot encoding transformed our target variable into a format ready for the rigors of model training. The data was then meticulously split into train and test sets, with additional preprocessing steps ensuring harmonious compatibility with our model's architecture.

4. **Model Building:** The crowning jewel of our endeavor was the creation of a bespoke Keras Sequential deep-learning model. This architectural marvel was meticulously crafted to navigate the complexities of emotion recognition, its layers intricately woven to distill the essence of emotional expression from raw audio inputs.

5. **Model Evaluation:** With bated breath, we unleashed our creation upon the data, witnessing its prowess as it gracefully danced through the task of emotion recognition. The model's accuracy stood at an impressive 63%, a testament to its ability to decipher the language of emotion concealed within spoken words.

## Future Improvements:

As we gaze towards the horizon, there are endless possibilities for further enhancing our model's capabilities. The journey towards greater accuracy and robustness beckons, promising untold discoveries and breakthroughs. Potential avenues for improvement include:
- Expansion of the training set to encompass a broader spectrum of emotional expressions.
- Exploration of novel augmentation techniques to enrich the diversity of our data.
- Investigation into alternative feature extraction methodologies to unearth hidden insights within the audio domain.

## Credits:

This project drew inspiration from the illustrious Kaggle notebook available [here](https://www.kaggle.com/code/shivamburnwal/speech-emotion-recognition/notebook), serving as a guiding light on our quest for excellence.

Join me in celebrating this milestone in our quest to decode the language of emotion and usher in a future where machines resonate with human sentiment, enriching lives and forging deeper connections in the process.
