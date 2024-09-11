# Predicting the Sale Prices of Bulldozers

## Deskripsi
Proyek ini bertujuan untuk memprediksi harga jual bulldozer menggunakan teknik machine learning. Dengan memanfaatkan karakteristik bulldozer dan data penjualan sebelumnya, kita dapat membuat model yang akurat untuk memperkirakan harga.

## 1. Definisi Masalah
> Seberapa baik kita dapat memprediksi harga jual masa depan dari bulldozer, berdasarkan karakteristik dan contoh sebelumnya dari harga jual bulldozer yang serupa?

## 2. Data
Data diunduh dari kompetisi Kaggle Bluebook for Bulldozers:
- [Data Kompetisi](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

Terdapat 3 set data utama:
- `Train.csv`: set pelatihan (data hingga akhir 2011).
- `Valid.csv`: set validasi (data dari 1 Januari 2012 - 30 April 2012).
- `Test.csv`: set pengujian (data dari 1 Mei 2012 - November 2012).

## 3. Evaluasi
Metrik evaluasi untuk kompetisi ini adalah RMSLE (root mean squared log error) antara harga lelang aktual dan prediksi.

Untuk informasi lebih lanjut, lihat:
- [Evaluasi Proyek](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation)

## 4. Fitur
Kaggle menyediakan data yang menjelaskan semua fitur dari dataset. Anda dapat melihatnya di Google Sheets:
- [Data Dictionary](https://docs.google.com/spreadsheets/d/1jW1AR7HwneJSosG2Fkca_IPnw-NyubNugllcmzr61kQ/edit?usp=sharing)

## 5. Instalasi
Untuk menjalankan proyek ini, pastikan Anda telah menginstal dependensi berikut:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
