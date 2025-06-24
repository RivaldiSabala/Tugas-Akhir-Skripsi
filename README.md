# Tugas-Akhir-Skripsi
# 🧠 Analisis Sentimen Pemilihan Kabinet Menteri 2024–2029 di Media Sosial X Menggunakan LSTM

Proyek ini merupakan bagian dari Tugas Akhir yang bertujuan untuk menganalisis sentimen masyarakat terhadap pemilihan kabinet menteri periode 2024–2029 menggunakan metode Long Short-Term Memory (LSTM). Data diambil dari media sosial X (Twitter) dan dianalisis menggunakan Natural Language Processing (NLP) dan deep learning.

---

## 🔍 Tujuan Penelitian

Menganalisis sentimen publik terhadap tokoh-tokoh kabinet menteri menggunakan data dari media sosial, dengan klasifikasi:
- 📈 **Positif**
- ⚪ **Netral**
- 📉 **Negatif**

---

## 🗂️ Struktur Folder


---

## ⚙️ Teknologi yang Digunakan

- Python 3.x
- TensorFlow & Keras
- Scikit-learn
- Pandas, NumPy, Matplotlib
- Sastrawi (stemming Bahasa Indonesia)
- Snscrape (pengambilan data dari media sosial X)

---

## 🔄 Alur Proses

1. **Pengumpulan Data**: menggunakan snscrape dari media sosial X
2. **Praproses Data**:
   - Cleansing teks
   - Case Folding
   - Tokenisasi
   - Normalisasi
   - Stopword removal
   - Stemming
3. **Ekstraksi Fitur**: Term Frequency - Inverse Document Frequency (TF-IDF)
4. **Modeling**: Arsitektur LSTM untuk klasifikasi sentimen
5. **Evaluasi Model**: Confusion Matriks dan AUC-ROC
6. **Visualisasi**: grafik performa dan distribusi sentimen

---

## 🧪 Contoh Output

```bash
Prediksi: Positif (92.5%)

