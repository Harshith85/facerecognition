
# Face Recognition Attendance System

This Python project implements a simple face recognition attendance system using the `face_recognition` library and OpenCV. The system captures video frames, detects faces, recognizes known faces, and logs attendance in a CSV file.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Known Issues](#known-issues)
- [Contributing](#contributing)
- [License](#license)

## Features

- Face detection and recognition using the `face_recognition` library.
- Real-time attendance logging.
- CSV file generation with student names and timestamps.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- face_recognition library (`pip install face_recognition`)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/face-recognition-attendance.git
   cd face-recognition-attendance
   
## Install the required dependencies:

pip install cmake/numpy/dlib/face-recognition/opencv-python


## Usage

1. Ensure your webcam is connected and functional.
2. Add images of known faces to the `faces` folder.
3. Run the script:

   ```bash
   python face_recognition_attendance.py
   ```

4. Press 'q' to exit the application.

## Configuration

- Adjust the `face_distance_threshold` variable in the script to fine-tune face recognition sensitivity.
- Customize the `faces` folder by adding images of known faces.

## Known Issues

- Doesn't work as intended in low light.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
