# Rekayasa Fitur Data Video

Project ini merupakan tugas mata kuliah **Rekayasa Fitur** yang bertujuan untuk melakukan ekstraksi fitur pada data video menggunakan teknik **Histogram Warna (RGB)** dan **Optical Flow**.

---

## 📌 Informasi Mahasiswa

- **Nama** : Rifqy Fakhry Zain
- **NIM** : 10123102
- **Kelas** : IF-3
- **Mata Kuliah** : Rekayasa Fitur

---

## 📂 Dataset

Dataset yang digunakan berupa video dengan format **.mp4**.

Lokasi dataset:

```
Dataset/
└── Dataset.mp4
```

---

## 🎯 Tujuan Project

Project ini bertujuan untuk:

- Melakukan ekstraksi fitur dari data video.
- Menghasilkan representasi fitur yang dapat digunakan sebagai data masukan pada proses analisis maupun machine learning.
- Menyimpan hasil ekstraksi fitur dalam bentuk file CSV dan visualisasi gambar.

---

## ⚙️ Metode Feature Extraction

Project ini menggunakan dua metode ekstraksi fitur, yaitu:

### 1. Histogram Warna (RGB)

Histogram warna digunakan untuk mengetahui distribusi intensitas warna pada setiap frame video.

Output yang dihasilkan:

- Histogram RGB
- Data histogram dalam format CSV

---

### 2. Optical Flow

Optical Flow digunakan untuk mendeteksi arah dan besar pergerakan objek antar frame video.

Output yang dihasilkan:

- Visualisasi Magnitude
- Visualisasi Angle
- Data Optical Flow (.npy)

---

## 📁 Struktur Project

```
rekayasa-fitur-video/
│
├── Dataset/
│   └── Dataset.mp4
│
├── Output/
│   ├── histogram_features.csv
│   ├── histogram_rgb.png
│   ├── optical_flow_angle.png
│   ├── optical_flow_magnitude.png
│   └── optical_flow.npy
│
├── rekayasa_fitur.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Output

Project menghasilkan beberapa file sebagai berikut.

| File                       | Keterangan                               |
| -------------------------- | ---------------------------------------- |
| histogram_features.csv     | Data histogram RGB hasil ekstraksi       |
| histogram_rgb.png          | Visualisasi histogram warna RGB          |
| optical_flow_angle.png     | Visualisasi arah pergerakan (Angle)      |
| optical_flow_magnitude.png | Visualisasi besar pergerakan (Magnitude) |
| optical_flow.npy           | Data Optical Flow dalam format NumPy     |

---

## 🛠️ Library yang Digunakan

- OpenCV
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🚀 Cara Menjalankan Project

### 1. Clone repository

```bash
git clone https://github.com/rifqyfakhryzain/rekayasa-fitur-video.git
```

### 2. Masuk ke folder project

```bash
cd rekayasa-fitur-video
```

### 3. Install dependency

```bash
pip install -r requirements.txt
```

### 4. Jalankan Jupyter Notebook

```bash
jupyter notebook
```

### 5. Buka file

```
rekayasa_fitur.ipynb
```

Kemudian jalankan seluruh cell secara berurutan (**Run All**) untuk menghasilkan seluruh output.

---

## 📦 Dependency

Seluruh dependency project terdapat pada file:

```
requirements.txt
```

Install menggunakan:

```bash
pip install -r requirements.txt
```

---

## 📌 Hasil Akhir

Project berhasil melakukan ekstraksi fitur video menggunakan metode:

- ✅ Histogram Warna (RGB)
- ✅ Optical Flow

Hasil ekstraksi disimpan dalam bentuk visualisasi gambar, file CSV, dan data NumPy sehingga dapat dimanfaatkan pada proses analisis data maupun pengembangan model machine learning.

---

## 👨‍💻 Author

**Rifqy Fakhry Zain**

Universitas Komputer Indonesia (UNIKOM)

Program Studi Teknik Informatika
