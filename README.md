# OpenCV Face Detection Web App

This project is a simple web-based face detection application built using **Python**, **Flask**, and **OpenCV**, with a frontend powered by **HTML**, **CSS**, and **JavaScript**.

The application utilizes Haar Cascade classifiers to detect faces in real-time through the user's webcam.

---

## ✨ Features

* Real-time face detection using webcam
* Clean and responsive UI
* Lightweight and easy to run locally

---

## ⚠️ Important Notice

The live or hosted version (if available) will only display the **User Interface (UI)**.
It will **not execute any face detection functionality** due to limitations in accessing the webcam and running OpenCV on the server.

If you'd like to run the full application, please follow the instructions below to run it locally.

---

## 🛠️ How to Run Locally

### 1. Clone the Repository

### 2. (Optional) Create Virtual Environment

```bash
python -m venv venv
# On Windows
dot\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
python app.py
```

### 5. Open in Browser

Visit `http://127.0.0.1:5000` in your browser. Allow access to the webcam when prompted.

---

## 📁 Project Structure

```
opencv_in_web/
├── app.py
├── requirements.txt
├── haarcascade_frontalface_default.xml
├── haarcascade_frontalface_alt2.xml
├── templates/
│   └── index.html
├── static/
│   ├── main.js
│   └── style.css
└── .gitignore
```

---

## 📄 License

This project is open-source and available for educational and personal use.
