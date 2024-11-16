
# Air Canvas Project

**Air Canvas** is a Python-based drawing application that allows users to draw on a canvas using their hands. The program uses OpenCV to track hand movements and detect color inputs via a webcam.

### Features

- **Real-time Drawing:** Users can draw on the canvas by moving their hand and selecting colors.
- **Color Selection:** Choose from predefined colors: Blue, Green, Red, Yellow, and Clear all options.
- **Trackbars:** The program includes adjustable trackbars for fine-tuning the HSV values (Hue, Saturation, Value) of the colors.

### Requirements

Before running the project, ensure that you have Python 3 and the necessary dependencies installed. You'll need to install `opencv-python` and `numpy` using `pip`.

### Installation and Setup

1. **Clone the Repository (if you haven't already):**
   ```bash
   git clone https://github.com/your-username/Air_canvas.git
   cd Air_canvas
   ```

2. **Install the required Python libraries:**
   ```bash
   pip install opencv-python numpy
   ```

3. **Run the Python script:**
   After the dependencies are installed, run the script to start the drawing application.
   ```bash
   python air_canvas.py
   ```

### Usage

1. **Color Selection:**
   - Use your hand to select a color from the top bar of the application window.
   - The available colors are: Blue, Green, Red, and Yellow.
   - The "CLEAR" button will clear the canvas.

2. **HSV Adjustments:**
   - Use the trackbars to adjust the Hue, Saturation, and Value ranges for color detection.

3. **Drawing:**
   - Move your hand within the webcam frame to draw on the canvas.
   - The drawn lines will be the color selected from the top bar.

4. **Exit:**
   - Press the `spacebar` to exit the application.

### Example Screenshots

![Color Selection and Canvas](images/example1.png)
![HSV Adjustments](images/example2.png)

### Troubleshooting

- **Webcam Not Detected:** Make sure that your webcam is connected and working properly.
- **Tracking Issues:** If the application is not detecting colors or movements properly, adjust the HSV values using the trackbars.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Credits

This project uses the following libraries:
- [OpenCV](https://opencv.org/) - for computer vision functionalities.
- [NumPy](https://numpy.org/) - for handling arrays and matrices.

For any questions or contributions, feel free to open an issue or a pull request on GitHub.
```

### Key Sections Explained:

- **Project Overview**: A brief description of the project and its functionality.
- **Installation & Setup**: Step-by-step instructions on how to set up the environment and run the project.
- **Usage**: Instructions on how to use the application, including interacting with the interface.
- **Troubleshooting**: Common issues and how to fix them.
- **License & Credits**: Information on the project’s license and third-party libraries used.

You can copy and paste this directly into your `README.md` file for a more comprehensive and user-friendly explanation of your project.