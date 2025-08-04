
### 📊 Jenis Analisis yang Digunakan
Analisis terhadap dataset `markets_cleaned.csv` mencakup beberapa pendekatan utama:

---

#### 1. 🧾 Analisis Deskriptif (Descriptive Analysis)
Digunakan untuk memahami struktur data dan karakteristik umum dari pasar.

**Contoh kegiatan:**
- Melihat jumlah pasar yang menjual masing-masing jenis produk.
- Menghitung statistik dasar (jumlah, rata-rata, dll).
- Visualisasi bar chart dan distribusi.

🛠️ **Tools yang digunakan:**
- `df.info()`, `df.describe()`, `df.sum()`
- Bar chart dengan `sns.barplot()`

---

#### 2. 🔍 Analisis Eksploratori Data (Exploratory Data Analysis / EDA)
Digunakan untuk menemukan pola, tren, dan hubungan antar variabel.

**Contoh kegiatan:**
- Heatmap korelasi antar fitur numerik.
- Scatterplot hubungan antara jumlah produk dan lama buka pasar.
- Mencari hubungan visual antar fitur.

🛠️ **Tools yang digunakan:**
- `sns.heatmap()`
- `sns.scatterplot()`

---

#### 3. 🤖 Analisis Prediktif (Predictive Analysis)
Menggunakan model regresi untuk memprediksi variabel target `months_open` berdasarkan `num_items_sold`.

**Model yang digunakan:**
- `Linear Regression`

**Evaluasi Model:**
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score (Koefisien Determinasi)

🛠️ **Tools yang digunakan:**
- `LinearRegression` dari `sklearn.linear_model`
- `mean_absolute_error`, `mean_squared_error`, `r2_score`

---

### 🧠 Kesimpulan
> Analisis yang digunakan mencakup pendekatan **deskriptif**, **eksploratif**, dan **prediktif**, untuk menggali wawasan dari data pasar serta membangun dasar model prediksi sederhana.
