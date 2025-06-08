English OCR with EasyOCR and OpenCV
This project demonstrates how to perform Optical Character Recognition (OCR) on images containing English text using EasyOCR and OpenCV. 
The code detects text in an image, draws bounding boxes, and displays the recognized text directly on the image.

🧰 Features
Detects and extracts English text from images.

Highlights detected text with bounding boxes.

Displays the processed image using matplotlib.

🖼️ Example
(Add a sample image output here if available)

🗂️ Project Structure
.
├── rc.jpg               # Input image with English text
├── ocr_english.py       # Python script
├── README.md            # Project documentation
🚀 Getting Started
✅ Requirements
Python 3.6+

pip package manager

📦 Installation
Install required packages using pip:

pip install easyocr opencv-python matplotlib
🧪 Usage
Replace the image_path in the script with the path to your image file.

Run the script:
python untitled.py
🧠 How It Works
Loads an image using OpenCV.

Initializes an EasyOCR reader for English ('en').

Detects text in the image and returns bounding box data.

Draws rectangles around detected text and labels it.

Displays the final image with annotations.

✏️ Code Overview

🌐 Language Configuration
The OCR is configured for English:

reader = easyocr.Reader(['en'], gpu=False)
You can add more languages or switch to another by changing the code above. See the EasyOCR docs for supported languages.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙋‍♀️ Author
Anisha S
Feel free to fork, use, or contribute!
