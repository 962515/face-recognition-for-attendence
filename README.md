# face-recognition-for-attendence
This Python script utilizes face recognition technology to automate attendance tracking in a classroom setting. It detects faces in a live video stream, matches them against a database of known faces, and logs attendance in a CSV file.
# Features
 1.Automatic face detection and recognition.
 2.Real-time attendance logging.
 3.Simple setup and usage.
 # Requirements
 1.Python3.x
 2.OpenCV
 3.face_recognition
 4.numpy
 # Install the required packages using pip:
 pip install opencv-python face-recognition numpy
 # Usage
 1. Clone or download the repository to your local machine.
 2. Ensure that your system has a webcam connected.
 3. Navigate to the directory containing the script.
 4. Replace the placeholder image paths in the script with the paths to your own images.
 5. Run the script using the following command:
     python attendance_system.py
 1.As students enter the camera's field of view, their attendance will be automatically logged in a CSV file named with the current date and time.
 # Configuration
  1.Modify the known_face_encodings and known_face_names lists with your own images and corresponding names.
  2.Adjust the video capture device index (e.g., video_capture = cv2.VideoCapture(0)) if necessary.
