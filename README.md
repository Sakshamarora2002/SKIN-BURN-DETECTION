Skin Burn Classification Project
Overview
This project aims to develop a machine learning model for accurately classifying degrees of skin burns using image data. Traditional diagnostic methods often rely on subjective assessments, leading to inconsistencies and delays in treatment. Leveraging machine learning algorithms, our goal is to provide a reliable and objective assessment tool for medical professionals.

Problem Statement
Accurate classification of skin burns is crucial for determining appropriate treatment and improving patient outcomes. Traditional methods are often subjective, resulting in inaccuracies and delays in care. Our challenge is to develop a system that can objectively classify the degree of skin burns, mitigating these shortcomings.

Solution Overview
Our solution involves using machine learning techniques to analyze extensive datasets of burn images. By training our model on historical data, it learns to differentiate between first-degree, second-degree, and third-degree burns. We employ various algorithms, including Simple Neural Networks, Convolutional Neural Networks (CNNs), and pre-trained models like VGG16 and InceptionV3, to achieve this.

Algorithms Used
Simple Neural Network: Baseline model for burn classification.
Convolutional Neural Network (CNN): Captures spatial hierarchies in images.
VGG16 Pre-trained Model: Leverages knowledge from a large dataset via transfer learning.
InceptionV3 Pre-trained Model: Explores another pre-trained model architecture for robustness.
General Considerations
Data Augmentation: Increase dataset diversity to prevent overfitting.
Evaluation: Assess model performance using standard metrics.
Visualization: Plot training and validation metrics to assess convergence.
Comparison and Selection: Compare model performance to select the most effective one.
Usage
Ensure you have the necessary dependencies installed (e.g., TensorFlow, Keras).
Prepare your dataset of burn images.
Train and evaluate different models using the provided scripts.
Compare model performance and select the best-performing one for your task.
Contributors
Saksham Arora
Tanya 
