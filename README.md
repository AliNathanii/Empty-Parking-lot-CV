# Parking Spot Detection

## Overview

This project detects available parking spots in a video stream using OpenCV and a pre-trained machine learning model. It processes a video of a parking lot, identifies parking spots using a mask image, compares frames to detect changes, and uses a model to determine if a spot is occupied or empty.

## Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/AliNathanii/parking-spot-detection.git
    cd parking-spot-detection
    ```

2. **Install Dependencies**:
    Ensure you have Python 3.6 or higher installed. Then install the required packages using pip:
    ```sh
    pip install -r requirements.txt
    ```

3. **Prepare the Model**:
    - Ensure the `model.p` file is in the `./model/` directory.

## Usage

### Running the Script

To run the script, use the following command:
```sh
python main.py
```

You can find the data (mp4 files) here: https://drive.google.com/drive/folders/1sOxXnZr3i3JSjry-9bwUaPwD5-hIcaTP?usp=sharing
