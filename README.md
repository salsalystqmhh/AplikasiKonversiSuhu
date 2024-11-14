# Aplikasi Konversi Suhu

Aplikasi Konversi Suhu adalah aplikasi berbasis Java yang membantu pengguna mengkonversi suhu antara berbagai skala, seperti Celcius, Fahrenheit, Kelvin, dan Reamur. Aplikasi ini memiliki antarmuka yang sederhana dan memungkinkan pengguna memilih arah konversi suhu.

## Keunggulan Aplikasi

- **Konversi Antar Skala Suhu**: Mendukung konversi suhu antara skala Celcius, Fahrenheit, Kelvin, dan Reamur.
- **Arah Konversi**: Memungkinkan pengguna untuk memilih arah konversi, baik dari kiri ke kanan atau sebaliknya.
- **Validasi Input**: Menampilkan pesan kesalahan jika input tidak valid atau jika skala yang dipilih tidak sesuai.
- **Antarmuka Sederhana dan Intuitif**: Dibangun menggunakan Java Swing untuk memudahkan penggunaan.

## Pembuat Aplikasi

Salsa Alya Istiqamah - 2210010089 - Tugas 2

## Fitur

Aplikasi Konversi Suhu memiliki fitur-fitur berikut:

1. **Pilihan Skala Suhu**  
   Pengguna dapat memilih skala suhu awal dan skala suhu tujuan untuk konversi. Aplikasi mendukung Celcius, Fahrenheit, Kelvin, dan Reamur.

2. **Arah Konversi**  
   Arah konversi suhu dapat dipilih, yaitu dari kiri ke kanan atau dari kanan ke kiri, sesuai pilihan pengguna.

3. **Validasi Input**  
   Aplikasi memvalidasi input numerik dan memastikan bahwa pengguna memilih skala yang berbeda untuk konversi. Jika tidak, akan muncul pesan error.

4. **Konfirmasi Keluar**  
   Tombol "Keluar" dilengkapi dengan dialog konfirmasi untuk memastikan pengguna sebelum menutup aplikasi.

5. **Antarmuka yang Mudah Digunakan**  
   Antarmuka berbasis Java Swing yang memungkinkan pengguna memasukkan nilai suhu, memilih skala konversi, dan melihat hasil konversi dengan mudah.

## Cara Menjalankan

1. Clone atau unduh repositori ini ke komputer Anda.
2. Buka proyek di IDE pilihan Anda (misalnya, NetBeans, IntelliJ, atau Eclipse).
3. Pastikan JDK telah dikonfigurasi dengan benar di IDE Anda.
4. Jalankan `Tugas2` untuk memulai aplikasi.

## Struktur Kode

- **Tugas2**: Kelas utama yang berisi antarmuka pengguna serta metode untuk menangani input dan tombol.
- **initComponents**: Metode untuk menginisialisasi komponen GUI, termasuk pengaturan tombol, label, dan pilihan skala suhu.
- **ActionListener pada Tombol**:
  - **Konversi**: Mengambil input suhu, memvalidasi skala, melakukan konversi, dan menampilkan hasilnya di kolom output.
  - **Keluar**: Mengonfirmasi sebelum menutup aplikasi.
- **KonversiSuhuHelper**: Kelas pembantu (helper) untuk menghitung konversi antar skala suhu. Pastikan kelas ini tersedia di proyek Anda agar konversi dapat berfungsi dengan benar.

## Demo


note : Aplikasi ini dirancang untuk memberikan pengalaman yang mudah dan intuitif bagi pengguna yang ingin melakukan konversi suhu antar skala dengan cepat.

