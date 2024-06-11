# Number Plate Detection Using Deep Learning

This project aims to detect number plates in images using a deep learning model. The model is trained to locate the bounding box coordinates of number plates in images. 

## Project Structure

- **data/**: Contains images and their corresponding XML annotation files.
- **labels.csv**: CSV file containing image paths and bounding box coordinates.
- **NPD.h5**: The saved model file.
- **test.jpeg**: An example output image with the detected bounding box.

## Requirements

- Python 3.x
- Required Python packages (listed in `requirements.txt`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/number-plate-detection.git
   cd number-plate-detection
