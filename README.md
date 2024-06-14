# Sign Language Recognizer

This project translate Indian sign language alphabets into text using Long Short-Term Memory (LSTM) networks. The system collects data in the form of images for each alphabet using OpenCV, preprocesses the images, trains an LSTM model, and then recognizes sign language gestures in real-time.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Collection](#data-collection)
- [Model Training](#model-training)
- [Real-Time Recognition](#real-time-recognition)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sign language is a crucial means of communication for many individuals with hearing and speech impairments. This project leverages deep learning techniques to bridge communication gaps by recognizing and translating sign language alphabets into text.

## Features

- **Data Collection**: Capture images of sign language alphabets using OpenCV.
- **Preprocessing**: Prepare images for training by normalization and feature extraction.
- **Model Training**: Train an LSTM-based neural network to recognize sign language alphabets.
- **Real-Time Recognition**: Recognize and translate sign language gestures in real-time through a user-friendly interface.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/sign-language-recognition-lstm.git
    cd sign-language-recognition-lstm
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Data Collection

1. Run the data collection script to capture images of sign language alphabets:
    ```bash
    python collect_data.py
    ```

2. Follow the on-screen instructions to capture images for each alphabet.

### Model Training

1. Preprocess the collected images and train the LSTM model:
    ```bash
    python train_model.py
    ```

2. The trained model will be saved for later use.

### Real-Time Recognition

1. Run the real-time recognition script to start translating sign language gestures:
    ```bash
    python recognize_gestures.py
    ```

2. Use the interface to perform sign language gestures in front of your camera and see the translations.

## Technologies Used

- **Programming Languages**: Python
- **Libraries**: TensorFlow, Keras, OpenCV, NumPy, pandas
- **Tools**: Visual Studio Code
- **Hardware**: Webcam for capturing images, GPU for training the model

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
