
# Assignment01 – Functional & Usability Testing

## 📌 Project Overview

This project is part of IT3040 – ITPM Assignment 1.

The objective of this assignment is to perform **functional testing and usability testing** on the website:
https://www.pixelssuite.com/

---

## 🧪 Features Tested

The following features were tested:

* Document Conversion
* PDF Editing
* Image Resizing
* Cropping
* Compression
* Image Format Conversion
* Meme Generation
* Color Picker
* Image Rotation
* Image Flipping

---

## ⚙️ Automation Testing

One test scenario was automated using **Playwright (Python)**.

### ✔ Automated Scenario:

* Image format conversion (PNG preview validation)

### ▶️ How to Run

```bash
pip install playwright openpyxl
playwright install
python3 image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
```

---

## 📊 Test Results

* CSV file: `execution_results.csv`
* Screenshot: `results/preview_pass.png`

---

## 📁 Project Structure

```
Assignment01/
│── image_preview_test.py
│── execution_results.csv
│── sample.png
│── results/
│   └── preview_pass.png
│── PixelsSuite_Test_Cases.xlsx
```

---

## 📋 Manual Testing

* Total Test Cases: 36
* Each feature includes:

  * 2 Negative Test Cases
  * 1 Positive Test Case

---

## 🚀 Repository Link

GitHub: https://github.com/Gowsikan27/Assignment01

---

## 👨‍💻 Author

* Name: (Your Name)
* Registration Number: (Your Reg No)
