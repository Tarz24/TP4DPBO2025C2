**Saya Muhammad Akhtar Rizki Ramadha dengan NIM 2304742 mengerjakan soal Tugas Praktikum 4 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.**

# Data Mahasiswa GUI

Program ini merupakan aplikasi berbasis Java yang menggunakan GUI (Graphical User Interface) untuk mengelola data mahasiswa. Aplikasi ini memungkinkan pengguna untuk menambahkan, memperbarui, dan menghapus data mahasiswa yang meliputi NIM, Nama, Jenis Kelamin, dan Program Studi.

## Struktur Kelas

**1. Mahasiswa**

Kelas model untuk merepresentasikan data mahasiswa dengan atribut

- nama
- nim
- jenisKelamin
- programStudi
    
**2. Menu**

Kelas utama yang berisi GUI aplikasi dengan komponen

- JTextField untuk input NIM dan Nama.
- JComboBox untuk memilih Jenis Kelamin dan Program Studi.
- JTable untuk menampilkan data mahasiswa.
- JButton untuk operasi CRUD (Create, Read, Update, Delete).

## Fitur Program

- Menampilkan daftar mahasiswa dalam bentuk tabel.
- Menambahkan data mahasiswa baru.
- Memperbarui data mahasiswa yang sudah ada.
- Menghapus data mahasiswa.
- Konfirmasi penghapusan data menggunakan JOptionPane.

## Alur Program

- Pengguna menginput data mahasiswa melalui form GUI.
- Data yang dimasukkan akan ditampilkan dalam tabel mahasiswa.
- Pengguna dapat memperbarui atau menghapus data yang telah dimasukkan.
- Setiap penghapusan akan dikonfirmasi menggunakan JOptionPane.
- Data yang sudah diperbarui atau dihapus akan diperbarui di tabel secara otomatis.
