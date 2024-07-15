# Potato Disease Classification

Farmers every year face economic loss and crop waste due to various diseases in potato crops. Potato crops are highly susceptible to various diseases that can cause significant yield losses and compromise crop quality. Early and accurate identification of these diseases is crucial for timely intervention and effective crop management.

This project aims to develop a robust and efficient system that can automatically classify potato leaf diseases based on images of affected plants. We propose a deep learning-based approach for potato leaf disease classification, leveraging convolutional neural networks (CNNs) to enhance crop health monitoring and enable proactive disease management. The system is designed as a web-based application, enabling easy access and usability for end-users.

## Features

1. **Dataset Preparation**:
    - Compiled a diverse dataset of potato plant images, including healthy and diseased states.
    - Preprocessed the data to enhance model performance.

2. **Deep Learning Model**:
    - Developed a CNN-based model to classify potato diseases.
    - Trained the model using the prepared dataset.

3. **React Interface**:
    - Created a user-friendly React interface for easy interaction.
    - Integrated the trained model for real-time disease classification.

4. **Real-time Classification**:
    - Enabled users to upload potato plant images for instant disease identification.

## Technologies Used

### Frontend

- **React**: JavaScript library for building user interfaces
- **Axios**: Promise-based HTTP client for making requests to the backend

### Backend

- **Flask**: Python web framework for building the API
- **TensorFlow/Keras**: Deep learning frameworks used to build and train the CNN model

### Deep Learning Approach

- **Deep Learning**: Utilized for developing the disease classification model.
- **Convolutional Neural Networks (CNNs)**: Employed for model prediction to accurately classify potato diseases based on images.


