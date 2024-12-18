# Skin Disease Detection using CNN

## Overview
This project aims to detect and classify various skin diseases using a Convolutional Neural Network (CNN). The system allows users to upload skin images and provides accurate predictions of the detected disease. The model was trained on a dataset of over 10,000 dermatological images and achieves high accuracy in classification. The project also includes a user-friendly front-end interface for image upload and prediction display.

## Features
- **Disease Classification**: Classifies multiple types of skin diseases with high accuracy.
- **Deep Learning**: Utilizes a CNN model trained on dermatological image data.
- **Web Application**: Provides a front-end interface for user interaction.
- **Preprocessing**: Performs image resizing, normalization, and augmentation to enhance model performance.

## Technologies Used
- **Programming Languages**: Python (Backend), HTML/CSS (Frontend)
- **Frameworks and Libraries**:
  - Flask: Web framework for the application
  - TensorFlow/Keras: Deep learning framework for CNN implementation
  - NumPy and PIL: For image preprocessing
  - Matplotlib: For visualizing results
- **Frontend**: Basic HTML, CSS for the user interface

## Dataset
The dataset contains over 10,000 images representing various dermatological conditions. Each image is labeled with the corresponding skin disease category. Preprocessing steps include:
- Image resizing to \(224 \times 224\) pixels.
- Normalization to scale pixel values between 0 and 1.
- Augmentation to improve model generalization.

## Key Steps
1. **Data Preprocessing**:
   - Resized images to uniform dimensions.
   - Applied normalization for pixel scaling.
   - Augmented data to improve robustness.

2. **Model Development**:
   - Built a CNN model with TensorFlow/Keras.
   - Fine-tuned hyperparameters for optimal performance.
   - Achieved over 96% accuracy on the test dataset.

3. **Web Application**:
   - Developed a Flask-based interface for uploading and predicting images.
   - Styled with CSS for a user-friendly experience.

4. **Deployment**:
   - Model integrated into a Flask app for local deployment.
   - The project can be further deployed to cloud platforms like AWS, Azure, or Heroku.

## Results
- The CNN model achieved a classification accuracy of over 96%.
- The application provides a seamless user experience for disease detection.

## Repository Structure
```
.
├── app.py                # Flask application backend
├── templates/
│   ├── index.html        # Frontend HTML file
├── static/
│   ├── style.css         # CSS file for styling
├── models/
│   ├── skin_disease_cnn.h5  # Trained model file
├── data/
│   ├── sample_images/    # Sample images for testing
├── README.md             # Project documentation
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/skin-disease-detection.git
   ```

2. Navigate to the project directory:
   ```bash
   cd skin-disease-detection
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the Flask application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://127.0.0.1:5000` to use the application.

## Future Enhancements
- Expand the dataset to include more skin conditions.
- Deploy the application on cloud platforms for public access.
- Add multilingual support for broader accessibility.
- Incorporate additional image preprocessing techniques.



