# NAMA ANGGOTA KELOMPOK:
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

# Install Dependensi
pip install -r requirements.txt

# Struktur File
project-spotify/
│
├── data/
│   └── spotify_raw.csv          # Dataset asli
│
├── output/
│   └── data_clean.csv           # Data hasil cleaning
│
├── src/
│   ├── cleaning.py              # Modul untuk cleaning data
│   ├── analysis.py              # Analisis & visualisasi
│   └── utils.py                 # Fungsi tambahan
│
├── main.py                      # Script utama menjalankan project
├── requirements.txt             # Daftar library yang diperlukan
└── README.md                    # Dokumentasi proyek
