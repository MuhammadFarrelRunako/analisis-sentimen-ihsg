# Hipotesis Proyek

## H1: Korelasi Sentimen & IHSG Return
- H0: ρ = 0 (tidak ada korelasi)
- H1: ρ &gt; 0 (korelasi positif signifikan)
- Uji: Pearson Correlation
- α = 0.05

## H2: Granger Causality
- H0: Sentimen tidak Granger-menyebabkan IHSG
- H1: Sentimen Granger-menyebabkan IHSG (lag 1–3)
- Uji: Granger Causality Test
- α = 0.05

## H3: Event Study
- H0: CAR = 0 (tidak ada abnormal return)
- H1: CAR ≠ 0 (ada abnormal return signifikan)
- Uji: Event Study t-test
- Window: [-5, +5]

## H4: Perbandingan NLP
- H0: Akurasi IndoBERT = Akurasi VADER
- H1: Akurasi IndoBERT &gt; Akurasi VADER
- Uji: Manual validation 200 samples