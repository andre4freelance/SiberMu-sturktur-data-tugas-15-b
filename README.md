# 📋 Tugas Praktek 15 - Queue (Antrian)

Program implementasi struktur data **Queue (Antrian)** menggunakan bahasa C++.

## 📖 Deskripsi

Program ini mengimplementasikan struktur data **Queue (Antrian) Linear** dengan konsep **FIFO (First In, First Out)** — data yang pertama masuk akan menjadi data yang pertama keluar. Queue diimplementasikan menggunakan **array statis** dengan kapasitas maksimum 20 elemen.

## ✨ Fitur

| Fitur | Fungsi | Keterangan |
|-------|--------|------------|
| **Enqueue** | `enqueue()` | Menambahkan data ke bagian belakang antrian |
| **Dequeue** | `dequeue()` | Mengambil data dari bagian depan antrian |
| **Print Queue** | `printQueue()` | Menampilkan seluruh isi antrian |
| **Cek Penuh** | `isFull()` | Mengecek apakah antrian sudah penuh |
| **Cek Kosong** | `isEmpty()` | Mengecek apakah antrian masih kosong |

## 🛠️ Struktur Data

```cpp
struct Queue {
    int front, rear, data[MAX];
};
```

- `front` — indeks elemen terdepan
- `rear` — indeks elemen terbelakang (jumlah elemen)
- `data[MAX]` — array penyimpan data antrian (MAX = 20)

## 🚀 Cara Menjalankan

### Prasyarat
- Compiler C++ (g++, MinGW, atau sejenisnya)

### Kompilasi & Jalankan

```bash
g++ -o main main.cpp
./main
```

### Contoh Penggunaan

```
--------------------
    Menu Pilihan
--------------------
 [1] Enqueue
 [2] Dequeue
 [3] Keluar

--------------------
Masukkan pilihan : 1
Masukkan Data : 10
Data ditambahkan
QUEUE : 10

Masukkan pilihan : 1
Masukkan Data : 20
Data ditambahkan
QUEUE : 10,20

Masukkan pilihan : 2
Mengambil data "10"...
QUEUE : 20
```

## 📂 Struktur File

```
├── main.cpp              # Source code utama program Queue
├── README.md             # Dokumentasi proyek
└── antrian_page-*.jpg    # Referensi gambar soal tugas
```
