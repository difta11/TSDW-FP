# NAMA ANGGOTA KELOMPOK 1:
| No | Nama                    | NRP        |
| -- | ----------------------- | ---------- |
| 1  | Bassa Bhaskara Desno G. | 5052241030 |
| 2  | M. Alief Afghani        | 5052241008 |
| 3  | M. Razan Thariq Aqil    | 5052241025 |
| 4  | Difta Raditya Pratama   | 5052241020 |

# Cara Menjalankan Ulang Proyek
## 1. Clone atau download repository
git clone https://github.com/difta11/TSDW-FP/tree/main/final-project
cd repo-spotify

## 2. Setup Virtual Environment
### **WINDOWS:**
python -m venv venv
venv\Scripts\activate

### **macOS/Linux:**
python3 -m venv venv
source venv/bin/activate

## 3. Install Dependensi
pip install -r requirements.txt

# Struktur File
```
final-project/
│
├── data/
│   ├── raw/                       # Dataset mentah
│   │   └── spotify_songs.csv
│   │
│   └── processed/                 # Dataset setelah dibersihkan
│       └── spotify_songs_cleaned.csv
│
├── notebooks/
│   └── final_project.ipynb        # Notebook analisis utama
│
├── requirements.txt               # Daftar package Python yang digunakan
└── README.md                      # Dokumentasi final project
```

# Deskripsi Proses Pengolahan Data
## 1. Import Dataset
Mengambil dataset Spotify dari folder data/raw.

## 2. Data Cleaning
### - Menghapus nilai kosong
### - Menghapus data duplikat
### - Normalisasi tipe data

## 3. Transformasi Data

### Pemilihan kolom penting

## 4. Export Data

### Data hasil pembersihan diekspor ke:
data/processed/spotify_songs_cleaned.csv

## 5. Analisis dan Visualisasi

### - Analisis pola tren banyak produksi genre dari tahun ke tahu
### - Analisis perubahan Rata-rata Tempo dan Valence dari Tahun ke Tahun
### - Heatmap korelasi

## 6. Table Ringkasan
### - Menghitung korelasi antara popularitas dengan fitur audio utama
### - Statistik Performa per Genre