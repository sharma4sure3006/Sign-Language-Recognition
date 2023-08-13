# Sign-Language-Recognition

The Sign Language Detection Project is an advanced machine learning and computer vision application that aims to recognize and interpret hand gestures to convert them into corresponding textual representations of sign language. This project has been developed to bridge the communication gap between the hearing-impaired and others by enabling real-time sign language translation.

The system utilizes state-of-the-art deep learning techniques and the power of Mediapipe and OpenCV libraries to accurately detect hand gestures and translate them into sign language phrases. The project uses a pre-trained deep learning model, which has been fine-tuned on a custom dataset generated for sign language recognition.

# Features
* **Real-time hand gesture recognition:** The application can interpret hand gestures in real-time, enabling seamless communication between sign language users and others.
* **Multi-language support:** The system supports multiple sign languages, making it versatile and applicable to various regions and communities.
* **High accuracy and performance:** The deep learning model achieves a high accuracy rate of over 95%, ensuring reliable and precise translation of hand gestures.
* **Simple and intuitive user interface:** The user interface is designed to be user-friendly, allowing users to easily interact with the application and see the translated sign language phrases.

This project serves as an essential tool for promoting inclusivity and accessibility, allowing sign language users to communicate effortlessly with people who may not be familiar with sign languages. Whether it's in educational, medical, or daily communication scenarios, the Sign Language Detection Project offers a powerful solution to enhance interaction and understanding for all individuals.

# Getting Started

## Prerequisites
* Python 3.6+
* OpenCV
* Tensorflow
* Keras
* Mediapipe

## Installation

1. Clone the repository:
   git clone https://github.com/sharma4sure3006/sign-language-detection.git

2. Install the required dependencies:
   pip install -r requirements.txt

# Usage

1. Run the main application:
   python app.py

2. The application will open up a webcam window, and you can start performing hand gestures in front of the camera to see the real-time recognition.

# Model Training

If you want to train the model on your custom dataset or improve the recognition accuracy, you can follow these steps:

1. Prepare your custom dataset and organize it into separate folders for each gesture category.

2. Use the collectdata.py script to capture and save the training data.

3. Run the trainmodel.py script to train the deep learning model on your dataset.

4. Update the model weights and architecture in the app.py file if you make changes to the model.

# Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or create a pull request.

# Contact
If you have any questions or want to get in touch, feel free to contact me:

Email: aloksh3006@gmail.com
LinkedIn: https://www.linkedin.com/in/alok-sharma-73a660237/
GitHub: https://github.com/sharma4sure3006
