# Python Mini Projects  
## Replikasi, Refactoring, dan Dokumentasi

---

## 1. Pendahuluan
Repositori ini berisi kumpulan **mini project Python** yang dikerjakan sebagai bagian dari **tugas individu** dengan pendekatan *replikasi berbasis pemahaman*. Proyek-proyek di dalam repositori ini mengacu pada materi video dan handbook *Python Projects for Beginners*.

Seluruh kode **tidak diunggah ulang secara mentah**, melainkan:
- Ditulis ulang dengan pemahaman sendiri
- Disusun ulang agar lebih terstruktur
- Diberi komentar penjelasan
- Direfaktorisasi menggunakan prinsip **DRY (Don’t Repeat Yourself)**

Repositori ini juga berfungsi sebagai **portofolio pembelajaran** untuk menunjukkan kemampuan dasar pemrograman Python dan praktik awal rekayasa perangkat lunak.

---

## 2. Tujuan Pengerjaan
Tujuan utama pengerjaan repositori ini adalah:
1. Memahami alur logika dan proses problem solving dalam proyek Python sederhana  
2. Melatih penggunaan struktur kontrol seperti percabangan dan perulangan  
3. Membiasakan penggunaan fungsi dan modularisasi kode  
4. Menerapkan struktur data yang sesuai (tuple, dictionary)  
5. Menerapkan prinsip **clean code** dan **DRY** melalui refactoring  
6. Mengelola dependency menggunakan virtual environment  
7. Menyusun dokumentasi teknis dalam Bahasa Indonesia  

---

## 3. Daftar Proyek dan Penjelasan

### 3.1 Dice Rolling Game
Program simulasi lempar dadu yang meminta input pengguna untuk melanjutkan atau menghentikan permainan. Setiap lemparan menghasilkan dua angka acak antara 1 hingga 6.

**Tujuan Pembelajaran:**
- Memahami perulangan tak terbatas (`while`)
- Menggunakan input pengguna
- Menghasilkan bilangan acak

**Konsep Utama:**
- Loop
- Input/Output
- Modul 

---

### 3.2 Number Guessing Game
Permainan menebak angka di mana komputer memilih angka acak antara 1 sampai 100. Program memberikan umpan balik apakah tebakan terlalu kecil, terlalu besar, atau benar.

**Tujuan Pembelajaran:**
- Melatih logika percabangan
- Menangani kesalahan input pengguna

**Konsep Utama:**
- `if / elif / else`
- Perulangan
- Exception handling (`try-except`)

---

### 3.3 Rock, Paper, Scissors Game
Permainan Batu–Gunting–Kertas antara pengguna dan komputer. Pilihan komputer ditentukan secara acak dan hasil permainan ditampilkan menggunakan emoji.

Program ini disusun secara modular dengan fungsi-fungsi terpisah agar mudah dibaca dan dipelihara.

**Tujuan Pembelajaran:**
- Membiasakan penggunaan fungsi
- Memisahkan logika dan tampilan
- Validasi input pengguna

**Konsep Utama:**
- Fungsi
- Dictionary
- Tuple
- Modularisasi

---

### 3.4 QR Code Generator
Program untuk menghasilkan QR Code dari teks atau URL yang dimasukkan oleh pengguna. QR Code disimpan dalam bentuk file gambar.

Program ini menggunakan **library pihak ketiga** dan dijalankan di dalam **virtual environment**.

**Tujuan Pembelajaran:**
- Menggunakan library eksternal
- Mengelola dependency proyek
- Bekerja dengan file output

**Konsep Utama:**
- Virtual environment
- Dependency management
- Third-party library (`qrcode`)

---

### 3.5 Refactoring – Applying the DRY Principle
Tahap refactoring dilakukan pada program **Rock, Paper, Scissors** dengan tujuan menghilangkan duplikasi kode dan meningkatkan keterbacaan.

**Refactoring yang dilakukan:**
- Menggunakan konstanta sebagai satu sumber nilai
- Menghindari pengulangan kondisi logika
- Menggunakan dictionary untuk aturan permainan
- Menyederhanakan fungsi penentuan pemenang

**Tujuan Pembelajaran:**
- Memahami pentingnya refactoring
- Menerapkan prinsip DRY
- Menulis kode yang lebih mudah dirawat

---

## 4. Struktur Repositori
Struktur repositori disusun agar rapi dan mudah dipahami.

python-mini-projects/
├── README.md
├── requirements.txt
├── .gitignore
├── src/
│ ├── dice_rolling/
│ ├── number_guessing/
│ ├── rock_paper_scissors/
│ ├── qr_code_generator/
│ └── refactoring_dry_principle/
└── docs/
├── dice-rolling/
├── number-guessing/
├── rock-paper-scissors/
├── qr-code-generator/
└── refactoring-dry-principle/

#Dokumentasi
dice-rolling
number-guessing
 rock-paper-scissors
qr-code-generator
refactoring-dry-principle
