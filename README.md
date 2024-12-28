Face Recognition System
A practical implementation of face recognition using triplet loss and TensorFlow. This project demonstrates a comprehensive pipeline for training a face recognition model, generating embeddings, and evaluating the system's ability to distinguish between similar and dissimilar faces.

🖥️ Features
-Face Detection and Recognition: Implements face detection using a convolutional neural network 
 architecture.
-Triplet Loss: Optimized for distinguishing embeddings of similar and dissimilar faces.
-Custom Layers: Includes an L2Normalization layer for embedding normalization.
-Efficient Data Handling: Generates triplets on-the-fly and manages memory efficiently.
-GPU Optimization: Configures GPU memory usage to avoid resource exhaustion.
-Evaluation: Tests the system with metrics like accuracy and a confusion matrix.

🏗️ Model Architecture
-Convolutional Layers: Extract features from input images.
-Residual Blocks: Enhance model depth while maintaining gradient flow.
-Global Average Pooling: Reduces the spatial dimensions of feature maps.
-Dense Layers: Learn compact embeddings.
-L2 Normalization: Ensures embeddings are on a unit hypersphere.

🛠 Tech Stack
Programming Languages:
-Python 🐍
Frameworks & Libraries:
-TensorFlow & Keras
-NumPy
-HDF5 (h5py) for data storage
-Matplotlib for visualization
-scikit-learn for evaluation metrics

Triplet Loss Function
The triplet loss ensures that:
-Distance(anchor, positive) < Distance(anchor, negative) + margin

📈 Performance Optimization
Memory-efficient data handling using batch processing and garbage collection.
Customized GPU configuration to prevent memory overflows.
Early stopping to avoid overfitting.

🔗 Connect:

📧 Email: priyadarshinidebamita@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/debamita-priyadarshini-1b7841296/?


