# Pertemuan 09 — List dan Pengolahan Data Numerik 

## Identitas

- **Nama:** Ziana Alfia Zahra
- **NIM:** 2225250076
- **Kelas:** 3A

## Tujuan

Mempelajari penggunaan list dalam Python, meliputi pembuatan list, pengaksesan indeks dan slicing, manipulasi data, pengolahan nilai numerik, penyaringan nilai kelulusan, serta penggunaan fungsi sederhana.

## Struktur Proyek

```text
pertemuan-09-list-2225250076/
├── .gitignore
├── README.md
├── latihan/
│   ├── 01_buat_list.py
│   ├── 02_indeks_slicing.py
│   ├── 03_manipulasi_list.py
│   ├── 04_agregasi_nilai.py
│   ├── 05_filter_kelulusan.py
│   └── 06_fungsi_statistik.py
└── praktik/
    └── analisis_nilai_mahasiswa.py
```

**Keterangan:**
- Folder `latihan/` berisi enam program latihan tentang list dan pengolahan data numerik.
- Folder `praktik/` berisi program analisis nilai mahasiswa.
- File `.gitignore` digunakan untuk mengabaikan file atau folder tertentu yang tidak perlu dimasukkan ke Git.
- File `README.md` berisi identitas, tujuan, struktur proyek, cara menjalankan program, hasil pengujian, dan refleksi.

## Cara Menjalankan Program

Pastikan Python sudah terpasang dan terminal berada di folder utama proyek.

Jalankan program latihan dengan perintah berikut:

```bash
python latihan/01_buat_list.py
python latihan/02_indeks_slicing.py
python latihan/03_manipulasi_list.py
python latihan/04_agregasi_nilai.py
python latihan/05_filter_kelulusan.py
python latihan/06_fungsi_statistik.py
```

Untuk menjalankan program praktik:

```bash
python praktik/analisis_nilai_mahasiswa.py
```

Jika perintah `python` tidak dikenali, sesuaikan dengan perintah Python yang tersedia di komputer.

## Test Case

Hasil aktual dan status diisi berdasarkan hasil program setelah dijalankan.

| Program | Data uji | Hasil yang diharapkan | Hasil aktual | Status |
|---|---|---|---|---|
| `01_buat_list.py` | `[75, 80, 65, 90, 88]` | List ditampilkan dan banyak data = 5 | Isi setelah diuji | Belum diuji |
| `02_indeks_slicing.py` | `[75, 80, 65, 90, 88, 70]` | Indeks pertama = 75, indeks terakhir = 70, `nilai[:3]` = `[75, 80, 65]`, `nilai[1:4]` = `[80, 65, 90]` | Isi setelah diuji | Belum diuji |
| `03_manipulasi_list.py` | `[75, 80, 65]` | Setelah perubahan, list = `[75, 70, 82, 90]` | Isi setelah diuji | Belum diuji |
| `04_agregasi_nilai.py` | `[75, 80, 65, 90, 88]` | Total = 398, rata-rata = 79.60, minimum = 65, maksimum = 90 | Isi setelah diuji | Belum diuji |
| `05_filter_kelulusan.py` | `[75, 55, 80, 60, 45, 90]` | Nilai lulus = `[75, 80, 60, 90]`, jumlah lulus = 4 | Isi setelah diuji | Belum diuji |
| `06_fungsi_statistik.py` | `[75, 80, 65, 90, 88]` | Rata-rata = 79.60 | Isi setelah diuji | Belum diuji |
| `analisis_nilai_mahasiswa.py` | `[78, 55, 90, 67, 60, 82, 45, 71, 88, 59]` | Banyak data = 10, total = 695, rata-rata = 69.50, minimum = 45, maksimum = 90, nilai lulus = `[78, 90, 67, 60, 82, 71, 88]`, jumlah lulus = 7, belum lulus = 3 | Isi setelah diuji | Belum diuji |

## Refleksi

1. **Hal yang dipahami:** List memudahkan penyimpanan dan pengolahan banyak data dalam satu variabel. Indeks digunakan untuk mengakses elemen, sedangkan slicing digunakan untuk mengambil sebagian elemen list.

2. **Kesalahan yang diperbaiki:** Memahami bahwa indeks list dimulai dari `0`, sehingga pengaksesan elemen harus menggunakan indeks yang sesuai dengan posisi data. Selain itu, fungsi rata-rata perlu memeriksa apakah list kosong agar tidak terjadi pembagian dengan nol.