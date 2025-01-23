# Prediksi Harga Saham dengan Machine Learning

## Deskripsi Proyek
Ini saya buat hanya untuk pembelajaran saya mengenai machine learning.
Proyek ini bertujuan untuk memprediksi harga penutupan saham menggunakan teknik Machine Learning. Saya mengambil data historis saham yang diunduh dari Yahoo Finance menggunakan pustaka `yfinance`.

## Pustaka yang Digunakan
- `yfinance`: Untuk mengunduh data saham
- `pandas`: Untuk manipulasi dan analisis data
- `numpy`: Untuk komputasi numerik
- `scikit-learn`: Untuk pemodelan pembelajaran mesin
- `matplotlib`: Untuk visualisasi data

## Langkah-Langkah
1. Mengunduh data saham dari Yahoo Finance
2. Memproses dan membersihkan data
3. Menambahkan fitur tambahan seperti rata-rata bergerak
4. Melatih model Linear Regression untuk memprediksi harga penutupan saham
5. Mengevaluasi dan memvisualisasikan kinerja model

## Hasil
Model Linear Regression menunjukkan Mean Squared Error (MSE) sebesar 0.972 dalam prediksi harga penutupan saham Apple Inc. (AAPL).

## Pustaka
Pustaka yang diperlukan:
   ```shell
   pip install yfinance pandas numpy scikit-learn matplotlib
