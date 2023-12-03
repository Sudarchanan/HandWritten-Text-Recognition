# HandWritten-Text-Recognition
This project is a Flask web app that can recognize handwritten text from images. It uses a deep learning pipeline based on the htr_pipeline module, which consists of a word detector and a reader. The word detector is a Faster R-CNN model that can locate words in an image, and the reader is a CRNN model that can recognize the text of each word.

## Installation
To run this project, you need to have Python 3.6 or higher and the following dependencies installed:

Flask
PyTorch
torchvision
opencv-python
numpy
Pillow
tqdm
You can install them using pip:

pip install -r requirements.txt

## Usage
To start the web app, run the following command:

python app.py

Then, open your browser and go to http://localhost:5000. You will see a simple interface where you can upload an image and get the recognized text.

You can also use the demo script to test the pipeline on some sample images:

python scripts/demo.py

This will show the original images, the detected words, and the recognized text.

## Examples
Here are some examples of the results:

## Credits
This project is based on the following repositories:
Faster R-CNN
CRNN
