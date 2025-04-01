# Proyek Klasifikasi Gambar: Rice Classification

## Deskripsi Proyek
Proyek ini bertujuan untuk mengklasifikasikan gambar beras ke dalam 5 kategori menggunakan model Convolutional Neural Network (CNN). Dataset yang digunakan adalah dari Kaggle yang terdiri dari gambar beras yang telah diberi label. Dataset ini dapat digunakan untuk mengidentifikasi 5 jenis beras yaitu Arborio, Basmati, Ipsala, Jasmine dan Karacadag. Model yang dikembangkan dapat membantu dalam Pengenalan jenis beras dan pengenalan gambar.

Anda dapat mengunduh datasetnya [disini](https://www.kaggle.com/datasets/ayanwap7/rice-image-dataset-train-test-split).

## Struktur Folder
Proyek ini memiliki struktur folder sebagai berikut:
- `tfjs_model`: Model TensorFlow.js yang disimpan untuk digunakan dalam aplikasi web, memungkinkan inferensi langsung di browser.
- `tflite`: Model TensorFlow Lite yang dioptimalkan untuk perangkat mobile dan sistem embedded, memberikan performa efisien dengan latensi rendah.
- `saved_model`: Format standar untuk menyimpan model TensorFlow, memungkinkan pemindahan dan penggunaan di berbagai platform dengan semua informasi yang diperlukan.
- `notebook.ipynb`: Dokumen interaktif dalam Jupyter Notebook untuk menulis dan menjalankan kode Python, sering digunakan untuk eksperimen dan analisis data.
- `README.md`: Dokumen panduan proyek yang memberikan informasi tentang instalasi, penggunaan, dan dependensi yang diperlukan.
- `requirements.txt`: File yang berisi daftar paket dan versi yang diperlukan untuk menjalankan proyek Python, memudahkan instalasi dependensi.

## Instalasi
Pastikan untuk menginstal dependensi yang diperlukan untuk menjalankan proyek ini. Anda bisa menginstal semua dependensi dengan perintah berikut:

```bash

pip install -r requirements.txt

- Persyaratan
Pastikan Anda telah menginstal Python 3.x dan pip. Selain itu, Anda memerlukan beberapa paket seperti tensorflow, numpy, kaggle dan paket paket lainnya, yang terdaftar dalam file requirements.txt.

- Penggunaan
  1. Unduh Dataset: Anda dapat mengunduh dataset dari Kaggle menggunakan API Kaggle atau mengunggahnya secara manual ke Google Colab atau Jupyter Notebook.
  2. Pelatihan Model: Buka dan jalankan notebook notebook.ipynb untuk melatih model CNN dengan menggunakan dataset gambar beras.Notebook ini mencakup:
      Pengolahan data (pengubahan ukuran gambar),
      Pembuatan dan pelatihan model CNN,
      Evaluasi dan visualisasi hasil pelatihan.
  3. Konversi Model: Setelah model selesai dilatih, model dapat disimpan dalam beberapa format seperti:
      TensorFlow.js (untuk aplikasi berbasis web),
      TensorFlow Lite (untuk perangkat mobile),
      SavedModel (format standar untuk TensorFlow).
  4. Evaluasi Model: Anda dapat menilai performa model pada dataset pengujian dan melihat akurasi serta loss yang tercatat selama proses pelatihan.

- Format Model yang Didukung
  1. TensorFlow SavedModel: Model baku yang dirancang untuk digunakan dalam TensorFlow, memungkinkan penyimpanan, pemuatan, dan pemindahan dengan mudah.
  2. TensorFlow Lite: Format model yang lebih ringan, cocok untuk digunakan pada perangkat mobile dan sistem embedded.
  3. TensorFlow.js: Format model yang ditujukan untuk aplikasi berbasis web.

- Contoh Output
  1. Akurasi model pada dataset pelatihan dan pengujian dapat ditampilkan dalam bentuk grafik.
  2. Model yang sudah dilatih dapat disimpan dalam berbagai format dan digunakan untuk inferensi di berbagai platform.
  Kontribusi

*Jika Anda berminat untuk berkontribusi pada proyek ini, Anda dapat melakukan fork dan membuat pull request untuk memperbaiki model atau menambahkan fitur baru.
