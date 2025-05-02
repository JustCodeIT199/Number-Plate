# 🚗 Number Plate Detection using OpenCV

This project is a Python-based implementation for detecting vehicle number plates from images using OpenCV. It uses computer vision techniques like contour detection, image preprocessing, and OCR to extract license plate numbers from vehicle images.

## 🎯 Objective

To detect and extract license plate numbers from images of vehicles using image processing and OCR (Optical Character Recognition).

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries Used**:
  - `OpenCV` – Image processing and contour detection
  - `pytesseract` – Optical character recognition
  - `imutils` – Image manipulation
  - `numpy` – Numerical operations

## 📁 Folder Structure

Number-Plate/ ├── Images/ # Input images of vehicles ├── main.py # Main script for plate detection ├── output/ # Output images with bounding boxes and plate text ├── utils.py # Utility functions (e.g., OCR) └── README.md

## 🔍 How It Works

1. Load vehicle image using OpenCV.
2. Preprocess image: grayscale, blur, edge detection.
3. Detect contours and identify possible number plate regions.
4. Use `pytesseract` to extract text from the detected plate.
5. Display and save the result with bounding box and extracted plate text.

## 🧪 How to Run Locally

1. **Clone the repository**
   git clone https://github.com/JustCodeIT199/Number-Plate.git
   cd Number-Plate
   
Install required libraries
pip install -r requirements.txt

Install Tesseract OCR

Windows: Download from Tesseract at UB Mannheim

Linux: sudo apt install tesseract-ocr

Mac: brew install tesseract

Make sure to update the Tesseract path in the script if needed.

Run the project
python main.py

📜 License
This project is open-source under the MIT License.

✍️ Author
JustCodeIT199 , Malhar-bhoir
