# 1. Deskripsi
Program ini digunakan untuk menghitung dan menganalisis nilai siswa
menggunakan bahasa pemrograman Python.

## 2. Fitur Program
- Input nilai siswa
- Menghitung rata-rata
- Menentukan nilai tertinggi
- Menentukan nilai terendah
- Menghitung jumlah siswa lulus
- Menghitung jumlah siswa tidak lulus
- Menyimpan hasil analisis

## 3. Persyaratan
- Python 3.x
- Visual Studio Code

## 4. Cara Menjalankan
Jalankan perintah berikut di terminal:

python main.py

## 5. Cara Pengujian
Jalankan perintah:

python -m unittest discover -s tests -v

## 6. Aturan Kelulusan
Nilai >= 60 = Lulus
Nilai < 60 = Tidak Lulus

## 7. Struktur Folder
proyek_pertemuan15/
    main.py
    README.md
    src/
        input_data.py
        proses.py
        output.py
    tests/
        test_case.py
    data/

## 8. Dokumentasi
Program dibuat untuk memenuhi tugas
Algoritma dan Pemrograman Pertemuan 15.

## 9. Referensi
- Bahan Ajar Pertemuan 15
- Dokumentasi Python
https://docs.python.org/3/
"""

with open("README.md", "w", encoding="utf-8") as file:
    file.write(isi_readme)