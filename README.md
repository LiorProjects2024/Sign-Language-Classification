Sign Language Letter Recognition Project using QDA Model

Overview
This project implements a Quadratic Discriminant Analysis (QDA) model to classify images of hand gestures representing letters in sign language. By leveraging a dataset of approximately 35,000 images, the project aims to identify letters from the American Sign Language alphabet with high accuracy.

Problem Statement
Automatically recognizing these gestures through machine learning can bridge communication gaps between deaf and hearing individuals. However, challenges such as image variation, noise, and complex background data complicate this task.

Dataset
The dataset contains images representing the letters A-Z. Each image corresponds to a unique hand gesture representing a single letter. The images were divided into training and testing sets to evaluate the model's performance.
Training Data: Consists of labeled images used to train the QDA model.
Testing Data: Used to evaluate the model's accuracy.

Model Selection:
Quadratic Discriminant Analysis (QDA) was chosen for its effectiveness in handling data that follows a Gaussian distribution. The QDA model is well-suited for cases where the variance of each class is different, which is crucial for distinguishing between hand gestures with subtle differences.

Training:
The training process involved fitting the QDA model to the dataset of ASL letters. The model learned the decision boundaries for each class based on the covariance and mean of each letter's image features.
Testing:
The trained model was tested on unseen data to evaluate its performance. Metrics such as accuracy, precision, and recall were used to assess the effectiveness of the model in recognizing the correct letters.

Results
The QDA model achieved an accuracy of 92% on the test dataset. This result demonstrates the model's capability to handle image classification tasks effectively, even without advanced preprocessing or augmentation techniques.
Key Learnings

QDA Performance: Despite its simplicity, the QDA model performed well in this image classification task. This demonstrates the model’s effectiveness in handling problems where data is well-separated by quadratic boundaries.
Challenges: Some classes, particularly those representing similar hand gestures, posed classification challenges, which could be addressed by further refining the feature extraction process or experimenting with other machine learning models.
