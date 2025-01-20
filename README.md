# AI Virtual Mouse

## Overview

The **AI Virtual Mouse** is an innovative project that replaces traditional input devices with intuitive hand gestures. Using a webcam, the system tracks hand movements and translates gestures into actions like mouse clicks, cursor movement, and keyboard shortcuts. This touchless technology is designed to enhance accessibility and explore new forms of human-computer interaction.

## Features

- **Cursor Movement:** Control the mouse pointer using hand gestures.
- **Left-Click and Right-Click:** Perform mouse clicks with pinch gestures.
- **Drag and Drop:** Toggle drag mode by pinching and holding.
- **Hover Click:** Simulate a click by hovering for a second.
- **Copy and Paste:** Execute copy and paste operations with specific gestures.
- **Real-Time Processing:** Smooth and responsive performance for seamless interaction.

## Technologies Used

- **Programming Language:** Python
- **Libraries and Frameworks:**
  - OpenCV: For video capture and processing.
  - Mediapipe: For hand landmark detection and tracking.
  - PyAutoGUI: For simulating mouse and keyboard actions.
  - NumPy: For numerical computations.
- **Platforms:**
  - Local Machine
  - Webcam for input hardware

## How It Works

1. **Hand Detection:** The system uses Mediapipe's Hand API to detect and track hand landmarks.
2. **Gesture Recognition:** Specific gestures (e.g., pinches or finger positions) are mapped to mouse and keyboard actions.
3. **Real-Time Interaction:** OpenCV captures live video frames, processes them, and translates gestures into actions on the screen.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ai-virtual-mouse
2. Install the required dependencies:
   ```bash
   pip install opencv-python mediapipe pyautogui numpy
4. Run the program:
    ```bash
    python ai_virtual_mouse.py
## Usage
- Ensure your webcam is connected and working.
- Run the program and allow it to access the webcam.
- Use the following gestures:
   - Cursor Movement: Move your hand to control the mouse pointer.
   - Left-Click: Pinch your thumb and index finger together.
   - Right-Click: Pinch your thumb, index, and middle fingers together.
   - Drag and Drop: Pinch your thumb and index finger to toggle drag mode.
   - Copy: Pinch your thumb, index finger, and pinky together.
   - Paste: Pinch your thumb and pinky together.
   - Hover Click: Keep your index finger still for one second to simulate a click.
Press 'Q' to quit the program.
## Challenges
1. Gesture Detection Accuracy:
   - Fine-tuning the system for reliable gesture detection in various conditions.
2. Smooth Cursor Movement:
   - Implementing smoothing algorithms to reduce jitter.
3. Real-Time Performance:
   - Ensuring low latency for a responsive experience.
4. False Positives:
   - Minimizing unintentional actions caused by misinterpreted gestures.
## Future Improvements
- Add support for multi-hand gestures.
- Enhance gesture differentiation to increase accuracy.
- Optimize performance for lower-end systems.
- Integrate additional gestures for more functionality.

 ##Demo
https://youtu.be/iUIgOLHIg68
## Contribution
Contributions are welcome! If you have suggestions or want to improve the project:

- Fork the repository.
- Create a new branch.
- Commit your changes and submit a pull request.
## License
This project is licensed under the [MIT License](LICENSE).
## Contact
 - email: kuasha10102@gmail.com
 - linkedin: www.linkedin.com/in/sayantichy
 - twitter/ X: https://x.com/Sayantichy
