# Face Detection with OpenCV

A simple Python application that uses OpenCV's Haar Cascade classifier to detect faces in real-time from your webcam feed.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Controls](#controls)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Features

- Real-time face detection using Haar Cascade classifier
- Draws bounding boxes around detected faces
- Graceful cleanup of resources on exit

## Prerequisites

- Python 3.7 or higher
- OpenCV library for Python
- A webcam or camera device connected to your computer

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/face-detection-opencv.git
   cd face-detection-opencv
   ```

2. **Create and activate a virtual environment** (optional but recommended)

   ```bash
   python -m venv venv
   # Windows
   .\venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   Your `requirements.txt` should include:
   ```text
   opencv-python
   ```

## Usage

Run the main script to start face detection:

```bash
python face_detection.py
```

The application will open a window showing your webcam feed with green rectangles around detected faces.

## Controls

- **q**: Quit the application and close the webcam feed.
- **ESC** (optional): Also terminates the application if enabled.

## Troubleshooting

- **Camera not opening**: Ensure no other application is using the webcam. Check connection and permissions.
- **No faces detected**: Verify good lighting and ensure your face is visible in the frame.
- **Module not found**: Make sure you installed dependencies: `pip install opencv-python`.

## Contributing

Contributions are welcome! To suggest improvements or report issues:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m "Add some feature"`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

