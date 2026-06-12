p# 🍎 FruitVision AI — Premium Real-Time Fruit Classification Web App

[![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/flask-%2314354C.svg?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![TensorFlow](https://img.shields.io/badge/tensorflow-%23FF6F00.svg?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Railway](https://img.shields.io/badge/deploy-railway-%23563D7C.svg?style=for-the-badge&logo=railway&logoColor=white)](https://railway.app)

Proyek ini adalah aplikasi web interaktif untuk **klasifikasi jenis buah** secara real-time menggunakan **Convolutional Neural Network (CNN)**. UI dirancang dengan **dark mode premium**, **glassmorphism**, dan **floating neon particles**, memberikan pengalaman startup AI yang modern dan interaktif.

Dikembangkan sebagai proyek implementasi untuk mata kuliah **Kecerdasan Buatan / Deep Learning (SMK / S1 Informatika)**.

---

## 🚀 Fitur Unggulan

* **AI Engine Otomatis:** CNN yang memprediksi 5 jenis buah (apple, banana, mango, grapes, orange) dengan akurasi tinggi.
* **Live Confidence Bar:** Progress bar interaktif yang menampilkan confidence prediksi dengan animasi gradient dan glow.
* **Drag & Drop Upload:** Upload gambar buah mudah dengan animasi hover, glowing border, dan preview smooth.
* **Loading AI Scan:** Animasi “Scanning AI” saat prediksi diproses, memberi efek real-time.
* **Animated Mesh Gradient:** Background aurora + floating neon particles yang bergerak pelan, memberi depth premium.
* **Glassmorphism UI:** Card dan panel blur dengan shadow untuk efek modern.
* **Responsive Design:** Desktop dan mobile support, tetap elegan di semua ukuran layar.
* **Cursor Glow Effect:** Cursor menghasilkan glow tipis di background, menambah efek futuristik.

---

## 🛠️ Spesifikasi Teknologi

- **Backend:** Python, Flask  
- **Machine Learning:** TensorFlow, Keras (CNN)  
- **Frontend:** HTML, CSS, JavaScript  
- **Deployment:** Railway / Render (opsional)

Model CNN dilatih dengan **dataset 5 kelas buah**, dan menghasilkan file pre-trained `fruit_model.h5` yang digunakan untuk prediksi real-time.

---

## 📂 Struktur Repositori

```text
CNN_BUAH/
│── app.py            # Backend Flask + API prediksi
│── fruit_model.h5    # Model CNN pre-trained
│── requirements.txt  # Daftar dependencies Python
│── runtime.txt       # Versi Python untuk deployment
├── templates/
│     └── index.html  # Layout web interaktif
└── static/
      ├── css/style.css   # Dark mode premium + glassmorphism + animation
      └── js/script.js    # Upload, preview, loading AI scan, interactivity
