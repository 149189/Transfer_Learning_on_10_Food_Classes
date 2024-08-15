# Transfer_Learning_on_10_Food_Classes
I trained a model to classify images into 10 different food categories using transfer learning. I utilized two powerful pre-trained models as feature extractors: 

***ResNet 50 V2***

![image](https://github.com/user-attachments/assets/546be908-3f6d-407e-9d17-9268afd0e72c)

***EfficientNetB0***.

![image](https://github.com/user-attachments/assets/124e6ecb-280e-495b-ab15-9516c35bc974)

Key Steps:
1. ***Data Preprocessing***: The dataset consisted of 10 food classes, and images were resized and normalized to match the input requirements of the models.
2. ***Transfer Learning***:
   
       1. ResNet 50 V2 was used as a feature extractor, leveraging its deep residual network architecture to capture complex features from the images.
   
       2. EfficientNetB0 was also employed for its efficiency in balancing performance and computational cost, particularly with its scalable architecture.
   
4. ***Model Training***: The extracted features from both models were fed into fully connected layers for classification.
5. ***Evaluation***: Both models were evaluated on the same test dataset to compare their performance.   

![image](https://github.com/user-attachments/assets/ffc36003-9868-4b62-9173-36eec162ef48)
