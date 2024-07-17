# Hand Tracking with MediaPipe

This project demonstrates real-time hand tracking using MediaPipe and OpenCV. The application captures video from a webcam, processes the video frames to detect hand landmarks, and displays the results with visual annotations.

## Features

- Real-time hand tracking using MediaPipe
- Hand landmark detection and annotation
- Captures video from a webcam and processes each frame
- Flips the video horizontally for a mirror-like experience
- Allows exiting the application by pressing the 'q' key

## Screenshots

### Hand
![Hand](images/1.png)

## Requirements

- Python 3.x
- MediaPipe
- OpenCV
- NumPy
- os

## Installation

1. Clone this repository:
    ```sh
    https://github.com/Jafar-97/YOLO-Drowsiness-Detection.git
    cd hand-tracking-mediapipe
    ```

2. Install the required packages:
    ```sh
    pip install mediapipe opencv-python numpy
    ```

## Usage

1. Run the `left_right.ipynb` Jupyter Notebook or convert the notebook to a Python script and run it:
    ```sh
    jupyter notebook left_right.ipynb
    ```
    or
    ```sh
    jupyter nbconvert --to script left_right.ipynb
    python left_right.py
    ```

2. The application will start capturing video from your webcam and process each frame to detect hand landmarks.

3. Press the 'q' key to exit the application.

## Code Overview

- The application uses the `mediapipe` library for hand tracking.
- Video frames are captured using `cv2.VideoCapture` and processed to detect hand landmarks.
- Detected hand landmarks are drawn on the video frames using `mp_drawing.draw_landmarks`.
- The processed video frames are displayed using `cv2.imshow`.

## Example

Here's an example of what the application looks like in action:

![Hand Tracking](path_to_example_image.png)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- [MediaPipe](https://mediapipe.dev/)
- [OpenCV](https://opencv.org/)

