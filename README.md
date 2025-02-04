# Prediksi Infeksi HIV/AIDS Menggunakan Machine Learning

Proyek ini bertujuan untuk membangun model prediksi infeksi HIV/AIDS berdasarkan data klinis dan biologis pasien. Dengan memanfaatkan algoritma CatBoostClassifier dan optimasi hyperparameter menggunakan Optuna, proyek ini diharapkan dapat memberikan akurasi tinggi serta mendukung inisiatif kesehatan global dalam mitigasi dampak AIDS.

## Latar Belakang

Infeksi AIDS (Acquired Immunodeficiency Syndrome) disebabkan oleh virus HIV (Human Immunodeficiency Virus) yang menyerang sistem kekebalan tubuh manusia. Berdasarkan laporan WHO pada tahun 2022:

- Lebih dari 38 juta orang hidup dengan HIV/AIDS di seluruh dunia.
- Jutaan kasus baru tercatat setiap tahunnya.

Diagnosis dini terhadap infeksi HIV/AIDS dapat mengurangi angka mortalitas secara signifikan. Namun, deteksi dini sering kali sulit dilakukan karena gejala tidak langsung terlihat, sehingga memerlukan pendekatan berbasis data untuk mendukung keputusan medis.

## Pentingnya Machine Learning

Teknologi machine learning telah terbukti memberikan prediksi akurat dalam berbagai kasus medis, termasuk prediksi infeksi HIV/AIDS. Dalam konteks analisis data pasien, beberapa indikator penting adalah:

- **Jumlah CD4/CD8**: Perubahan jumlah ini sering kali terkait dengan tingkat keparahan infeksi.
- **Durasi terapi antiretroviral**: Menjadi indikator penting dalam memprediksi perkembangan penyakit.

Algoritma seperti Random Forest, Gradient Boosting, dan CatBoost telah menunjukkan performa tinggi dalam prediksi berbasis data medis.

## Teknologi dan Metode

1. **Algoritma CatBoostClassifier**
   - Unggul dalam menangani data dengan fitur kategorikal.
   - Memberikan performa tinggi dalam analisis data medis.

2. **Optimasi Hyperparameter**
   - Menggunakan Optuna untuk menemukan konfigurasi model terbaik.

3. **Teknik Balancing Data**
   - Menggunakan SMOTE (Synthetic Minority Over-sampling Technique) untuk menangani dataset dengan ketidakseimbangan kelas yang tinggi.

## Referensi Penting

- WHO, 2022: Statistik global HIV/AIDS.
- Obermeyer dan Emanuel: Pendekatan big data dalam diagnosis medis.
- Dorogush et al.: Keunggulan CatBoost dalam menangani data dengan fitur kategorikal.
- SMOTE: Teknik balancing data untuk meningkatkan performa model klasifikasi.

---
Proyek ini diharapkan dapat memberikan kontribusi signifikan dalam pengembangan solusi berbasis teknologi untuk mengatasi tantangan HIV/AIDS secara global.
