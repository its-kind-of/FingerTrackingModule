# Hand Detection using Mediapipe and OpenCV

This project demonstrates hand detection using Mediapipe and OpenCV. It detects and tracks multiple hands in a video stream and provides the landmarks (positions) of the detected hands.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Mediapipe (`pip install mediapipe`)

## Usage

1. Clone the repository or download the source code.

2. Install the required dependencies using the command `pip install -r requirements.txt`.

3. Run the `hand_detection.py` script.

```
python hand_detection.py
```
## Demo
A video stream will open, showing the detected hands and their landmarks (position). The FPS (frames per second) will be displayed on the screen.

Press 'Q' to exit the program.

# Customization
You can customize the behavior of the hand detection by modifying the parameters in the HandDetector class constructor:

* mode: Set to True for static images or False for video stream (default: False).
* maxHands: Maximum number of hands to detect (default: 2).
* modelComplexity: Model complexity, can be 0, 1, or 2 (default: 1).
* detectionCon: Minimum confidence threshold for hand detection (default: 0.5).
* trackCon: Minimum confidence threshold for hand tracking (default: 0.5).
Feel free to experiment with these parameters to achieve the desired hand detection behavior.

# License
This project is licensed under the MIT License.