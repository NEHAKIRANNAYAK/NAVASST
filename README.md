# AR4VI: Assistive Navigation for the Visually Impaired

## Project Overview

AR4VI (Augmented Reality for Visually Impaired) is a Flask-based web application designed to assist visually impaired individuals with navigation and object recognition. The project utilizes computer vision techniques for object detection and face recognition to provide real-time feedback to users.

## Features

1. Object Detection: Identifies and locates objects in the user's environment.
2. Face Recognition: Detects and recognizes faces, with the ability to add new faces to the system.
3. Real-time Video Streaming: Provides live video feed with object and face detection overlays.
4. User-friendly Web Interface: Easy-to-use web pages for accessing different functionalities.

## Installation

1. Clone the repository;
2. Install required dependencies;
3. Ensure you have the necessary models and data files for object detection and face recognition.

## Usage

1. Run the Flask application:
   ```
   python app.py
   ```

2. Open a web browser and navigate to `http://localhost:5000`

3. Use the web interface to access object detection and face recognition features.

## File Structure

- `app.py`: Main Flask application file
- `object_camera.py`: Contains `VideoCamera` class for object detection
- `facecam.py`: Contains `Facecamera` class for face recognition
- `templates/`: HTML templates for the web interface
  - `object_index.html`: Main page for object detection
  - `object_index2.html`: Page displayed after closing object detection
  - `face_index.html`: Main page for face recognition
  - `face_index2.html`: Page displayed after closing face recognition

## Future Development

- Mobile application development is pending for increased portability and accessibility.
- Further optimization for real-time performance on mobile devices.
- Integration with additional assistive technologies for comprehensive support.

