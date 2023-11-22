# Sign Language Digits Translation 🤟🔢

Welcome to the Sign Language Digits Translation project repository! This project is a bridge between technology and communication, translating sign language digits into actionable information.

## Project Overview 🌐

This project utilizes computer vision and machine learning techniques to recognize sign language digits. It involves the use of the MediaPipe library for hand landmark detection and a RandomForestClassifier for digit classification.

## Workflow 🚀

### 1. Data Gathering:

- The dataset used in this project is sourced from [Sign Language Digits Dataset](https://github.com/ardamavi/Sign-Language-Digits-Dataset).
- The dataset captures hand gestures representing digits in sign language.

### 2. Hand Landmark Detection:

- The MediaPipe library is employed for hand landmark detection in the images.
- Landmarks are extracted to represent the spatial coordinates of key points in the hand.

### 3. Model Training:

- The RandomForestClassifier is utilized to train a model for digit classification.
- The model is trained on the extracted hand landmark coordinates.

### 4. Model Evaluation:

- The model is evaluated on a test set, achieving an accuracy of 98.06%.
- A detailed classification report provides insights into precision, recall, and F1-score for each digit.

### 5. Cross-Validation:

- Cross-validation is performed to ensure the model's robustness, yielding high accuracy scores across different folds.

## How to Use 🤖

To use the model for digit translation, follow these steps:

1. Clone the repository: `git clone https://github.com/Aliraqimustafa/Sign-Language-Digits-Translation.git`
2. Clone the Datasets : `git clone https://github.com/ardamavi/Sign-Language-Digits-Dataset.git`
3. Install dependencies: `pip install -r requirements.txt`
4. Run Cells in  `main.ipynb`

## Contribution Guidelines 🤝

Feel inspired to contribute to this project? Follow these guidelines:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure they adhere to existing standards.
4. Add documentation or tests for your changes if applicable.
5. Submit a pull request and let's enhance this project together!

## Dataset Link 📂

Explore the dataset on GitHub: [Sign Language Digits Dataset](https://github.com/ardamavi/Sign-Language-Digits-Dataset)

## Contact 📧

Have questions, ideas, or just want to connect? Reach out:

- Telegram: [Mustafa Mohammad 👥](t.me/ha12qw)
- Facebook: [Mustafa Mohammad 🐦](facebook.com/100049592914479)

Your engagement is crucial! Let's make this project a valuable tool for sign language digit translation. 🤟🔢
