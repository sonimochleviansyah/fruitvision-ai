Oke **Mr Son**, ini versi **full README** yang sudah lengkap, sesuai proyek **FruitVision AI**, siap untuk GitHub atau dokumentasi:

---

# 🍎 FruitVision AI — Premium Real-Time Fruit Classification Web App

[![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge\&logo=python\&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/flask-%2314354C.svg?style=for-the-badge\&logo=flask\&logoColor=white)](https://flask.palletsprojects.com/)
[![TensorFlow](https://img.shields.io/badge/tensorflow-%23FF6F00.svg?style=for-the-badge\&logo=tensorflow\&logoColor=white)](https://www.tensorflow.org/)
[![Railway](https://img.shields.io/badge/deploy-railway-%23563D7C.svg?style=for-the-badge\&logo=railway\&logoColor=white)](https://web-production-47cc7.up.railway.app/predict)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/sonimochleviansyah/FruitVision-AI)

---

## 📖 Deskripsi Proyek

Proyek ini adalah aplikasi web interaktif untuk **klasifikasi jenis buah** secara real-time menggunakan **Convolutional Neural Network (CNN)**.
UI dirancang dengan **dark mode premium**, **glassmorphism**, dan **floating neon particles**, memberikan pengalaman startup AI modern dan interaktif.

Dikembangkan sebagai proyek implementasi untuk mata kuliah **Kecerdasan Buatan / Deep Learning (SMK / S1 Informatika)**.

---

## 🚀 Fitur Unggulan

* **AI Engine Otomatis:** CNN yang memprediksi 5 jenis buah (apple, banana, mango, grapes, orange) dengan akurasi tinggi.
* **Live Confidence Bar:** Progress bar interaktif menampilkan confidence prediksi dengan animasi gradient dan glow.
* **Drag & Drop Upload:** Upload gambar buah mudah dengan animasi hover, glowing border, dan preview smooth.
* **Loading AI Scan:** Animasi “Scanning AI” saat prediksi diproses, memberi efek real-time.
* **Animated Mesh Gradient:** Background aurora + floating neon particles pelan, memberi depth premium.
* **Glassmorphism UI:** Card dan panel blur dengan shadow untuk efek modern.
* **Responsive Design:** Desktop dan mobile support, tetap elegan di semua ukuran layar.
* **Cursor Glow Effect:** Cursor menghasilkan glow tipis di background, menambah efek futuristik.

---

## 🛠️ Teknologi

* **Backend:** Python, Flask
* **Machine Learning:** TensorFlow, Keras (CNN)
* **Frontend:** HTML, CSS, JavaScript
* **Deployment:** Railway

Model CNN dilatih dengan **dataset 5 kelas buah**, menghasilkan file pre-trained `fruit_model.h5` yang digunakan untuk prediksi real-time.

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
```

---

## ⚡ Instalasi & Menjalankan Lokal

```bash
# Clone repo
git clone https://github.com/sonimochleviansyah/FruitVision-AI.git
cd FruitVision-AI

# Buat virtual environment
python -m venv venv
# Windows
venv\Scripts\activate
# Linux / macOS
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Jalankan Flask server
python app.py

# Buka browser
http://127.0.0.1:5000
```

---

## 🎬 Demo

* **Link Deploy:** [FruitVision AI on Railway](https://web-production-47cc7.up.railway.app/predict)
* **Video Presentasi:** [Demo YouTube](https://youtu.be/<link_video>)

---

## 🔮 Roadmap / Fitur Selanjutnya

* Tambah variasi dataset buah untuk akurasi lebih tinggi.
* Loader AI lebih interaktif, efek visual neon lebih kompleks.
* Toggle Dark/Light Mode.
* Statistik history prediksi per user upload.
* Upgrade CNN ke arsitektur lebih kompleks (ResNet / EfficientNet) untuk performa lebih tinggi.

---

## 📚 Referensi

1. Geron, A. (2019). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*. O'Reilly Media.
2. Chollet, F. (2017). *Deep Learning with Python*. Manning Publications.
3. Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.
4. Flask Documentation: [https://flask.palletsprojects.com](https://flask.palletsprojects.com)
5. Pedregosa, F., et al. (2011). *Scikit-learn: Machine Learning in Python*. Journal of Machine Learning Research, 12, 2825–2830.

---

