
# AI Virtual Mouse

This project demonstrates an AI-powered virtual mouse system using **OpenCV**, **PyAutoGUI**, and **MediaPipe**. It enables users to control their computer mouse with hand gestures, offering an innovative touch-free interface.

## Features

- **Hand Tracking**: Utilizes MediaPipe for real-time hand landmark detection.
- **Gesture Recognition**: Identifies gestures like pointing, clicking, scrolling, and dragging.
- **Mouse Control**: Maps hand gestures to mouse movements using PyAutoGUI.
- **Customizable Sensitivity**: Adjusts the responsiveness of the virtual mouse.
- **Cross-Platform**: Works on Windows, macOS, and Linux.

## Technologies Used

1. **MediaPipe**: For hand detection and tracking.
2. **OpenCV**: For video capture and image processing.
3. **PyAutoGUI**: For simulating mouse events (movement, clicks, etc.).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-virtual-mouse.git
   cd ai-virtual-mouse
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   The `requirements.txt` includes:
   - `mediapipe`
   - `opencv-python`
   - `pyautogui`
   - `numpy`

3. Ensure your camera is functional and accessible.

## Usage

1. Run the script:
   ```bash
   python ai_virtual_mouse.py
   ```

2. Position your hand in front of the camera to start interaction.

### Default Gestures

- **Index Finger Up**: Move the mouse cursor.
- **Index + Middle Finger Up**: Left click.
- **Index + Thumb Touch**: Drag.
- **Scroll Gesture**: Simulates vertical/horizontal scrolling.

## Configuration

- Adjust sensitivity and gesture mappings in the `config.py` file.
- Camera index and resolution settings can also be customized.

## Known Issues

- Performance may vary with lighting conditions and background clutter.
- Gestures may misfire if the hand position is unclear.

## Future Improvements

- Add more gesture customization options.
- Improve robustness under diverse environmental conditions.
- Integrate additional functionalities like right-click and multi-finger scrolling.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
