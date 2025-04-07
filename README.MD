# 🚗 Car Detection, Speed Tracking & License Plate OCR System

A computer vision-based Python project that detects vehicles in a video feed, calculates their speed, reads license plates using OCR, and issues fines with simulated account deduction and SQLite challan storage.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries/Tools:** OpenCV, EasyOCR, SQLite3  
- **Environment:** Jupyter Notebook  
- **Model:** Haarcascade (`cars.xml`)

---

## 🚀 Features

- Detects cars in video using pre-trained Haar Cascade Classifier.
- Calculates car speed between two points.
- Recognizes license plates using OCR (`easyocr`).
- Deducts fine amount from account if speed exceeds limit.
- Stores challan details in SQLite database.
- Shows live video with bounding boxes and OCR overlay.

---

## ▶️ How to Run

1. Install dependencies:
    ```bash
    pip install opencv-python easyocr
    ```

2. Add the following files to the same folder:
    - `cars.xml` (car detection Haarcascade)
    - A sample video file (e.g., `highway_video.mp4`)

3. Run the notebook cells in order.

---

## 💡 Future Improvements

- Real-time camera integration.
- Add vehicle tracking for more accurate speed.
- Integrate with cloud database or APIs.
- License plate format validation.
- GUI dashboard for admin view.

