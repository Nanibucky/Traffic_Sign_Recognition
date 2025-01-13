# Traffic-Sign-Classification-Using-Deep-Learning
## Overview
Traffic sign classification is critical for applications in autonomous vehicles, smart cities, and intelligent transportation systems. This project, Traffic Sign Classification Using Deep Learning, implements a robust Convolutional Neural Network (CNN)-based system to classify traffic signs accurately. Utilizing the German Traffic Sign Recognition Benchmark (GTSRB) dataset, the project showcases the effectiveness of CNNs for real-world image recognition tasks.

# Features
Data Preprocessing:
Resized images to multiple resolutions for analysis (30x30 and 60x60 pixels).
Applied augmentation techniques such as rotation, translation, and normalization to improve generalization.
Model Development:
Designed and trained a custom CNN architecture with multiple layers optimized for the GTSRB dataset.
Experimented with various configurations, including the number of layers, nodes, and preprocessing strategies.
Model Evaluation:
Used accuracy, precision, recall, and F1-score to evaluate model performance.
Visualized results with confusion matrices to identify misclassified traffic sign classes.
Exploration of YOLO:
Studied real-time object detection using the YOLO algorithm but focused primarily on classification using CNN.
# Dataset
The German Traffic Sign Recognition Benchmark (GTSRB) dataset is a comprehensive collection of traffic sign images:

Total Images: 50,000+ across 43 classes.
Data Splits: 80% training, 10% validation, 10% testing.
Characteristics: Images captured under varying lighting, weather, and viewing angles.
Classes: Includes stop signs, speed limits, yield signs, and pedestrian crossings.
# Steps Completed
Data Preprocessing:
Resized images to 30x30 and 60x60 pixels.
Normalized pixel values for stability during training.
Applied data augmentation techniques to enhance dataset diversity.
Model Development:
Built a CNN model tailored to the GTSRB dataset using Keras.
Experimented with architectures by varying layers and hyperparameters.
Evaluation:
Compared performance metrics across configurations.
Fine-tuned the model using data augmentation for improved accuracy.
# Results
The final CNN model achieved a high classification accuracy with consistent performance across validation and testing datasets.
Key Insights:
Larger image sizes (60x60 pixels) captured finer details, improving recognition.
Data augmentation reduced overfitting and increased robustness.
# Challenges and Learnings
Balancing model complexity to avoid overfitting while achieving high accuracy.
Experimenting with YOLO highlighted the real-time detection potential but reinforced CNN's suitability for classification.
Preprocessing and augmentation were critical for handling variability in the dataset.
# Future Scope
Integrate YOLO for real-time traffic sign detection.
Explore transfer learning to enhance model efficiency.
Extend the system to incorporate multi-modal data such as LIDAR or radar for improved robustness.
Investigate advanced architectures, such as attention-based CNNs or graph neural networks.
