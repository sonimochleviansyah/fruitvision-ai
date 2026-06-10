Oke **Mr Son**, gue bikinin **FULL README.md siap copy-paste** buat GitHub project lo. Ini udah termasuk deskripsi catchy, fitur, teknologi, struktur folder, cara install, deploy, dan author info. Lo tinggal bikin file `README.md` di folder project dan paste ini:

```markdown
# FruitVision AI - Premium Web App

## Deskripsi Singkat
**FruitVision AI** – Real-time fruit classification web app with CNN and premium interactive UI. Responsive di PC & HP, dengan animated mesh gradient, floating neon particles, drag & drop upload, smooth preview, loading AI scan animation, dan confidence bar interaktif.

---

## Overview

FruitVision AI adalah aplikasi web interaktif yang memanfaatkan **Convolutional Neural Network (CNN)** untuk melakukan **klasifikasi jenis buah** secara real-time. UI dirancang dengan **glassmorphism**, **floating neon particles**, dan **aurora gradient**, memberikan pengalaman premium ala startup AI.

Aplikasi ini **fully responsive**, dengan animasi prediksi, preview gambar smooth, confidence bar interaktif, dan loading AI scan animation.

---

## Fitur Utama

- **Real-time Fruit Prediction**: Prediksi jenis buah dengan akurasi tinggi.
- **Drag & Drop Upload**: Upload gambar mudah dengan animasi hover dan glowing border.
- **Smooth Preview**: Gambar yang di-upload tampil dengan zoom-in efek.
- **Confidence Meter**: Animasi progress bar dengan gradient dan glow.
- **Loading AI Scan Animation**: Indikator prediksi seperti sistem AI nyata.
- **Floating Neon Particles**: Background bergerak memberi vibe modern.
- **Responsive Design**: PC dan mobile support.
- **Glassmorphism UI**: Card dan panel modern dengan blur dan shadow.
- **Cursor Glow Effect**: Kursor memunculkan glow tipis di background.

---

## Screenshots

![Upload Page](./static/images/screenshot1.png)  
![Prediction Result](./static/images/screenshot2.png)  

---

## Technology Stack

- **Backend**: Python, Flask
- **Machine Learning**: TensorFlow, Keras (CNN)
- **Frontend**: HTML, CSS, JS
- **Deployment**: Railway / Render (opsional)

---

## Project Structure

```

CNN_BUAH/
│── app.py
│── fruit_model.h5
│── requirements.txt
│── runtime.txt
├── templates/
│     └── index.html
└── static/
├── css/style.css
└── js/script.js

````

---

## Installation & Running Locally

1. Clone repository:

```bash
git clone <repo_url>
cd CNN_BUAH
````

2. Buat virtual environment & install dependencies:

```bash
python -m venv venv
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

3. Jalankan web app:

```bash
python app.py
```

4. Buka browser:

```text
http://127.0.0.1:5000
```

---

## Deployment

Rekomendasi platform:

* **Railway**: Gratis, mudah untuk Flask + TensorFlow
* **Render**: Gratis, stabil, support file model besar (`.h5`)

---

## Notes

* Dataset: 5 kelas buah (apple, banana, mango, grapes, orange)
* Model: `fruit_model.h5` (CNN pre-trained)
* UI: Fully responsive dan interaktif
* Background animated mesh gradient, floating neon particles, drag & drop, glass card, confidence bar animasi

---

## License

MIT License

---

## Author

**Mr Son** – Mahasiswa Informatika dengan UI/UX dream startup vibes 🚀

---

## GitHub Short Description

*FruitVision AI – Real-time fruit classification with CNN & premium interactive UI.*

```
