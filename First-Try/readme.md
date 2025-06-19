## 🔥🔥 Kuliah Final Project 🔥🔥

### TITLE : PEMANFAATAN ARTIFICIAL NEURAL NETWORK UNTUK MENDETEKSI STUNTING DAN WASTING

Tujuan : Membuat ANN untuk mendeteksi _Stunting_ dan _Wasting_

Bahasa Pemrograman : 🐍 Python (Jupyter lab)

### Progress:

- 📖 Kajian Literatur ✅

  - Cari referensi jurnal ✔
  - Cari referensi buku ✔

- 📝 Pengumpulan Data ✅

  - Data Latih => 10 ribu baris data, situs Kaggle, diakses tanggal 15 April 2025 ✔
  - Data Uji => 190 data balita, situs pemkomedan, diakses tanggal 15 Februari 2023 [Site Redacted] ✔

- 💾 Pre-processing Data ✅

  - Cleaning Data ✅
    - Hapus data kosong ✔
    - Ubah penulisan data ✔
    - Ubah format data ✔
    - Cari outlier data ✔
    - Bersihkan data noise ✔
    - Mengganti nama fitur ✔
  - Integration Data ✅
    - Gabung dataset uji menjadi satu pada excel ✔
  - Transformation Data ✅
    - Ubah nilai label yang sudah ada ✔
    - Interpolasi nilai data yang tidak ada pada tabel WHO ✔
    - Menentukan nilai label baru ✔
    - Membuat label hot-encoded vector ✔
  - Reduction Data ✅
    - Hapus fitur dan label yang tidak relevan ✔
    - Hapus fitur dan label yang tidak dipakai lagi ✔
    - Hapus data duplikat ✔

- 🕸 Rancang jaringan ANN ✅

  - Menentukan jumlah neuron input layer ✔
    - 4 Neuron : umur, jenis kelamin, berat badan, tinggi badan
  - Menentukan jumlah hidden layer
    - 1 dan 2 Hidden Layer
  - Menentukan jumlah neuron hidden layer ✔
    - HL1: 9 Neuron
    - HL2: 4 Neuron
  - Menentukan fungsi aktivasi pada hidden layer ✔
    - ReLU
  - Menentukan jumlah neuron output layer ✔
    - 4 Neuron: Sehat, Stunting, Wasting, Keduanya
  - Menentukan fungsi aktivasi pada output layer ✔
    - SoftMax
  - Menentukan model jaringan yang akan dipakai ✔
    - Model 1
      - 1 Input Layer, 4 Neuron
      - 1 Hidden Layer, 9 Neuron
      - 1 Output Layer, 4 Neuron
    - Model 2
      - 1 Input Layer, 4 Neuron
      - 2 Hidden Layer, 13 Neuron :
        - 9 Neuron
        - 4 Neuron
      - 1 Output Layer, 4 Neuron

- 👨‍🏫 Latih dan Uji jaringan ✅
  - Hasil akurasi didapat:
    - Model 1 : 43%
    - Model 2 : 42%
