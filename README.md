# Dokumentasi Dataset Agroklimatik Indonesia

## 1. Informasi Dataset

- **Nama Dataset:** Nationwide Agroclimatic Dataset for Indonesia
- **Sumber Dataset:** Mendeley Data
- **Link Dataset:** https://data.mendeley.com/datasets/3pfbdbzfff/1
- **Format Data:** Parquet
- **Jumlah Baris:** 2.235.636
- **Jumlah Kolom:** 23
- **Penggunaan:** Eksplorasi dan analisis data agroklimatik di Indonesia.

## 2. Deskripsi Dataset

Dataset ini berisi informasi agroklimatik wilayah Indonesia yang dapat digunakan untuk menganalisis kondisi iklim dan indikator agroklimat.

Data disimpan dalam format Parquet dan terdiri dari beberapa file berdasarkan tahun serta file hasil pemrosesan.

## 3. Struktur Dataset

Dataset disimpan dalam direktori:

`data/raw/agroclimatic_indonesia/data/`

Struktur folder:

- `raw/`: Berisi data tahunan dari 2016 sampai 2025.
- `processed/`: Berisi dataset hasil pemrosesan.
- `code/`: Berisi kode yang disediakan bersama dataset.
- `metadata/`: Berisi informasi metadata dataset.

File utama yang digunakan dalam penelitian:

`processed/agroclimate_with_indicators.parquet`

## 4. Hasil Pemeriksaan Awal

Berdasarkan proses profiling menggunakan Polars, diperoleh:

| Informasi | Hasil |
|---|---:|
| Jumlah baris | 2.235.636 |
| Jumlah kolom | 23 |
| Format | Parquet |
| Library profiling | Polars |
| Library analitik | DuckDB |

Dataset memenuhi persyaratan minimal tugas, yaitu lebih dari 1 juta baris.

## 5. Cara Mendapatkan Dataset

1. Buka tautan sumber dataset di atas.
2. Unduh dataset dari Mendeley Data.
3. Ekstrak file ZIP.
4. Letakkan folder hasil ekstraksi pada `data/raw/agroclimatic_indonesia/`.
5. Jalankan notebook profiling untuk memeriksa dataset.

## 6. Catatan

File dataset mentah tidak disertakan dalam repository GitHub karena ukurannya relatif besar. Pengguna dapat mengunduh dataset melalui sumber yang telah dicantumkan di atas.