
🌱 Plant & Tomato Disease Classification – Deep Learning Project
📌 Project Overview
This project focuses on classifying plant and tomato leaf images to assist in early disease detection using deep learning techniques.
A Convolutional Neural Network (CNN) model was built with TensorFlow/Keras to process image datasets, train models, and evaluate performance.

🎯 Objectives
Preprocess plant and tomato leaf images for model input

Build and train CNN models for image classification

Evaluate model accuracy and visualize results

Provide a foundation for automated plant disease detection systems

🛠 Tools & Technologies
Python

TensorFlow / Keras

NumPy, Pandas

Matplotlib, Seaborn

📂 Repository Structure
bash
Copy
Edit
deep_learning/
│
├── tomato.ipynb       # Training & evaluation for tomato leaf dataset
├── training.ipynb     # Training & evaluation for plant leaf dataset
└── README.md          # Project description
📊 Dataset
Tomato Leaf Dataset: Stored in tomato_image/

Plant Leaf Dataset: Stored in plant_image/

Preprocessed using image_dataset_from_directory for batching & resizing

🚀 Model Workflow
Load Dataset – Images are loaded and resized to 256x256 pixels

Preprocessing – Normalization, shuffling, batching

Model Building – CNN layers with convolution, pooling, dropout

Training – Using Adam optimizer and categorical crossentropy loss

Evaluation & Visualization – Accuracy and loss plots

📈 Results
Achieved high accuracy in classification

Visualizations show clear learning patterns and good model convergence


Edit
jupyter notebook tomato.ipynb
jupyter notebook training.ipynb
Run the cells to retrain or evaluate the models


