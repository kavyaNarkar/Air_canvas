# Air_canvas
Air Canvas : A Python project using OpenCV to draw on a virtual canvas in real-time. Hand gestures act as the brush, enabling touch-free drawing with customizable colors and brush thickness.

Here’s how you can set everything up with a single bash script, from installing dependencies to running the code. The script will set up the environment and then execute the Python script:

```bash
#!/bin/bash

# Update and install dependencies
echo "Installing Python dependencies..."

# Install Python 3 if not installed (for Ubuntu/Debian systems)
sudo apt-get update
sudo apt-get install python3 python3-pip -y

# Install OpenCV and NumPy
pip3 install opencv-python numpy

# Clone or download your repository (if not already done)
# Replace "your-repository-url" with the actual GitHub repo URL
# git clone your-repository-url
# cd your-repository-name

# Check if the Python script exists
SCRIPT_NAME="your_script_name.py"
if [ ! -f "$SCRIPT_NAME" ]; then
    echo "Python script ($SCRIPT_NAME) not found in this directory."
    echo "Please make sure to place your script in the same directory as this bash file."
    exit 1
fi

# Run the Python script
echo "Running the Python script..."
python3 "$SCRIPT_NAME"

echo "Script execution completed."
```

### Steps to Use:
1. Save this as a `.sh` file, for example `setup_and_run.sh`.
2. Make it executable by running:
   ```bash
   chmod +x setup_and_run.sh
   ```
3. Execute the bash script:
   ```bash
   ./setup_and_run.sh
   ```

### What it does:
- Installs Python 3, pip, and the required libraries (`opencv-python` and `numpy`).
- Optionally, it clones a repository if you need it to fetch the code.
- Checks for the existence of your Python script (`your_script_name.py`) and runs it.

