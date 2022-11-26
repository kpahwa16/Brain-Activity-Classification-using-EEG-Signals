# Brain-Activity-Classification-using-EEG-Signals

In this project, we build a Machine Learning model for a Brain-Computer Interface(BCI) system to classify Brain activity from EEG signals. 
We use the BCI Competition IV 2a dataset recorded from nine subjects who performed four Motor Imagery(MI) tasks. We check the viability of
using a model on a subject that was trained on a different set of subjects. We also discuss building individual models optimized for each subject. 
Three main architectures have been explored and compared in detail, namely Convolutional Neural Networks, a hybrid Convolutional Neural Network - 
Long Short Time Memory (CNN-LSTM ) model, and SkipNet architecture that leverages anchored-STFT and an adversarial data augmentation scheme called 
‘Fast Gradient Sign Method’ (FGSM). We achieved 70% accuracy using the CNN model, 71% accuracy using the CNN-LSTM model, and 76% accuracy
using the SkipNet model.
