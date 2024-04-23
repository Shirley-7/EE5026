EE5026 Assignment: Face Recognition

#### Overview

For the course project, I constructed a face recognition system. 
I applied Principal Component Analysis (PCA) to perform data dimensionality reduction and visualization, to understand underlying data distribution. 
Then I train and apply three classification models, including Linear Discriminative Analysis (LDA), Support Vector Machine (SVM), and Convolutional Neural Networks (CNN), to classify the face images, and one clustering model – Gaussian Mixture Model (GMM) – to group the face images. 

#### Programming Language
Python

#### Project Structure
myenv/
│
├── pie (dataset)
├── data_processing.ipynb
├── PCA.ipynb
├── LDA.ipynb
├── SVM.ipynb
├── CNN.ipynb
├── (report)
├── appendix
└── README.md

#### Instructions
1. Data processing: 
Download the CMU PIE training set and include my own photos in the dataset.
2. Run PCA:
Execute main.py with PCA configuration to reduce dimensionality, and visualize the projected data in 2D and 3D plots.
Report classification accuracy using the nearest neighbor classifier.
3. Run LDA:
Execute main.py with LDA configuration to reduce dimensionality and visualize data distribution in 2D and 3D.
Report classification accuracy using nearest neighbor classifier.
4. Run SVM:
Execute main.py with SVM configuration to classify face images and try different values of the penalty parameter C.
Report classification accuracy for each parameter and dimensionality.
5. Run CNN:
Train the CNN using the provided architecture and report the final classification performance.

#### Results
A report including visualizations, accuracy reports and introduction of them.
Discuss the insights gained from the experiments, the impact of different techniques, and any challenges encountered during the project.

#### Contributors
QI SHUOLI


