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
![flowchart praktikum6](https://github.com/user-attachments/assets/d2a0869a-a75a-44da-b3bd-01ab7760eb80)

# Berikut adalah deskripsi flowchart yang menggambarkan alur program:
  - Mulai: Program dimulai.
  - Tampilkan Menu: Menampilkan pilihan menu (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data, Keluar).
  - Pilih Menu: Pengguna memilih opsi dari menu.
    -Jika "Tambah Data", jalankan fungsi `tambah_data`().
    - Jika "Tampilkan Data", jalankan fungsi `tampilkan_data`().
    - Jika "Ubah Data", jalankan fungsi `ubah_data`().
    - Jika "Hapus Data", jalankan fungsi `hapus_data`().
    - Jika "Cari Data", jalankan fungsi `cari_data`().
    - jika "Keluar", keluar dari loop dan program selesai.
  - Kembali ke Menu: Setelah menjalankan fungsi, kembali ke langkah 2 untuk menampilkan menu lagi.

# Contoh Penggunaan
  - Menambah Data:
    - Pengguna memasukkan nama, NIM, dan nilai untuk tugas, UTS, dan UAS. Program menghitung dan menyimpan nilai akhir.
  - Menampilkan Data:
    - rogram menampilkan semua data mahasiswa dalam tabel.
  - Mengubah Data:
    - Pengguna memasukkan nama mahasiswa yang ingin diubah dan nilai baru. Program memperbarui data
  - Pengguna memasukkan nama mahasiswa yang ingin diubah dan nilai baru. Program memperbarui data
    - pengguna memasukkan nama mahasiswa yang ingin dihapus. Program menghapus data tersebut.
  - Pengguna memasukkan nama mahasiswa yang ingin dihapus. Program menghapus data tersebut.
    - Pengguna memasukkan nama mahasiswa yang ingin dihapus. Program menghapus data tersebut.

# Contoh Output

# Tambahkan Data
![Cuplikan layar 2024-11-24 141953](https://github.com/user-attachments/assets/7321837e-c635-4e3e-8f77-64deef2c2ca5)

# Tampilkan Data
![Cuplikan layar 2024-11-24 142302](https://github.com/user-attachments/assets/ce3d2d41-5b20-4d28-9127-eb692df1a1c7)

# Ubah Data
![Cuplikan layar 2024-11-24 142450](https://github.com/user-attachments/assets/1c06332d-66a1-4667-9a50-60ae53486b67)

# Hapus Data
![Cuplikan layar 2024-11-24 142631](https://github.com/user-attachments/assets/1d17b6c0-580d-4ed0-87d1-0b5302262f1b)

# Cari Data
![Cuplikan layar 2024-11-24 143216](https://github.com/user-attachments/assets/f3df2d78-9ffe-465a-916e-f7158c37f7cc)

# Keluar
![Cuplikan layar 2024-11-24 143345](https://github.com/user-attachments/assets/545433c9-8066-4a62-a29b-3ecdfb16ac61)

![Cuplikan layar 2024-11-24 150723](https://github.com/user-attachments/assets/626e9387-3150-4914-80f1-b9ab24dd3aba)
