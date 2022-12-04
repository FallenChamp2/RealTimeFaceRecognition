# RealTimeFaceRecognition

Description :

 This project detects in real time whether a person is wearing a mask or not using laptop's webcam.

Languages and libraries:

 This project uses python3, tensorflow, keras, PIL, numpy, pandas, os.listdir in kaggle jupyter notebook environment.

Dataset :

 Dataset contained images of masked and non masked people divided into three folders - Train, Validation, Validation.
 Using tensorflow 224x224 sized images were loaded having 3 channels-RGB.

Models used :

 1. Pre-trained ResNet50 model followed by a dense layer for classification was used for the training, validation and testing stage.
 2. HaarCascade frontal face alt_ 2 pre-trained model was used to capture real time face for detection of mask.
 3. One code used facnet pre-trained model followed by linear SVC but real time detection was not done using this code.
