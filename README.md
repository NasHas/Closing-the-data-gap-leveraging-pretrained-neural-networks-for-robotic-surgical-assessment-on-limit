# Transfer-learning-of-pretrained-network-on-limited-clinical-data-Human-Study

Clinical data for action recognition and skills assessment using deep learning. Including public dataset from human robot-assisted surgical procedures.

The codes are open-source. However, when using the code, please make a reference to our paper and repository.

Instructions:

1) Download the video data, labels, and information about the dataset from: https://www.synapse.org/Synapse:syn63852421/wiki/
   2) Use the algorithm, following the steps below: Have all the .py files in one folder, all the videos in another folder, and all the labels in a third folder.
   3) Use 'Publication_main vidoes to frames.py' to split videos into indiviual frames
   4) Use 'Publication_Preprocessing.py' to generate training, validation and test sets.
   5) Use 'Publication_mainTraining_ActionRecognition_LSTM.py' for training your action recognition network.
   6) Use 'Publication_mainTraining_SkillsAssessment_LSTM.py' for training your skills assessment network.
   7) Use 'Publication_mainTesting_ActionRecognition.py' to test your action recognition network.
   8) Use 'Publication_mainTesting_SkillsAssessment.py' to test your skills assessment network.
   9) Use 'Publication_ ActionRecognition_Cross_Validation-HUMAN.py' to do five-fold cross validation for action recognition.
   10) Use 'Publication_Skills Assessment Cross Validation-HUMAN.py'
   11) Use 'Publication_GradCam_DvS.py' to create GradCAM images of your test results (either action recognition or skills assessmnet).
12) Download the 'Datasets and included videos for AC and SA from Hashemi et al 2025 Human study.txt' for information about how our training, validation and test-sets where constructed.

/Hashemi et. al. 2025
