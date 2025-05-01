# 🪨📄✂️ Rock-Paper-Scissors Image Classification
---

## 📝 Deskripsi Proyek
Proyek ini mengimplementasikan model klasifikasi gambar untuk mengenali tiga kategori gestur tangan:
- 🪨 **Rock**
- 📄 **Paper**
- ✂️ **Scissors**

Model dibangun menggunakan **TensorFlow** dan **Keras**, dengan teknik **Transfer Learning** menggunakan arsitektur _pre-trained_ **MobileNetV2** sebagai _feature extractor_.

---

## 📂 Struktur Dataset
Dataset yang digunakan berasal dari Kaggle: [Rock Paper Scissors Dataset](https://www.kaggle.com/datasets).  
Struktur direktori dataset harus seperti berikut:

```
dataset/
├── rock/
├── paper/
└── scissor/
```

---

## 🔧 Setup dan Persiapan

### Kebutuhan Sistem
- Python ≥ 3.7 (disarankan 3.9–3.11)
- TensorFlow 2.x
- Scikit-learn
- Matplotlib
- Streamlit (untuk frontend)
- FastAPI & Uvicorn (untuk backend)

### Instalasi Dependensi
```bash
pip install -r requirements.txt
```

---

## 📁 Struktur Folder Proyek

```
Tugas-Pembelajaran-Mesin/
├── backend/
│   ├── __pycache__/
│   ├── main.py
│   └── requirements.txt
├── dataset/
│   ├── rock/
│   ├── paper/
│   └── scissors/
├── frontend/
│   ├── app.py
│   └── requirements.txt
├── model/
│   └── best_transfer.h5
├── README.md
└── requirements.txt
```

---

## 🚀 Menjalankan Aplikasi

### Langkah Penggunaan

1. **Clone Repository**
```bash
git clone https://github.com/tiaraagustinn/Tugas3_TiaraAgustin_2208107010004.git
cd Tugas3_TiaraAgustin_2208107010004
```

2. **Siapkan Environment Python**
Disarankan menggunakan Python versi 3.9–3.11. Buat environment baru, lalu install dependencies:
```bash
pip install -r requirements.txt
```

3. **Download Dataset**
Unduh dataset Rock-Paper-Scissors dari Kaggle:  
🔗 [Rock-Paper-Scissors Dataset – Kaggle](https://www.kaggle.com/datasets)

Setelah diunduh dan diekstrak, susun ke dalam folder:
```
dataset/
├── rock/
├── paper/
└── scissor/
```

4. **Jalankan Aplikasi**

- **Backend (FastAPI)**
```bash
cd backend
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```
Server akan berjalan di: [http://localhost:8000](http://localhost:8000)

- **Frontend (Streamlit)**
```bash
cd frontend
streamlit run app.py
```
Akses aplikasi di: [http://localhost:8501](http://localhost:8501)

---

## 📊 Hasil dan Performa

Contoh hasil prediksi dari model:



