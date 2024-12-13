# American Sign Language (ASL) Alphabet Recognition Project

## Overview

This project is designed to recognize American Sign Language (ASL) alphabet gestures in real-time using computer vision and machine learning. By utilizing OpenCV for webcam integration, MediaPipe for hand tracking, and classifiers like Support Vector Machine (SVM) and Random Forest, the model can accurately identify ASL hand gestures and convert them into corresponding alphabetic characters.

![Project Demo](./Sign_Language_Detection-main\Gui.png")

## Features

- **Real-time ASL Alphabet Detection:** Utilizes OpenCV and MediaPipe for live hand gesture detection via webcam.
- **Machine Learning Models:** Employs SVM and Random Forest classifiers to predict ASL letters based on hand gesture data.
- **Tkinter Interface:** A simple GUI is implemented using Tkinter to display predicted text and control functionalities.
- **Custom Labels:** Detects and outputs specific ASL hand gestures for the English alphabet (A-Z), numbers (0-9), and some basic words like "Hello," "Thanks," etc.

## Prerequisites

Before running this project, make sure you have the following installed on your system:

1. **Python 3.13.0** or higher
2. **pip** - Python package manager

To install `pip`, follow these steps:
1. **Windows:**
   ```bash
   python -m ensurepip --upgrade
   ```

2. **Linux/MacOS:**
   ```bash
   sudo apt install python3-pip
   ```

### Required Libraries

The following Python libraries are required to run this project:

- `opencv-python`
- `mediapipe`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `Pillow`
- `tkinter`
- `pickle`
- `mlflow`
- `flask`

You can install these dependencies by running the following command:

```bash
pip install opencv-python mediapipe numpy scikit-learn matplotlib Pillow mlflow flask
```

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ASL_Alphabet_Recognition.git
   ```

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python Real_Time.ipynb
   ```

## Usage

1. **Run the Application**: Launch the `Real_Time.ipynb` script to begin real-time ASL alphabet detection.
2. **Webcam Integration**: Once the webcam is activated, hold up ASL gestures in front of the camera, and the recognized character will appear on the GUI interface.
3. **Text Interaction**: The recognized gestures will be automatically converted into alphabetic characters and displayed in the Tkinter window.

## Model Training

The model was trained using a combination of hand-tracking data and gesture classification techniques. Features extracted from hand landmarks were passed to SVM and Random Forest classifiers to detect the corresponding ASL letter.

## Future Enhancements

- **Word Formation:** Implementing Generative Adversarial Networks (GANs) to predict entire words from ASL gestures.
- **Deployment on Cloud**: Utilizing Azure services to deploy and scale the system for real-time usage.
- **Recommendation System**: Adding a personalized interaction system to suggest words or phrases based on previous interactions.

## Contributions

Contributions to this project are welcome. Feel free to submit a pull request or report issues.

