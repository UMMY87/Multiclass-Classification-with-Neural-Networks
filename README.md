# Multiclass Classification with Neural Networks

This code snippet demonstrates building and training a neural network for multiclass classification using TensorFlow and Keras. Below is a breakdown of its components:

## 1. Imports
The code imports necessary libraries for various operations:
- **NumPy**: For numerical operations.
- **Matplotlib**: For plotting.
- **scikit-learn**: For generating synthetic data.
- **TensorFlow and Keras**: For building and training neural networks.

## 2. Dataset Generation
A synthetic dataset with four classes is generated using scikit-learn's `make_blobs` function. The dataset comprises 100 samples with four clusters centered at predefined coordinates.

## 3. Model Definition
A neural network model is defined using the Sequential API from Keras. It comprises two fully connected layers (`Dense` layers) with ReLU activation for the first layer and linear activation for the output layer.

## 4. Model Compilation
The model is compiled with appropriate loss function (`SparseCategoricalCrossentropy`) and optimizer (`Adam`) for multiclass classification.

## 5. Model Training
The model is trained on the generated dataset (`X_train` and `y_train`) using the `fit` method.

## 6. Visualization
Various plots are generated after training to visualize the model's behavior and learnings. This includes visualizing the data, decision boundaries, the activation function of the first layer (ReLU), and the output layer.

- **Plot Multi-class Data**

![Plot-Multiclass-Data](https://github.com/UMMY87/Multiclass-Classification-with-Neural-Networks/assets/117314436/9cbe7e6a-c104-42bc-8357-07e0498e59c8)

- **Plot Multi-class Decision Boundary**

![Plot-Multiclass-Decision-Boundary](https://github.com/UMMY87/Multiclass-Classification-with-Neural-Networks/assets/117314436/8150192b-ac9f-4370-98d3-5948fdbb8151)

- **Plot the function of first layer**

![Plot-the-function-of-first-layer](https://github.com/UMMY87/Multiclass-Classification-with-Neural-Networks/assets/117314436/c94e1549-30c4-4dfe-829d-b14edf6a1c74)

- **Plot Output layer**

![Plot-Output-layer](https://github.com/UMMY87/Multiclass-Classification-with-Neural-Networks/assets/117314436/df5c8c1b-ded6-48ea-b29e-d48982dc5c60)

## 7. Analysis
Insights into how the neural network learns to classify the data are provided by examining the parameters of each layer and visualizing their effects on the data.

Understanding and implementing neural networks for classification tasks is crucial in various fields such as machine learning, pattern recognition, and data analysis. It enables automated learning and decision-making based on data patterns, facilitating tasks such as image recognition, natural language processing, and predictive analytics. This code serves as a foundational example for building and understanding neural networks for classification tasks.
