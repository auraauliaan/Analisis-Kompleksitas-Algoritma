**Analisis Perbandingan Kinerja Metode Iteratif dan Rekursif dalam Sistem Perhitungan Konversi**

# Sistem Penghitungan Tarif Pengiriman

## Deskripsi Proyek
Proyek ini adalah aplikasi berbasis Python yang menghitung biaya pengiriman berdasarkan berat barang, dimensi, dan berat volumetrik. Aplikasi ini mendukung dua metode penghitungan:
1. **Iteratif**: Menggunakan perulangan untuk memproses data pengiriman.
2. **Rekursif**: Menggunakan pendekatan rekursif untuk memproses data pengiriman.

Proyek ini dirancang untuk memberikan pengalaman pengguna yang interaktif, di mana pengguna dapat memasukkan data pengiriman secara manual melalui terminal.

## Fitur
- **Penghitungan biaya pengiriman**
  - Berdasarkan berat barang (kg)
  - Berdasarkan dimensi barang (cm)
  - Berdasarkan berat volumetrik (kg)
- **Metode Iteratif dan Rekursif**
- **Antarmuka Terminal Interaktif** untuk input pengguna

## Struktur File
```
|-- Code AKA.ipynb  # Kode utama
|-- README.md              # Dokumentasi proyek
```

## Penjelasan Logika Program
### Iteratif
Metode ini menggunakan perulangan untuk menghitung biaya pengiriman untuk setiap entri dalam dataset. Keunggulan metode ini adalah efisiensi penggunaan memori.

### Rekursif
Metode ini menggunakan pemanggilan fungsi secara rekursif untuk menghitung biaya pengiriman. Kode lebih sederhana untuk dibaca, namun penggunaan memori lebih tinggi karena adanya stack rekursi.

## Contoh Input dan Output
### Input:
```text
--- Sistem Penghitungan Tarif Pengiriman ---
Ingin memasukkan data pengiriman? (y/n): y
Masukkan ID Pengiriman: A001
Masukkan Berat Barang (kg): 2.5
Masukkan Panjang Barang (cm): 50
Masukkan Lebar Barang (cm): 30
Masukkan Tinggi Barang (cm): 20
Masukkan Berat Volumetrik (kg): 3.2
Ingin memasukkan data pengiriman? (y/n): n
```

### Output:
```text
--- Hasil Perhitungan (Iteratif) ---
ID Pengiriman: A001, Total Cost (IDR): 93000
--- Hasil Perhitungan (Rekursif) ---
ID Pengiriman: A001, Total Cost (IDR): 93000
```

## Lisensi
Proyek ini menggunakan lisensi [MIT](https://opensource.org/licenses/MIT).

## Kontribusi
Kontribusi sangat diterima! Jika Anda ingin menambahkan fitur baru atau memperbaiki kode, silakan buka *pull request* atau buat *issue*.

## Kontak
Untuk pertanyaan lebih lanjut, hubungi:
- **Email**: auraauliaan@gmail.com
- **GitHub**: [GitHub Username](https://github.com/auraauliaan)

