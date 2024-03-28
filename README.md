# Flower Recognition System

This project aims to develop a flower recognition system using convolutional neural networks (CNNs). The system can identify the type of flower from an input image and display its common name, family name, and major uses.

## Methodology

### Data Preprocessing
- The system is trained on a dataset of flower images with corresponding labels.
- Input images are resized for efficient processing.
- Data augmentation techniques like rotation and shear are applied to increase the dataset size and improve model performance.

### Model Architecture
- A convolutional neural network (CNN) is used for image classification.
- The CNN model consists of a stack of layers, including convolutional layers, ReLU activation layers, pooling layers, and fully connected layers.
- The model is trained over 150 epochs with a batch size of 32.
- During training, the model learns to extract features and patterns from the input images, starting with simple features and gradually progressing to more detailed ones.

### Loss Function and Optimization
- Categorical cross-entropy is used as the loss function.
- Initially, the loss values are high, but as training progresses, the weight values are adjusted to minimize the loss function.

## Deployment
- The trained model is deployed as a web application for user convenience.
- Users can upload an image of a flower through the web interface.
- Upon clicking the "Predict" button, the model processes the input image and predicts the flower type.
- The common name, family name, and major uses of the identified flower are displayed to the user.

## Usage
1. Clone the repository or download the project files.
2. Install the required dependencies (e.g., Python, TensorFlow, Flask).
3. Run the web application.
4. Access the application through a web browser.
5. Upload an image of a flower.
6. Click the "Predict" button.
7. View the predicted flower information, including common name, family name, and major uses.

## Contributing
Contributions to the project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- List any third-party libraries, datasets, or resources used in the project.
- Acknowledge any contributors or sources of inspiration.
