# 🚗 Automatic Number Plate Recognition (ANPR) using OpenCV and Tesseract OCR

An Automatic Number Plate Recognition (ANPR) system developed using Python, OpenCV, and Tesseract OCR. The project detects a vehicle's license plate from an image using computer vision techniques and extracts the registration number through Optical Character Recognition (OCR).

## 📖 Overview

Automatic Number Plate Recognition (ANPR) is a computer vision application that automates the process of identifying and reading vehicle registration numbers from images. This project utilizes OpenCV for image preprocessing and license plate localization, while Tesseract OCR is used to recognize and extract alphanumeric characters from the detected plate.

The project demonstrates the integration of image processing and OCR techniques for applications such as vehicle identification, parking management, toll collection, and traffic monitoring.

---

## ✨ Features

- Detects vehicle license plates from input images.
- Performs image preprocessing to improve detection accuracy.
- Applies edge detection and contour analysis for plate localization.
- Extracts alphanumeric characters using Tesseract OCR.
- Implements a simple and efficient computer vision pipeline.
- Built entirely in Python using open-source libraries.

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **Optical Character Recognition:** Tesseract OCR (Pytesseract)
- **Image Processing:** Imutils
- **Numerical Computing:** NumPy

---

## 📂 Project Structure

```
Automatic-Number-Plate-Recognition/
│
├── pytessarct.ipynb          # Jupyter Notebook containing the implementation
├── images.jpg                # Sample input image
├── 7.png                     # Sample input image
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Automatic-Number-Plate-Recognition.git
cd Automatic-Number-Plate-Recognition
```

### 2. Install Python dependencies

```bash
pip install -r requirements.txt
```

### 3. Install Tesseract OCR

This project requires the Tesseract OCR engine to be installed separately.

#### Windows

1. Download and install Tesseract OCR.
2. Update the following line in the notebook with the path to your `tesseract.exe`:

```python
pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"
```

---

## 🚀 Usage

1. Open the Jupyter Notebook:

```bash
jupyter notebook
```

2. Open `pytessarct.ipynb`.

3. Update the image path if necessary.

4. Run all notebook cells sequentially.

The notebook will detect the vehicle's license plate and extract the registration number using Optical Character Recognition.

---

## 🔍 Project Workflow

1. Load the input image.
2. Convert the image to grayscale.
3. Apply bilateral filtering for noise reduction.
4. Detect edges using the Canny Edge Detection algorithm.
5. Identify contours in the image.
6. Locate the license plate region.
7. Crop the detected license plate.
8. Extract text using Tesseract OCR.

---

## 📌 Applications

- Automatic Toll Collection
- Smart Parking Systems
- Vehicle Access Control
- Traffic Monitoring
- Law Enforcement
- Vehicle Identification Systems

---

## 📦 Requirements

Python packages required:

- OpenCV
- NumPy
- Imutils
- Pytesseract

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements

- Support real-time video and webcam input.
- Improve license plate detection using deep learning models such as YOLO.
- Store recognized license plate data in a database.
- Build a web interface using Flask or Streamlit.
- Add support for multiple license plate formats.

---

## 👨‍💻 Author

**Pratik Lagishetty**

If you found this project useful, consider giving the repository a ⭐.
