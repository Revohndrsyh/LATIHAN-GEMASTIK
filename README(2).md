# 📊 Kesimpulan Analisis Dataset `markets_cleaned.csv`

## 🛒 Produk Utama yang Dijual
- Produk yang paling sering dijual di pasar:
  - 🥬 **Sayuran** (`vegetables`)
  - 🍎 **Buah-buahan** (`fruits`)
  - 🍱 **Makanan siap saji** (`prepared`)
- Produk yang jarang ditemukan di pasar:
  - 🍷 **Wine**
  - 🍄 **Mushrooms**
  - 🧈 **Tofu**

## 🔗 Hubungan antara Produk & Lama Buka Pasar
- Terdapat **hubungan positif** antara jumlah produk yang dijual (`num_items_sold`) dan lama operasional pasar (`months_open`).
- Semakin banyak jenis produk yang dijual, semakin besar kemungkinan pasar telah buka lebih lama.
- Visualisasi scatterplot menunjukkan bahwa pasar dengan diversifikasi produk yang tinggi cenderung **lebih bertahan lama**.

## 🤖 Hasil Prediksi & Evaluasi Model Regresi
- Model yang digunakan: **Linear Regression**
- Tujuan: Memprediksi `months_open` berdasarkan `num_items_sold`
- **Hasil Evaluasi:**
  - 📉 **MAE (Mean Absolute Error):** Nilai rendah → prediksi cukup akurat
  - 📊 **RMSE (Root Mean Squared Error):** Menunjukkan deviasi kecil dari nilai aktual
  - 📈 **R² Score:** Mendekati 1 → Model menjelaskan sebagian besar variansi data

## 🧩 Insight dari Korelasi (Correlation Heatmap)
- Fitur yang berkorelasi positif terhadap jumlah produk dan lama buka:
  - 🍇 `fruits`
  - 🥕 `vegetables`
  - 🍖 `meat`
- Heatmap korelasi memperlihatkan pola bahwa pasar yang menjual lebih banyak produk ini cenderung lebih sukses dan bertahan lama.

## 🎯 Rekomendasi
- Fokus pengembangan pasar baru sebaiknya pada produk-produk dengan korelasi tinggi seperti sayur, buah, dan daging.
- Pertimbangkan pendekatan **segmentasi pasar** berbasis komposisi produk (clustering).
- Model regresi sederhana bisa digunakan sebagai alat prediksi awal keberlangsungan pasar berdasarkan jumlah produk yang dijual.

---

🛠️ **Tools dan Library yang Digunakan:**
- `pandas`, `matplotlib`, `seaborn`, `sklearn.linear_model`, `sklearn.metrics`
- Teknik: Descriptive Analysis, Exploratory Data Analysis (EDA), Predictive Modeling, Correlation Analysis
