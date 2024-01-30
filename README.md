# Face Recognition Live Streaming with Python Flask

This project demonstrates face recognition using the face_recognition library in Python, integrated with a Flask web application for live streaming. The system recognizes faces in real-time through your webcam, comparing them to a set of known faces.

## Project Structure

The project has the following structure:

- **Samson**, **Virat**, and **Warne** folders contain images of individuals for face recognition.
- **templates** folder holds HTML templates for the web application.
  - **index.html**: Displays live streaming with face recognition.
  - **results.html**: Displays final recognition results in a tabular format.
- **app.py**: The main Flask application script.
- **main.py**: A standalone script for face recognition without the web interface.

## Dependencies

Make sure you have the following dependencies installed:

```bash
pip install Flask opencv-python face_recognition numpy
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/face-recognition-flask.git
cd face-recognition-flask
```

2. Run the Flask application:

```bash
python app.py
```

3. Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to view the live streaming with face recognition.

## Instructions

1. The application captures frames from your webcam and performs face recognition against known faces.
2. Recognized faces are highlighted with a bounding box and labeled with the corresponding name.
3. Access the live streaming page by visiting the provided URL. Press 'q' to quit the live streaming window.

## Additional Notes

- The known faces and their encodings are defined in `app.py`.
- The face_recognition library is used for face recognition, and OpenCV is used for video capturing and display.
- Modify the code to add more known faces or customize the recognition logic.

Feel free to explore and enhance the project according to your needs. Happy coding!
