# 🚗 Smart License Plate Detection using Deep Learning

A deep learning-based web application that detects vehicle license plates in images using a CNN model and extracts the plate number using Optical Character Recognition (OCR). Designed for real-time execution and mobile-friendly deployment.

---

## 📌 Features

- 📷 Detects vehicle license plates from uploaded images
- 🔍 Uses a trained CNN for bounding box detection
- 🔡 Extracts plate number text using Tesseract OCR
- 💡 Outputs annotated image and detected number
- 📱 Compatible with mobile (Pydroid 3) and web platforms
- 🌐 Flask-based web interface for ease of use

---

## 🛠️ Technologies Used

- Python 3
- TensorFlow / Keras (for CNN model)
- OpenCV (for image processing)
- Tesseract OCR (for text extraction)
- Flask (web backend)
- HTML / CSS (frontend interface)
- Pydroid 3 (for Android deployment)

---

## 📁 Project Structure
smartplate_app/ │ 
├── app.py                  # Flask application
├── model.h5                # Pretrained CNN model 
├── plate_number.txt        # Extracted license number
├── requirements.txt        # List of dependencies 
│ ├── templates/ 
│   └── index.html          # HTML template for the web UI
│ ├── static/ 
│   └── output.jpg          # Annotated result image

---

## 🚀 How to Run the Project

### 💻 On Desktop

1. Clone the repository or unzip the project folder.
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies:

pip install -r requirements.txt


4. Start the Flask app:

python app.py


5. Open your browser and go to http://127.0.0.1:5000




---

## 📱 On Mobile (Using Pydroid 3)

1. Extract the folder to /storage/emulated/0/Download/smartplate_app


2. Open Pydroid 3 terminal and run:

cd /storage/emulated/0/Download/smartplate_app
pip install -r requirements.txt
python app.py


3. Visit http://127.0.0.1:5000 on your mobile browser.

To share the app publicly, install ngrok and run:

ngrok http 5000


---

🧪 Sample Output

Detected Plate Number: THO98Y 9776

Annotated output is saved in static/output.jpg

---

📦 Requirements

Install dependencies from requirements.txt:

tensorflow
flask
opencv-python
pytesseract
Pillow

Make sure Tesseract is installed on your device or accessible from code.


---

📌 Future Enhancements

Support for real-time video stream

Model fine-tuning for non-standard plates

Multi-language OCR integration

Deployment using Docker or cloud hosting



---

📄 License

This project is open-source and intended for academic and research use. Contributions are welcome!


---
