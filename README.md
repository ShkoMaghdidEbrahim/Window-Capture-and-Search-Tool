# Transparent Window Capture and Search Tool

## Overview
This Python application creates a transparent, draggable window that allows users to capture text and images from a specified screen region. It integrates with Google for text searches and Yandex for image searches, opening the search results in a web browser. The tool is designed to provide a quick and convenient way to search for information based on screen content.

## Features
- **Transparent, Draggable Window**: A resizable and movable window that stays on top of other applications.
- **Text Capture and Search**: Captures text from the specified region and performs a Google search with the captured text.
- **Image Capture and Search**: Takes a screenshot of the defined area and searches for similar images using Yandex.
- **Hotkey Activation**: The tool responds to specific keyboard shortcuts for text and image capture.
- **Clipboard Integration**: Utilizes the clipboard for intermediate storage of captured text.

## Running the Program
To run this tool, follow these steps:

1. **Set Up the Environment**:
   - Ensure Python is installed on your system along with necessary libraries: `tkinter`, `pyautogui`, `keyboard`, `pyperclip`, `pygetwindow`, `requests`, and `json`.
   - Install any missing libraries using pip (e.g., `pip install pyautogui`).
   - Ensure `Microsoft PowerToys` is installed and the shortcut for `Text Extractor` is set to `Alt + T`

2. **Run the Script**:
   - Execute the script with Python: `python Main.py`.
   - A transparent window will appear, which can be moved and resized as needed.

3. **Using the Tool**:
   - Position the transparent window over the area of interest on your screen.
   - Press `Alt` to capture text and search on Google.
   - Press `Ctrl` to capture an image and search on Yandex.

## Additional Notes
- The window's transparency and size can be adjusted in the script.
- The application uses threading to manage the GUI and capture/search operations simultaneously.

## Contribution
Contributions are welcome to enhance this tool, such as adding support for different search engines, optimizing performance, or improving the user interface.

## License
Free To Use.
