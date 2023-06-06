# Face and Emotion Recognition

This project implements a pipeline model for face and emotion recognition using pre-trained models and machine learning algorithms. The model consists of face detection, feature extraction, face recognition, and emotion recognition.

## Prerequisites

- Python 3.7 or higher
- OpenCV (`cv2`) library
- NumPy library
- scikit-learn (`sklearn`) library
- Django framework

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/face-emotion-recognition.git
   
   
   
2. Install the required Python Libraries using pip:
```bash 
   pip install -r requirements.txt
   ```


3. Configure the Django settings:
 - Open the settings.py file in the Django project.
 - Set the STATIC_DIR variable to the path of your static directory.


## Usage

1. Run the django server
 ```bash 
  python manage.py runserver
   ```
   
2. Access the application through your web brower:
 ```bash 
  http://127.0.0.1:8000/

   ```
   
3. Upload an image and click the "Process" button.
4. The application will detect faces in the image, perform face recognition, and predict the emotions of the detected faces. The processed image will be displayed along with the predicted results.


## Demo


https://github.com/aayush3416/Face-Recognition/assets/87783633/194144b1-13d4-4798-a48f-eb0b88ebb444


## License
This project is licensed under the MIT License.

## Acknowledgments
- The face detection model is based on the work of Dlib.
- The feature extraction model is based on the work of OpenFace.
- The face recognition and emotion recognition models are trained using scikit-learn.
