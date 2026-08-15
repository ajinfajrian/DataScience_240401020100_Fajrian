# Portofolio Data Science - Aktivitas Praktikum Sesi 1 s/d 7
---

## Identitas Mahasiswa
* **Nama Lengkap** : Fajrian Ichlasul Maruto
* **NIM** : 240401020100
* **Kelas** : IF401
* **Program Studi** : S1 PJJ Informatika
* **Institusi** : Universitas Siber Asia

---

## Deskripsi Repositori
Repositori ini dibangun dan didekasikan khusus sebagai pemenuhan berkas portofolio **Ujian Tengah Semester (UTS)** pada mata kuliah **Data Science (Genap 2025/2026)**. 

Portofolio ini merangkum seluruh aktivitas eksperimen interaktif berbasis Jupyter Notebook (`.ipynb`) dari Pertemuan 1 hingga Pertemuan 7. Alur pengerjaan di dalam repositori ini mengadopsi standar industri **CRISP-DM (Cross-Industry Standard Process for Data Mining)**, yang melatih pemrosesan data mentah yang tidak terstruktur (*dirty data*), eksplorasi statistik deskriptif (*Exploratory Data Analysis*), rekayasa fitur data (*data preprocessing*), hingga visualisasi prediktif menggunakan algoritma *Machine Learning Supervised Learning*.

---

## Daftar Isi

Seluruh lembar kerja berikut telah dieksekusi penuh secara bertahap dan mempertahankan rekaman output program (teks, tabel, dan grafik visual) tanpa memerlukan eksekusi ulang (*ready-to-view*):

| Sesi | Pembahasan Modul / Aktivitas Praktikum | Jenis Dataset yang Digunakan | Tautan File Kerja Interaktif |
| :---: | :--- | :---: | :---: |
| **01** | **Pengenalan & Sintaks Dasar Python**<br>• Konstruksi `print()`, variabel, enumerasi `list`, loop, dan f-string. | Python Native String | [Lihat Notebook Sesi 1](./Pertemuan1_Fajrian_Ichlasul_240401020100.ipynb) |
| **02** | **Struktur Data Dasar & Library Pandas**<br>• Inspeksi awal dimensi DataFrame, `.info()`, dan filter data berkelompok. | Titanic Open Dataset | [Lihat Notebook Sesi 2](./Pertemuan2_Fajrian_Ichlasul_240401020100.ipynb) |
| **03** | **Data Cleaning Pipeline**<br>• Handling missing values, standardisasi teks kategori, dan Clipping Outliers via IQR. | Housing Dirty CSV | [Lihat Notebook Sesi 3](./Pertemuan3_Fajrian_Ichlasul_240401020100.ipynb) |
| **04** | **Statistika Deskriptif & Analisis EDA**<br>• Perhitungan Mean, Median, Variance, Skewness, Kurtosis, dan Heatmap matriks. | Iris Dataset (Seaborn) | [Lihat Notebook Sesi 4](./Pertemuan4_Fajrian_Ichlasul_240401020100.ipynb) |
| **05** | **Visualisasi Data & Narasi Storytelling**<br>• Implementasi framework narasi visual kualitatif *What? So What? Now What?* | Titanic Open Dataset | [Lihat Notebook Sesi 5](./Pertemuan5_Fajrian_Ichlasul_240401020100.ipynb) |
| **06** | **Data Preparation & Preprocessing Pipeline**<br>• One-Hot Encoding, StandardScaler, dan Stratified Train-Test Split. | Titanic Open Dataset | [Lihat Notebook Sesi 6](./Pertemuan6_Fajrian_Ichlasul_240401020100.ipynb) |
| **07** | **Pengantar Machine Learning: Regresi Linear**<br>• Prediksi nilai kontinu (`fare`), evaluasi metrik MAE, RMSE, $R^2$, dan Residual plot. | Titanic Open Dataset | [Lihat Notebook Sesi 7](./Pertemuan7_Fajrian_Ichlasul_240401020100.ipynb) |
| **09** | **Algoritma Klasifikasi (Bagian 1):**<br>• Logistic Regression, Decision Trees, Confusion Matrix, Accuracy, Precision, Recall, F1-Score. | [Lihat Notebook Sesi 9](./Pertemuan9_Fajrian_Ichlasul_240401020100.ipynb) |
| **10** | **Algoritma Klasifikasi (Bagian 2):**<br>• Metode Ensemble (Random Forest) & penanganan Imbalanced Dataset. | [Lihat Notebook Sesi 10](./Pertemuan10_Fajrian_Ichlasul_240401020100.ipynb) |
| **11** | **Unsupervised Learning (Clustering):**<br>• K-Means, Hierarchical Clustering, Metode Elbow. | [Lihat Notebook Sesi 11](./Pertemuan11_Fajrian_Ichlasul_240401020100.ipynb) |
| **12** | **Asosiasi Data & Sistem Rekomendasi:**<br>• Algoritma Apriori, Collaborative/Content-Based Filtering. | [Lihat Notebook Sesi 12](./Pertemuan12_Fajrian_Ichlasul_240401020100.ipynb) |
| **13** | **Pengantar Deep Learning & NLP Dasar:**<br>• Artificial Neural Network & Analisis Sentimen Teks. | [Lihat Notebook Sesi 13](./Pertemuan13_Fajrian_Ichlasul_240401020100.ipynb) |

