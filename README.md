# Digit Recognition with Machine Learning

## Overview
This project demonstrates a digit recognition system using machine learning. The application features a virtual blackboard where users can draw digits, and the system will recognize and output the digit drawn.

## Features
- **Digit Recognition**: Recognizes digits (0-9) drawn on a virtual blackboard.
- **Machine Learning Model**: Utilizes a pre-trained Convolutional Neural Network (CNN) model.
- **Interactive Drawing Board**: Users can draw digits on a desktop-based blackboard interface.

![image](https://github.com/zvoicu000/Digit-Recognition/assets/130836504/13114570-7b29-4a1d-a7c5-c63da5f98d69)


## Technologies Used
- **Python**: Main programming language for model training and application logic.
- **TensorFlow/Keras**: For building and training the machine learning model.
- **OpenCV**: For image preprocessing.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.10+
- pip (Python package installer)
- Virtual environment (optional but recommended)

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/zvoicu000/Digit-Recognition.git
    cd digit-recognition-app
    ```

2. **Create a virtual environment (optional but recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

### Running the Application

1. **Start the application:**
    ```sh
    python app.py
    ```
