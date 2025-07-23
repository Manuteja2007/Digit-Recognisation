# 🧠 Digit Recognition Web App

A simple web application built with Flask to recognize handwritten digits using a TensorFlow Lite model.

---

## 🚀 How to Run the Project Locally


```bash
1. Clone the Repository :
git clone https://github.com/Manuteja2007/Digit-Recognisation.git
cd Digit-Recognisation

2. Set Up a Virtual Environment:
python -m venv flaskenv

Activate the environment:
Windows:
flaskenv\Scripts\activate
macOS/Linux:
source flaskenv/bin/activate

3. Install Required Packages:
pip install -r requirements.txt

4. Download the Model File:
Since the model file model.tflite is too large to be stored in the GitHub repository,
please download it manually from the link below:

➡️ Download model.tflite
https://drive.google.com/file/d/1jUy-7Om-03I6jZEBg74yi-sh425HNjzr/view?usp=sharing

Then, place model.tflite in the root directory of the project (same folder as app.py).

5. Run the Application:
python app.py

Open your browser and go to the link displayed in the terminal (usually http://127.0.0.1:5000).

📁 THE PROJECT STRUCTURE SHOULD BE:

Digit-Recognisation/
├── app.py
├── model.tflite     <-- (Place here after downloading)
├── model.py
├── requirements.txt
├── static/
│   ├── style.css
│   └── script.js
├── templates/
│   └── home.html
├── .gitignore
└── README.md
