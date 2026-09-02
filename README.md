# 📊 Analisis Sentimen Berita Ekonomi vs Pergerakan IHSG

> Proyek analisis data end-to-end oleh Muhammad Farrel Runako  
> Mahasiswa Bisnis Digital | Durasi: 6 Minggu | 2019–2024

## 🎯 Tujuan
Menganalisis hubungan kausalitas antara sentimen berita ekonomi (Kompas, CNBC Indonesia, Kontan) dengan pergerakan Indeks Harga Saham Gabungan (IHSG).

## 🏗️ Struktur Proyek
├── data/           # Dataset mentah & hasil preprocessing
├── notebooks/      # Jupyter notebooks (EDA, NLP, Statistik)
├── src/            # Modul Python reusable
├── dashboard/      # Aplikasi Streamlit interaktif
├── reports/        # Laporan & presentasi
└── docs/           # Dokumen planning & metodologi
plain

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Statsmodels, Scikit-learn
- **NLP**: IndoBERT, VADER, Sastrawi
- **Visualisasi**: Matplotlib, Seaborn, Plotly
- **Dashboard**: Streamlit
- **Data**: yfinance, BeautifulSoup, newspaper3k

## 📅 Timeline
| Fase | Minggu | Status |
|------|--------|--------|
| Planning | 1 | ✅ |
| Data Collection | 1–2 | ⏳ |
| Data Preparation & EDA | 2 | ⏳ |
| NLP & Statistical Analysis | 3–4 | ⏳ |
| Dashboard Development | 5 | ⏳ |
| Reporting | 6 | ⏳ |

## 🚀 Cara Menjalankan
```bash
# 1. Clone repo
git clone https://github.com/MuhammadFarrelRunako/ihsg-sentiment-analysis.git

# 2. Masuk ke folder
cd ihsg-sentiment-analysis

# 3. Aktifkan virtual environment
venv\Scripts\activate        # Windows
source venv/bin/activate     # Mac/Linux

# 4. Install dependencies
pip install -r requirements.txt

# 5. Jalankan dashboard
streamlit run dashboard/app.py
📧 Kontak
Email: muhammadfarrelrunako1@gmail.com