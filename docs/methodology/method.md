# Metodologi Proyek

## NLP Pipeline
1. IndoBERT (indobenchmark/indobert-base-p1) → 3 kelas: POSITIVE, NEGATIVE, NEUTRAL
2. VADER (vaderSentiment) → compound score
3. Preprocessing: Sastrawi stopword + regex cleaning

## Statistical Pipeline
1. ADF Test → stasioneritas
2. Differencing (jika perlu)
3. Granger Causality (lag 1–5, pilih optimal via AIC)
4. VAR Model → Impulse Response Function
5. Event Study → CAR analysis

## Tools
- Python 3.10+
- Google Colab (GPU) untuk IndoBERT
- VS Code untuk development
- Streamlit untuk dashboard