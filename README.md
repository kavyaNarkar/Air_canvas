
---

# Color Detection and Drawing Application

This project is a simple color detection and drawing application built using Python and OpenCV. It allows users to draw on a canvas using a webcam feed by detecting colors in real-time. Users can adjust the HSV (Hue, Saturation, Value) color thresholds to customize the color detection.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Adjusting Color Detection](#adjusting-color-detection)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- Real-time color detection using webcam input.
- Adjustable HSV thresholds via trackbars for fine-tuning color sensitivity.
- Multiple color options for drawing: Blue, Green, Red, Yellow.
- Clear button to reset the drawing canvas.
- Draw lines by moving your finger or a colored object in front of the camera.

## Installation

To run this project, you need to have Python installed along with the required libraries. Follow these steps to set up the environment:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/color-detection-drawing.git
   cd color-detection-drawing
   ```

2. Install the required packages:

   ```bash
   pip install numpy opencv-python
   ```

## Usage

Run the application using Python:

```bash
python main.py
```

Make sure your webcam is connected and accessible. The application will open two windows: one for tracking and one for painting.

### Controls

- **Spacebar**: Quit the application.
- Use your finger or an object of the desired color in front of the webcam to draw on the canvas.
- Adjust the HSV values using the trackbars to change the sensitivity of color detection.

## Adjusting Color Detection

You can fine-tune the color detection by adjusting the HSV values through the trackbars in the "Color detectors" window:

- **Upper Hue**: Maximum hue value for color detection.
- **Upper Saturation**: Maximum saturation value.
- **Upper Value**: Maximum brightness value.
- **Lower Hue**: Minimum hue value for color detection.
- **Lower Saturation**: Minimum saturation value.
- **Lower Value**: Minimum brightness value.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, feel free to reach out:

- Your Name - [@narkarp.kavya@gmail.com](https://twitter.com/yourusername) 

---

Feel free to replace placeholders such as `yourusername` and `email@example.com` with your actual information. Additionally, if there are any specific features or functionalities unique to your application, make sure to highlight those in the README as well!