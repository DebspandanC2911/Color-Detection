# Color Detection App

This is a simple color detection web app built with OpenCV. The app allows users to upload an image, and it detects the color of a pixel in the center of the image. It uses a dataset of color names to return the closest matching color along with the RGB and Hex values.

## Features

- Upload an image and detect the color of a central pixel.
- Displays the name of the color along with its RGB and Hex values.

## Prerequisites

- Python 3.x
- OpenCV
- Pandas

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository**:

    ```
    git clone https://github.com/your-username/color-detection-app.git
    cd color-detection-app
    ```

2. **Install the dependencies**:

    Install the required Python libraries using pip:

    ```
    pip install flask opencv-python pandas
    ```

3. **Download the `colors.csv` file**:

    Make sure to place the `colors.csv` file (which contains the list of colors and their RGB values) in the project directory. The CSV file should be in this format:

    ```
    color,color_name,hex,R,G,B
    ...
    ```

5. **Run on Jupyter Notebook or VS Code(.ipynb Extension is a prerequisite)**:


## Usage

1. Upload an image by selecting a file using the command - ```python color_detection.py -i <Your File with Location>```.
3. The app will display the uploaded image and show the color name, RGB values, and Hex code of the central pixel.

## Example Screenshot

![Color Detection App Screenshot](https://github.com/user-attachments/assets/64487362-9c1c-467d-8cf7-758a88df7518)


## Future Improvements

- Improve the accuracy of color detection by averaging pixel values around the center.
- Add support for larger images and higher resolution color detection.
- Provide an option to display a color palette based on the entire image.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- This app uses the OpenCV library for image processing.
- Color data sourced from `colors.csv` to match pixel values to color names.

---
