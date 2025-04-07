# 🚗 Prediksi Harga Mobil Bekas Cars4u 📊

<div align="center">
  <img src="https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?ixlib=rb-1.2.1&auto=format&fit=crop&w=1200&h=400&q=80" alt="Analisis Mobil Bekas">
  
  [![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
  [![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)](https://pandas.pydata.org/)
  [![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-red.svg)](https://scikit-learn.org/)
  [![Statsmodels](https://img.shields.io/badge/Statsmodels-0.13+-purple.svg)](https://www.statsmodels.org/)
</div>

## 🌟 Ringkasan Proyek

Proyek ini menganalisis dataset **7.253 mobil bekas di India** untuk membangun model prediksi harga yang akurat menggunakan **Regresi Linear dan Polinomial**. Kami melakukan eksplorasi mendalam untuk menemukan faktor-faktor yang paling mempengaruhi nilai pasar mobil bekas dan menciptakan alat prediksi harga yang handal.

## 👨‍💻 Tim Pengembang

**Kelompok 2:**
| Foto | Nama | NIM |
|------|------|-----|
| <img src="https://ui-avatars.com/api/?name=Ganang+Setyo+Hadi&size=50&background=random" width="50" height="50" style="border-radius:50%"/> | **Ganang Setyo Hadi** | 2208107010052 |
| <img src="https://ui-avatars.com/api/?name=Alvia+Zuhra&size=50&background=random" width="50" height="50" style="border-radius:50%"/> | **Alvia Zuhra** | 2208107010003 |
| <img src="https://ui-avatars.com/api/?name=Al-Mahfuzh+Fadhlur+Rohman&size=50&background=random" width="50" height="50" style="border-radius:50%"/> | **Al-Mahfuzh Fadhlur Rohman** | 2208107010016 |
| <img src="https://ui-avatars.com/api/?name=Nurul+Uzratun+Nashriyyah&size=50&background=random" width="50" height="50" style="border-radius:50%"/> | **Nurul Uzratun Nashriyyah** | 2208107010030 |
| <img src="https://ui-avatars.com/api/?name=Azimah+Al-Huda&size=50&background=random" width="50" height="50" style="border-radius:50%"/> | **Azimah Al-Huda** | 2208107010069 |

## 🎯 Tujuan Proyek

- 🔍 Memahami faktor-faktor yang mempengaruhi harga mobil bekas di pasar India
- 🧮 Mengembangkan dan membandingkan model Regresi Linear dan Polinomial
- 💡 Memberikan wawasan untuk strategi penetapan harga di pasar mobil bekas
- 📏 Mengevaluasi kinerja model menggunakan berbagai metrik (RMSE, MAE, R²)

## 📊 Informasi Dataset

Dataset Cars4u berisi informasi detail tentang 7.253 mobil bekas di India, dengan 14 variabel:

<table align="center">
  <tr>
    <th>Fitur</th>
    <th>Deskripsi</th>
  </tr>
  <tr>
    <td>Name</td>
    <td>Merek dan model mobil</td>
  </tr>
  <tr>
    <td>Location</td>
    <td>Kota tempat mobil dijual</td>
  </tr>
  <tr>
    <td>Year</td>
    <td>Tahun pembuatan</td>
  </tr>
  <tr>
    <td>Kilometers_Driven</td>
    <td>Total kilometer yang ditempuh</td>
  </tr>
  <tr>
    <td>Fuel_Type</td>
    <td>Bensin, Diesel, Listrik, CNG, LPG</td>
  </tr>
  <tr>
    <td>Transmission</td>
    <td>Otomatis atau Manual</td>
  </tr>
  <tr>
    <td>Owner_Type</td>
    <td>Pemilik Pertama, Kedua, Ketiga, atau Keempat & Lebih</td>
  </tr>
  <tr>
    <td>Mileage</td>
    <td>Efisiensi bahan bakar (kmpl atau km/kg)</td>
  </tr>
  <tr>
    <td>Engine</td>
    <td>Kapasitas mesin (CC)</td>
  </tr>
  <tr>
    <td>Power</td>
    <td>Tenaga mesin maksimum (bhp)</td>
  </tr>
  <tr>
    <td>Seats</td>
    <td>Jumlah kursi</td>
  </tr>
  <tr>
    <td>New_Price</td>
    <td>Harga mobil baru dengan model sama (Lakh INR)</td>
  </tr>
  <tr>
    <td>Price</td>
    <td>Harga mobil bekas (Lakh INR)</td>
  </tr>
</table>

## 🛠️ Tahapan Pengerjaan Proyek

### 1️⃣ Pemahaman Dataset
- 📥 Loading dan eksplorasi dataset
- 📊 Statistik deskriptif dan visualisasi
- 📈 Mengkaji distribusi data dan hubungan antar variabel

### 2️⃣ Pra-pemrosesan Data
- 🧹 Menangani missing values dengan teknik yang tepat
- ✨ Feature engineering (mis. membuat 'Age' dari 'Year')
- 🔄 Encoding variabel kategorikal
- 🏷️ Membuat klasifikasi merek (Brand Classification)

### 3️⃣ Implementasi Model
- 📐 Membangun model Regresi Linear
- 📊 Mengimplementasikan Regresi Polinomial dengan optimasi derajat
- 🔪 Pembagian data train-test (70-30) untuk validasi

### 4️⃣ Evaluasi Model
- 📏 Metrik performa: RMSE, MAE, MAPE, R²
- 🔍 Perbandingan antara model Linear dan Polinomial
- 📉 Analisis residual dan verifikasi asumsi

### 5️⃣ Analisis Hasil
- 🧠 Interpretasi koefisien regresi
- 🎨 Visualisasi kesesuaian model (model fit)
- 💡 Ekstraksi wawasan pasar mobil bekas

## 📈 Temuan Utama

- **Kinerja Model**: Regresi Linear (R² = 0,894) terbukti lebih andal dibandingkan Regresi Polinomial yang menunjukkan overfitting parah
- **Faktor Penting yang Mempengaruhi Harga**:
  - **Usia Mobil**: Setiap tambahan tahun mengurangi harga sekitar 6,21%
  - **Tenaga Mesin**: Setiap kenaikan 1 bhp menaikkan harga sekitar 5,03%
  - **Jenis Bahan Bakar**: Mobil diesel memiliki harga sekitar 126% lebih tinggi dari baseline
  - **Kepemilikan**: Setiap perpindahan kepemilikan menurunkan nilai (Kedua: -14,44%, Ketiga: -21,78%)
- **Dampak Lokasi**: Variasi harga yang signifikan antar kota (Pune: +19,08%, Kochi: -24,93%)
- **Efek Merek**: Merek premium mempertahankan nilai jual kembali yang lebih tinggi

## 📊 Perbandingan Model

<table align="center">
  <tr>
    <th>Metrik</th>
    <th>Regresi Linear</th>
    <th>Regresi Polinomial</th>
  </tr>
  <tr>
    <td>R²</td>
    <td>0,894</td>
    <td>0,986</td>
  </tr>
  <tr>
    <td>RMSE (Train)</td>
    <td>6,50</td>
    <td>3,67</td>
  </tr>
  <tr>
    <td>RMSE (Test)</td>
    <td>7,70</td>
    <td>∞</td>
  </tr>
  <tr>
    <td>MAE (Train)</td>
    <td>2,28</td>
    <td>1,68</td>
  </tr>
  <tr>
    <td>MAE (Test)</td>
    <td>2,56</td>
    <td>~1,24e+107</td>
  </tr>
  <tr>
    <td>MAPE (Train)</td>
    <td>23,30%</td>
    <td>18,12%</td>
  </tr>
  <tr>
    <td>MAPE (Test)</td>
    <td>23,66%</td>
    <td>~1,90e+107%</td>
  </tr>
</table>

## 🖥️ Implementasi Teknis

### Teknologi yang Digunakan
- Python 3.x
- Library: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

### Struktur Repositori
```
.
├── data
│   └── raw-data
│       └── used_cars_data.csv
├── main.ipynb
├── README.md
└── soal.pdf
```
## 📝 Kesimpulan

Model Regresi Linear memberikan pendekatan yang stabil dan andal untuk memprediksi harga mobil bekas, dengan kinerja yang konsisten baik pada data training maupun testing. Meskipun Regresi Polinomial mencapai akurasi lebih tinggi pada training set, model ini mengalami overfitting parah dan gagal melakukan generalisasi pada data baru.

Prediktor utama untuk harga mobil meliputi usia, tenaga mesin, jenis bahan bakar, dan riwayat kepemilikan, dengan model yang mampu menjelaskan sekitar 89,4% variasi harga.

> *"Kadang, yang sederhana justru paling kuat."*  
> *"Regresi linear membuktikan bahwa stabilitas dan generalisasi lebih penting daripada sekadar akurasi di atas kertas."*

## 📚 Referensi

- Dataset asli: ["Cars4u" oleh Sukhmani Bedi di Kaggle](https://www.kaggle.com/datasets/sukhmanibedi/cars4u)
- [Dokumentasi Scikit-learn](https://scikit-learn.org/)
- [Dokumentasi Statsmodels](https://www.statsmodels.org/)

## 📬 Kontak

Jika Anda memiliki pertanyaan atau saran, silakan hubungi anggota tim kami melalui email kampus.

---

<div align="center">
  <p>💻 Dibuat dengan ❤️ oleh Kelompok 2 | Data Science 2022</p>
</div>