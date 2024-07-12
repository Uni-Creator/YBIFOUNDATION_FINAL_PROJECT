# Handwritten Digit Recognition with Random Forest Classifier

This project demonstrates the implementation of a handwritten digit recognition system using the Random Forest algorithm. It uses the digits dataset from sklearn, which contains images of handwritten digits (0-9) represented as 8x8 pixel arrays.

## Project Structure

- **digit_recognition.py**: Python script containing the code for data loading, preprocessing, model training, and evaluation.
- **README.md**: This file, providing an overview of the project.
- **requirements.txt**: Lists the required Python libraries for this project.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/digit-recognition.git
   cd digit-recognition
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script:**
   ```bash
   python digit_recognition.py
   ```

## How it Works

- **Data Loading:** Loads the digits dataset using sklearn's `load_digits` function.
- **Data Preprocessing:** Reshapes the images into flattened arrays and normalizes pixel values to enhance model performance.
- **Model Training:** Splits the dataset into training and testing sets, then trains a Random Forest classifier on the training data.
- **Model Evaluation:** Predicts labels for the test data and evaluates performance using metrics like accuracy, confusion matrix, and classification report.

## Why it's Useful

This project serves as a practical introduction to machine learning workflows, covering data loading, preprocessing, model training, and evaluation. It helps in understanding how to manipulate data, build machine learning models, and assess their performance using standard metrics. By running and exploring this project, you can gain hands-on experience in digit recognition and deepen your skills in Python programming and machine learning concepts.
