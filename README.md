# LabPy06
# Tugas Pemrograman p10

![Cuplikan layar 2024-11-24 132121](https://github.com/user-attachments/assets/2729fa22-b7e2-42a9-8204-f657c6242a31)
![Cuplikan layar 2024-11-24 132255](https://github.com/user-attachments/assets/d9c56b9a-5a84-46a4-9f6c-75298c196b4a)
![Cuplikan layar 2024-11-24 132348](https://github.com/user-attachments/assets/1df31c83-aff4-4cd1-b7c0-d4aa8e56a8d1)
![Cuplikan layar 2024-11-24 132448](https://github.com/user-attachments/assets/e014df0b-c424-4acd-ba85-6ca89a8a7780)

# 1. Penjelasan Program:
  - Program menggunakan dictionary (`dataMahasiswa`) untuk menyimpan data mahasiswa. Nama mahasiswa menjadi kunci (key), dan nilai-nilai (NIM, nilai tugas, UTS, UAS, dan nilai 
    akhir) disimpan dalam dictionary terpisah sebagai nilai (value).

# 2. Fungsi-Fungsi:
  - `tambah_data()`:
    - Fungsi ini meminta pengguna untuk memasukkan nama, NIM, dan nilai untuk tugas, UTS, dan UAS.
    - Menghitung nilai akhir dengan rumus: [ \text{Nilai Akhir} = (0.30 \times \text{Tugas}) + (0.35 \times \text{UTS}) + (0.35 \times \text{UAS}) ]
    - Menyimpan semua data ke dalam dictionary `dataMahasiswa`.
  - `tampilkan_data()`:
    - Fungsi ini menampilkan semua data mahasiswa dalam format tabel.
    - Fungsi ini menampilkan semua data mahasiswa dalam format tabel.
 - `ubah_data()`:
    - Meminta pengguna untuk memasukkan nama mahasiswa yang ingin diubah
    - Jika nama ditemukan, pengguna akan diminta untuk memasukkan nilai baru.
    - Jika nama ditemukan, pengguna akan diminta untuk memasukkan nilai baru.
  - `hapus_data()`:
    - Meminta pengguna untuk memasukkan nama mahasiswa yang ingin dihapus.
    - Jika nama ditemukan, data mahasiswa akan dihapus dari dictionary.
  - `cari_data()`:
     - Meminta pengguna untuk memasukkan nama mahasiswa untuk dicari.
     - Jika ditemukan, akan menampilkan detail nilai mahasiswa tersebut.

# 3. Menu Utama:
  - Program menggunakan loop `while True` untuk menampilkan menu utama yang memungkinkan pengguna memilih opsi yang diinginkan (menambah, menampilkan, mengubah, menghapus, 
    atau mencari data mahasiswa, atau keluar dari program).

# Flowchart
