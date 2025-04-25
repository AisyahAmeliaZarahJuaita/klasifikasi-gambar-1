# Proyek Klasifikasi Gambar: Intel Image Classification

Proyek ini merupakan implementasi deep learning untuk klasifikasi gambar menggunakan dataset **Intel Image Classification**. Model CNN (Convolutional Neural Network) digunakan untuk mengenali gambar ke dalam beberapa kategori seperti bangunan, jalan, pegunungan, dll.

## Informasi Pengembang
- Nama: Aisyah Amelia Zarah Juaita  
- Email: aisyahamelia740@gmail.com  
- ID Dicoding: aisyahameliazarahj  

## Deskripsi Proyek

Tujuan dari proyek ini adalah membangun model klasifikasi gambar berbasis CNN dengan pipeline yang mencakup:
- Preprocessing dan visualisasi data
- Augmentasi data untuk meningkatkan generalisasi model
- Pembuatan dan pelatihan model CNN
- Evaluasi performa model
- Penyimpanan model dalam berbagai format untuk keperluan deployment:
  - TensorFlow SavedModel
  - TensorFlow Lite (TFLite)
  - TensorFlow.js (TFJS)

## Struktur Notebook

1. Import Library
Semua library yang dibutuhkan seperti TensorFlow, Keras, Matplotlib, dll diimpor di bagian awal.

2. Data Preparation
- Menggabungkan data train dan test ke direktori yang sama
- Visualisasi gambar contoh dari setiap kelas
- Visualisasi distribusi jumlah gambar per kelas
- Augmentasi data untuk memperkaya variasi gambar
- Pembagian data menjadi: training, validation, dan test set

3. Pembuatan Model CNN
- Model CNN dibangun menggunakan arsitektur Conv2D, MaxPooling, Flatten, dan Dense layers.
- Implementasi callbacks seperti EarlyStopping dan ModelCheckpoint untuk optimisasi pelatihan.

4. Training Model
Model dilatih menggunakan data training dan divalidasi menggunakan data validation.

5. Evaluasi Model
Evaluasi dilakukan untuk melihat performa model terhadap data uji.

6. Simpan dan Konversi Model
Model yang telah dilatih disimpan dalam tiga format utama:
- TensorFlow SavedModel
- TensorFlow Lite
- TensorFlow.js

7. Inference
Contoh inferensi ditunjukkan menggunakan model TFLite.

## Cara Menjalankan
1. Clone repositori ini
2. Jalankan semua sel dalam notebook `notebook.ipynb`
3. Pastikan direktori dataset tersedia sesuai path yang disebutkan
4. Model yang telah disimpan bisa digunakan untuk deployment sesuai kebutuhan

## Lisensi
Proyek ini hanya untuk keperluan pembelajaran.
