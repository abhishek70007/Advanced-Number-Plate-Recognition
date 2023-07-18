# Advanced Number Plate Recognition with Facial Recognition

The Advanced Number Plate Recognition project is a Python-based application developed using TensorFlow, YOLOv3, Haar Cascade classifiers, and Facial Recognition. It aims to provide an accurate and efficient system for recognizing both vehicle number plates and human faces. This project was initially developed as part of the Internal Kavach Hackathon under the team name Cryptonics.

## Features

- **Object Detection**: The project utilizes the YOLOv3 model for precise object detection. It can accurately identify vehicles and their number plates within images or videos.

- **Plate Localization**: Haar Cascade classifiers are employed to localize number plates within the detected vehicle regions. This technique enhances accuracy and enables focused OCR processing.

- **Facial Recognition**: The project integrates facial recognition capabilities using advanced techniques and libraries. It can detect and recognize human faces, providing additional functionality beyond number plate recognition.

- **Simultaneous Training and Testing**: The application allows for simultaneous training and testing of the number plate recognition and facial recognition systems. This feature facilitates iterative improvements and real-time evaluation of the models' performance.

- **OCR and Adaptive Otsu Image Segmentation**: The project plans to incorporate the Adaptive Otsu image segmentation technique to enhance the OCR accuracy. This enhancement will ensure optimal character recognition and extraction from the number plates.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/abhishek70007/advanced-number-plate-recognition.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Prepare the training data and annotations following the project's guidelines.

4. Train the number plate recognition and facial recognition systems:
   ```
   python train.py
   ```

5. Test the system on images or videos:
   ```
   python test.py --image path/to/image.jpg
   python test.py --video path/to/video.mp4
   ```

6. The system will detect and recognize number plates and faces in the provided images or videos, providing the results in the console or saving them to output files.

## Contributing

Contributions to the Advanced Number Plate Recognition project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgements

The Advanced Number Plate Recognition project was developed using TensorFlow, YOLOv3, Haar Cascade classifiers, and Facial Recognition. The team Cryptonics would like to thank the Internal Kavach Hackathon organizers for providing the platform to showcase their skills and work on this project. Special thanks to the open-source community for their valuable contributions and the developers of the libraries and models used in this project.
