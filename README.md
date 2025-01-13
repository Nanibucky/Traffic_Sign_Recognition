# Traffic-Sign-Classification-Using-Deep-Learning
## Overview
Traffic sign classification plays a crucial role in autonomous vehicles, smart cities, and intelligent transportation systems. This project implements a robust Convolutional Neural Network (CNN) to accurately classify traffic signs using the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The project highlights the effectiveness of CNNs for real-world image recognition tasks, demonstrating their potential for critical applications.

# Features
# Data Preprocessing:

Resized images to multiple resolutions (30x30 and 60x60 pixels).
Applied augmentation techniques (rotation, translation, and normalization) to improve generalization.
#Model Development:

Designed and trained a custom CNN architecture optimized for the GTSRB dataset.
Experimented with various configurations, including layer count, node sizes, and preprocessing strategies.
# Model Evaluation:

Evaluated performance using metrics like accuracy, precision, recall, and F1-score.
Visualized misclassified traffic sign classes using confusion matrices.
Exploration of YOLO:

Investigated real-time object detection using YOLO but focused primarily on CNN-based classification.
Dataset
The GTSRB dataset is a comprehensive traffic sign image collection, ideal for classification tasks:

Total Images: 50,000+ across 43 classes.
Data Splits: 80% training, 10% validation, 10% testing.
Characteristics: Varying lighting, weather, and viewing angles.
Classes: Includes stop signs, speed limits, yield signs, and pedestrian crossings.
Steps Completed
# Data Preprocessing:

Resized images to 30x30 and 60x60 pixels.
Normalized pixel values for stable training.
Applied data augmentation to enhance dataset diversity.
# Model Development:

Built a CNN tailored to the GTSRB dataset using Keras.
Experimented with different architectures by varying layers and hyperparameters.
# Evaluation:

Assessed performance across configurations.
Fine-tuned the model using augmented data for improved accuracy.
# Results
The final CNN model achieved high classification accuracy, with consistent performance on validation and testing datasets.

# Key Insights:

Larger image resolutions (60x60 pixels) improved recognition by capturing finer details.
Data augmentation reduced overfitting and enhanced model robustness.
# Challenges and Learnings
Balancing model complexity to prevent overfitting while maintaining high accuracy.
YOLO exploration highlighted real-time detection potential, but CNN proved more suitable for classification tasks.
Preprocessing and augmentation were essential to handle dataset variability.
# Future Scope
Integrate YOLO for real-time traffic sign detection./
Explore transfer learning to improve model efficiency.
Extend the system with multi-modal data (e.g., LIDAR, radar) for greater robustness.
Investigate advanced architectures like attention-based CNNs or graph neural networks.
