# license_plate_recognition_project
🚘 License Plate Recognition Project

This project is a License Plate Recognition (LPR) system built using *OpenCV* and *Tesseract OCR*. It detects and extracts license plate numbers from vehicle images using image processing and optical character recognition.

## 📁 Project Structur
license_plate_recognition_project/ │ ├── data/                      # Training/test CSVs and raw image data │   └── test_images/          # Folder with vehicle images for testing │ ├── notebooks/                # Jupyter notebooks for development │   └── license_plate_recognition.ipynb │ ├── output/ │   └── final_submission.csv  # Output file with extracted plate numbers │ ├── .gitignore ├── LICENSE └── README.md 
## 🔧 Technologies Used

- Python
- OpenCV
- Pytesseract (Tesseract OCR)
- Pandas
- Matplotlib

## 🚀 How It Works

1. Preprocesses vehicle images (grayscale, threshold, contours)
2. Detects the license plate area using OpenCV
3. Applies Tesseract OCR to extract plate numbers
4. Stores the recognized plates into a CSV file

## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shubham822-ttpi/license_plate_recognition_project.git
   cd license_plate_recognition_project
   pip install -r requirements.txt
   ---

After pasting, scroll down and click *“Commit changes”* (green button).

Let me know if you want a requirements.txt or sample output too!