> *Catatan: Sesi 8 adalah jadwal pelaksanaan Ujian Tengah Semester (UTS), sedangkan Sesi 14-15 berfokus pada diskusi konseptual tata kelola data sehingga tidak menyertakan file kode.*

---

## Spesifikasi Tools & Modules

Eksperimen portofolio ini dikembangkan menggunakan ekosistem *cloud-computing* dengan spesifikasi infrastruktur sebagai berikut:

### 1. Perangkat Lunak Utama & Environment
* **Runtime Jaringan**: Google Colab Virtual Machine (tanpa instalasi lokal, mendukung akses GPU/TPU).
* **Bahasa Pemrograman**: Python (komunitas pemrograman terbesar di dunia).
* **Sistem Kontrol Versi**: GitHub Engine.

### 2. Pustaka Pemrosesan & Manipulasi Data (Data Wrangling)
* **`NumPy`**: Digunakan untuk operasi komputasi berbasis vektor dan manipulasi array multi-dimensi.
* **`Pandas`**: Berperan sebagai core engine pembuatan struktur data tabular (DataFrame), pembacaan file (CSV/JSON), dan penanganan nilai kosong.

### 3. Pustaka Analisis Statistik & Visualisasi Data
* **`SciPy`**: Digunakan untuk mengukur *Skewness* dan *Kurtosis* pada distribusi data.
* **`Matplotlib` & `Seaborn`**: Digunakan sebagai fondasi dasar pembuatan struktur objek grafik interaktif, seperti Heatmap, Boxplot, dan kurva distribusi.

### 4. Perangkat Machine Learning & Kecerdasan Buatan
* **`Scikit-Learn` (`sklearn`)**: Berperan penuh dalam fase pemodelan cerdas (Regresi, Klasifikasi Random Forest, K-Means Clustering), serta preprocessing pembagian *train-test split*.
* **`mlxtend`**: Digunakan untuk penambangan *Association Rules* (Algoritma Apriori).
* **`TensorFlow` & `Keras`**: Digunakan untuk membangun dan melatih arsitektur *Artificial Neural Network* (Deep Learning).

---

## Kesimpulan
Rangkaian praktikum dari Sesi 1 hingga Sesi 13 ini memberikan pemahaman yang sangat komprehensif bagi saya mengenai alur kerja seorang praktisi data profesional. 

Melalui pembelajaran di paruh pertama, saya menyadari bahwa algoritma *Machine Learning* yang rumit tidak akan memberikan hasil akurat tanpa didahului oleh pembersihan data (*Data Cleaning*) dan persiapan data (*Data Preprocessing*). Penerapan penguncian distribusi target lewat *stratified split* dan standardisasi skala fitur mengajarkan saya untuk tidak hanya menulis baris kode, tetapi mampu mengekstrak nilai bermakna dari data mentah.

Pada paruh kedua, pembelajaran bergeser ke pemahaman algoritma lanjutan. Saya belajar pentingnya pemilihan metrik evaluasi yang tepat (seperti *Recall* untuk data *Imbalanced*), bagaimana algoritma *Unsupervised* (K-Means & Apriori) mampu menemukan pola tersembunyi tanpa label target, hingga bagaimana Jaringan Saraf Tiruan (*Deep Learning*) dan ekstraksi NLP (TF-IDF) memungkinkan mesin memahami data teks yang kompleks. Portofolio ini menjadi pondasi dasar yang sangat kuat bagi saya untuk melangkah ke metodologi *Artificial Intelligence* tingkat lanjut di masa mendatang.
