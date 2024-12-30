# Studi-kasus

## Biodata

Nama    : Zizantara Arzeva Cakra Kahana

NIM     : 312410398

Kelas   : TI,24.A.3

# Program Validasi Form Input

# Program Validasi Form Pendaftaran

Program ini adalah sistem validasi sederhana untuk form pendaftaran online yang ditulis dalam bahasa Python. Program melakukan validasi terhadap input nama lengkap, nomor telepon, dan alamat email berdasarkan kriteria tertentu.

## Fitur

Program memiliki beberapa fitur validasi:
- Validasi nama lengkap (hanya menerima input huruf)
- Validasi nomor telepon (hanya menerima input angka)
- Validasi email (harus mengandung karakter @ dan .)

## Persyaratan Sistem

- Python 3.x

## Cara Menggunakan Program

1. Pastikan Python sudah terinstal di sistem Anda
2. Jalankan program dengan perintah:
   ```bash
   python validasi_form.py
   ```
3. Ikuti instruksi yang muncul di layar untuk memasukkan data

## Struktur Program

Program terdiri dari beberapa fungsi utama:

### validasi_nama(nama)
- Fungsi untuk memvalidasi nama lengkap
- Parameter: nama (string)
- Return: True jika valid, False jika tidak valid
- Kriteria: hanya boleh mengandung huruf dan spasi

### validasi_telepon(telepon)
- Fungsi untuk memvalidasi nomor telepon
- Parameter: telepon (string)
- Return: True jika valid, False jika tidak valid
- Kriteria: hanya boleh mengandung angka

### validasi_email(email)
- Fungsi untuk memvalidasi alamat email
- Parameter: email (string)
- Return: True jika valid, False jika tidak valid
- Kriteria: harus mengandung karakter @ dan .

### validasi_pendaftaran()
- Fungsi utama yang menjalankan proses validasi
- Meminta input dari pengguna
- Melakukan validasi menggunakan fungsi-fungsi di atas
- Menampilkan hasil validasi

## Contoh Penggunaan

```
=== Form Pendaftaran ===
Masukkan nama lengkap: John Doe
Masukkan nomor telepon: 08123456789
Masukkan email: john.doe@email.com

Data pendaftaran valid.
Nama: John Doe
Telepon: 08123456789
Email: john.doe@email.com
```

## Penanganan Error

Program akan menampilkan pesan error spesifik untuk setiap jenis kesalahan:
1. Jika nama mengandung karakter selain huruf:
   ```
   Error: Nama hanya boleh berisi huruf!
   ```
2. Jika nomor telepon mengandung karakter selain angka:
   ```
   Error: Nomor telepon hanya boleh berisi angka!
   ```
3. Jika email tidak mengandung @ dan .:
   ```
   Error: Email harus mengandung karakter @ dan .
   ```

## Keterbatasan

- Validasi email masih sederhana (hanya mengecek keberadaan @ dan .)
- Program tidak menyimpan data ke database
- Tidak ada validasi untuk panjang input

## Pengembangan Selanjutnya

Beberapa fitur yang bisa ditambahkan:
1. Validasi email yang lebih kompleks
2. Penyimpanan data ke database
3. Validasi panjang minimum dan maksimum input
4. Validasi format nomor telepon yang lebih spesifik
5. Interface grafis (GUI)

## Kontribusi

Silakan berkontribusi dengan cara:
1. Fork repository
2. Buat branch baru
3. Commit perubahan
4. Push ke branch
5. Buat Pull Request

## Lisensi

Program ini bersifat open source dan dapat digunakan secara bebas.