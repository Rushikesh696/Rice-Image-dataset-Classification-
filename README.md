# Rice-Image-dataset-Classification-
## Problem Statement
- This project aims to develop an automated image classification system to identify different 
rice grain types using deep learning. A Convolutional Neural Network (CNN) with transfer 
learning will be used to leverage pre-trained features for accurate classification. The model 
will be trained on a labeled dataset and evaluated using metrics like accuracy, precision, 
recall, and F1-score. Hyperparameter tuning will be performed to optimize performance. A 
simple user interface will allow users to upload images and receive rice type predictions.

 ## Objectives
• To develop an image classification model using CNN and transfer learning for rice grain 
identification.
• To utilize a pre-trained model (e.g., MobileNetV2) for feature extraction and fine-tune it on 
the rice grain dataset.
• To evaluate the model using performance metrics such as accuracy, precision, recall, and 
F1-score.
• To apply hyperparameter tuning techniques to improve model performance.
• To design a user-friendly interface that allows users to upload rice grain images and receive 
predictions.

## Conclusion
• The rice grain classification model built using transfer learning with MobileNetV2 achieved 
excellent results, demonstrating its effectiveness in accurately identifying different rice varieties. With a test accuracy of 98.6%, a low loss of 0.0456, and a weighted F1-score of 0.99, 
the model shows exceptional generalization and minimal misclassification across all five rice 
classes. The confusion matrix confirms the model’s robustness in distinguishing between Arborio, Basmati, Ipsala, Jasmine, and Karacadag. Loading the dataset using TensorFlow’s 
image_dataset_from_directory function ensured accurate class labeling, crucial for prediction mapping. The system also includes a function to predict and display the class of a single 
image with high confidence. Overall, the model proves to be a reliable and efficient solution 
for automated rice grain classification.
