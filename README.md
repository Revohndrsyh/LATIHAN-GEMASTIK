readme_content = """
# 📊 Kesimpulan Analisis Sleep Health and Lifestyle Dataset

## 1. Klasifikasi – Quality of Sleep

- Model Random Forest Classifier mampu memprediksi **Quality of Sleep** dengan **akurasi 97,3%**.
- Nilai **precision**, **recall**, dan **f1-score** pada tiap kelas rata-rata di atas 0,97.
- Matriks kebingungan (confusion matrix) menunjukkan prediksi model sangat akurat pada hampir seluruh kelas.

**Interpretasi:**  
Model klasifikasi sangat efektif membedakan kualitas tidur berdasarkan fitur-fitur numerik yang tersedia dalam dataset.

---

## 2. Regresi – Sleep Duration

- Model Linear Regression menghasilkan:
  - **MAE (Mean Absolute Error):** 0.29 jam
  - **RMSE (Root Mean Squared Error):** 0.35 jam
  - **R² Score:** 0.81
- Artinya, sekitar **81% variasi durasi tidur** bisa dijelaskan oleh fitur dalam dataset.

**Interpretasi:**  
Model regresi cukup baik dalam memprediksi lama tidur, dengan error rata-rata sekitar 17–21 menit.

---

## 3. Insight Data

- Fitur numerik seperti aktivitas fisik, tekanan darah, detak jantung, dan langkah harian berpengaruh besar pada kualitas dan durasi tidur.
- Performa model sangat baik, menunjukkan data cukup informatif dan proses preprocessing sudah tepat.
- Kolom `Sleep Disorder` memiliki missing value yang perlu ditangani jika ingin digunakan untuk analisis lebih lanjut.


---

## 4. Kesimpulan Umum

- **Prediksi kualitas dan durasi tidur** dapat dilakukan secara akurat menggunakan fitur gaya hidup dan kesehatan dasar.
- **Data sudah bersih** dan layak untuk pemodelan machine learning, kecuali pada kolom `Sleep Disorder` yang perlu penanganan missing value.
- **Strategi preprocessing dan fitur** yang digunakan sudah optimal dan terbukti menghasilkan model dengan performa tinggi.
