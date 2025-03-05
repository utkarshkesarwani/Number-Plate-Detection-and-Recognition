# Vehicle Number Plate Detection and Recognition

## Overview
The **Vehicle Number Plate Detection and Recognition** project utilizes **Support Vector Machine (SVM)**, **Python**, **Scikit-learn**, and **MNIST** to detect and recognize vehicle license plates. This system can be used for traffic monitoring, automated toll collection, and security surveillance.

## Features
- **Image Preprocessing:** Noise reduction, grayscale conversion, and thresholding.
- **License Plate Detection:** Identifies the license plate area in an image.
- **Character Segmentation:** Extracts individual characters from the plate.
- **Character Recognition:** Uses SVM trained on the MNIST dataset to recognize characters.
- **Real-time Processing:** Can be integrated with live camera feeds for real-time detection.
- **Data Logging:** Stores detected license plate numbers for future reference.

## Tech Stack
- **Python**: Primary programming language.
- **OpenCV**: Image processing and plate detection.
- **Scikit-learn**: Machine learning algorithms for character recognition.
- **Support Vector Machine (SVM)**: Classification of characters.
- **MNIST Dataset**: Pre-trained dataset for character recognition.

## Installation Guide
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV
- NumPy
- Scikit-learn

### Setting Up the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Vehicle-Plate-Recognition.git
   cd Vehicle-Plate-Recognition
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Application:**
   ```bash
   python main.py
   ```


## Model Training
1. **Preprocess the Data:** Convert images to grayscale and apply thresholding.
2. **Train the SVM Model:**
   ```bash
   python train_svm.py
   ```
3. **Test the Model:**
   ```bash
   python recognize_characters.py
   ```

## Usage
1. Run the detection script on an image:
   ```bash
   python detect_plate.py --image sample.jpg
   ```
2. Process a video stream:
   ```bash
   python detect_plate.py --video sample.mp4
   ```

