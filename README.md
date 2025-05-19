# Analisis Sentimen dan Linguistik Komentar Publik terhadap Kebijakan Militer Menggunakan Model RoBERTa

Proyek ini bertujuan untuk menganalisis sentimen dan karakteristik linguistik dari komentar publik di media sosial terhadap kebijakan militer di Indonesia. Dengan menggunakan model pralatih `IndoRoBERTa`, kami melakukan klasifikasi sentimen dan eksplorasi fitur linguistik untuk memahami persepsi masyarakat.

## 📌 Tujuan Proyek
- Mengklasifikasikan komentar publik menjadi kategori **positif**, **netral**, atau **negatif** menggunakan model RoBERTa berbahasa Indonesia.
- Mengekstraksi dan menganalisis pola linguistik dari setiap kategori sentimen.
- Menyediakan visualisasi hasil analisis berupa word cloud, distribusi sentimen, dan metrik evaluasi model.

## 🛠 Teknologi yang Digunakan
- Python 3.10+
- HuggingFace Transformers (`w11wo/indonesian-roberta-base-sentiment-classifier`)
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn, WordCloud
- Jupyter Notebook

## 📂 Struktur Direktori
├── data/ # Dataset komentar publik (csv/json)
├── model/ # File hasil fine-tuning model (jika ada)
├── notebooks/ # Jupyter Notebooks untuk preprocessing, training, analisis
├── output/ # Grafik, wordcloud, dan laporan hasil
├── src/ # Script modular (preprocessing, training, evaluation)
├── README.md # Deskripsi proyek


## 🔍 Fitur Proyek
- **Klasifikasi Sentimen**: Menggunakan model IndoRoBERTa dari HuggingFace untuk klasifikasi 3 kelas.
- **Analisis Linguistik**: Menghitung frekuensi kata, TF-IDF, dan kata kunci dominan per kategori sentimen.
- **Visualisasi Data**:
  - WordCloud untuk masing-masing sentimen.
  - Grafik distribusi sentimen.
  - Confusion matrix dan classification report.
- **Perbandingan Model** *(opsional)*: Melibatkan baseline lain seperti Logistic Regression atau SVM.


