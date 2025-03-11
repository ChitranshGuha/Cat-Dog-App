# Cat & Dog Classifier App

This project is an Android application that classifies images of cats and dogs using a machine learning model trained with TensorFlow. The app allows users to upload an image, and it predicts whether the image contains a cat or a dog, displaying the confidence percentage.

## Features
- Upload an image from your device
- Get a prediction with confidence percentage
- Uses a TensorFlow Lite model for fast on-device inference

## Technologies Used
- **TensorFlow & Keras**: Model training in Google Colab
- **Android Studio**: App development
- **TensorFlow Lite**: Model optimization for mobile devices
- **GitHub**: Version control and code storage

## Installation
1. Clone the repository from GitHub:
   ```sh
   git clone https://github.com/ChitranshGuha/your-repo.git
   ```
2. Open the project in Android Studio.
3. Ensure that all dependencies are installed.
4. Run the app on an emulator or a physical device.

## Model Training
- The model was trained using MobileNetV2 in Google Colab.
- Dataset: [Dog and Cat Classification Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)
- Training process:
  - Data preprocessing and augmentation
  - Model fine-tuning
  - Conversion to TensorFlow Lite format for mobile deployment

## File Structure
```
- /model/
  - cat_dog_classifier.h5 (original Keras model)
  - cat_dog_classifier.tflite (optimized model for mobile)
- /app/
  - Android app source code
- /notebooks/
  - Model training notebook (Google Colab)
- README.md
```

## How It Works
1. The user uploads an image via the app.
2. The image is processed and passed through the TensorFlow Lite model.
3. The model predicts whether the image contains a cat or a dog and returns a confidence score.
4. The result is displayed on the screen.

## Future Improvements
- Improve model accuracy with a larger dataset.
- Optimize app performance and UI.
- Add real-time camera classification.

## Contributors
- [Chitransh Guha](https://github.com/ChitranshGuha)

## License
This project is licensed under the MIT License.

