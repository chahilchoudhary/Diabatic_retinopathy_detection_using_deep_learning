# Diabatic_retinopathy_detection_using_deep_learning

Overview
Diabetic Retinopathy (DR) is a severe complication that can affect individuals with diabetes. Early detection and treatment are critical to prevent blindness. This project leverages the capabilities of Deep Learning and Transfer Learning to automatically detect and classify the stages of DR from retinal images.

Dataset
The dataset comprises retinal images, annotated according to the severity of diabetic retinopathy:

No DR
Mild
Moderate
Severe
Proliferative DR
Each image has been labeled by expert ophthalmologists, ensuring the quality and reliability of the training data.

Methodology
Data Augmentation: Given the limited number of retinal images in each category, data augmentation techniques have been employed to artificially increase the dataset's size, enhancing the model's generalization capability.

Transfer Learning: Instead of building a deep learning model from scratch, we've utilized pre-trained models (e.g., VGG16, ResNet, InceptionV3) and fine-tuned them for our specific task. This approach capitalizes on the knowledge these models have gained from extensive training on large datasets.

Model Training: The fine-tuned models have been trained on our retinal image dataset to classify the severity of DR.

Evaluation: The performance of the models is assessed using metrics such as accuracy, precision, recall, and F1-score. A confusion matrix has also been used to understand the models' classification capabilities in detail.

Deployment: The best-performing model has been integrated into a user-friendly web application, enabling clinicians and researchers to upload retinal images and receive immediate predictions.
