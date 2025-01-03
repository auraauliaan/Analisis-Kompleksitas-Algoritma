# Analisis Perbandingan Kinerja Metode Iteratif dan Rekursif dalam Sistem Perhitungan Konversi

## Sistem Penghitungan Tarif Pengiriman

### Deskripsi Proyek
Proyek ini adalah aplikasi berbasis Python yang menghitung biaya pengiriman berdasarkan berat barang, dimensi, dan berat volumetrik. Aplikasi ini mendukung dua metode penghitungan:
1. **Iteratif**: Menggunakan perulangan untuk memproses data pengiriman.
2. **Rekursif**: Menggunakan pendekatan rekursif untuk memproses data pengiriman.

Proyek ini menggunakan dataset dummy JNE_dummy_dataset_no_tarif.csv yang terdiri dari 100 dataset dan bisa diakses pada folder yang sama.

### Fitur
- **Penghitungan biaya pengiriman**
  - Berdasarkan berat barang (kg)
  - Berdasarkan dimensi barang (cm)
  - Berdasarkan berat volumetrik (kg)
- **Metode Iteratif dan Rekursif**

### Struktur File
```
|-- code_AKA_final.ipynb  # Kode utama
|-- JNE_dummy_dataset_no_tarif.csv # Dataset Dummy
|-- README.md              # Dokumentasi proyek
```
[Code](https://github.com/auraauliaan/Analisis-Kompleksitas-Algoritma/blob/main/code_AKA_final.ipynb)
[Dataset](https://github.com/auraauliaan/Analisis-Kompleksitas-Algoritma/blob/main/JNE_dummy_dataset_no_tarif.csv)
[Poster](https://github.com/auraauliaan/Analisis-Kompleksitas-Algoritma/blob/main/poster%20AKA%20tubes.png)

### Penjelasan Logika Program
#### Iteratif
Metode ini menggunakan perulangan untuk menghitung biaya pengiriman untuk setiap entri dalam dataset. Keunggulan metode ini adalah efisiensi penggunaan memori.

#### Rekursif
Metode ini menggunakan pemanggilan fungsi secara rekursif untuk menghitung biaya pengiriman. Kode lebih sederhana untuk dibaca, namun penggunaan memori lebih tinggi karena adanya stack rekursi.


### Lisensi
Proyek ini menggunakan lisensi [MIT](https://opensource.org/licenses/MIT).

### Kontribusi
Kontribusi sangat diterima! Jika Anda ingin menambahkan fitur baru atau memperbaiki kode, silakan buka *pull request* atau buat *issue*.

### Kontak
Untuk pertanyaan lebih lanjut, hubungi:
- **Email**: auraauliaan@gmail.com
- **GitHub**: [GitHub Username](https://github.com/auraauliaan)

