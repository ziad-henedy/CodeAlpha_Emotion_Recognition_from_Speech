# CodeAlpha_Emotion_Recognition_from_Speech
Happy to share that I completed task 2 of the CodeAlpha Machine Learning Internship.



In this task I was required to build a model that can recognize emotions in speech audio using deep learning and speech processing

techniques to classify spoken sentences into different

emotions like happiness, anger, or sadness.



In this model, I used the SAVEE(Surrey Audio-Visual Expressed Emotion) dataset, which can be found here: https://www.kaggle.com/datasets/barelydedicated/savee-database/code



The first step after loading the data is Data Augmentation, which is the process by which we make new synthetic data by making small perturbation and alterations to the data such as injecting noise, shifting time, changing pitch and speed.



The objective is to make the model invariant to those perturbations and enhance its ability to generalize.



After this process is complete, we begin to extract features from the data.



Data provided by the audio samples cannot be directly fed into the model, therefore we need to extract some measurable features so that the model can be trained.



Features extracted are:



 Zero Crossing Rate 

Chroma_stft,  

MFCC Mel Frequency Cepstral Coefficients, 

RMS(root mean square) value, 

MelSpectogram



Next we need to One-Hot encode our y variable to be used in the model, split into train and test, further preprocessing to make our data compatible with the model.



The model of choice is Keras Sequential deep-learning model. 



After fitting the model with the data, we form a prediction.



The Accuracy of the model was 63%.



This can be improved by increasing the size of the training set, applying more augmentation techniques and using other feature extraction methods.



This was guided by the Kaggle notebook at: https://www.kaggle.com/code/shivamburnwal/speech-emotion-recognition/notebook



#machinelearning #CodeAlpha #deeplearning
