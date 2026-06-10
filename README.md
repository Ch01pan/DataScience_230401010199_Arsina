
* **Nama Lengkap:** Arsina
* **NIM:** 230401010199
* **Kelas:** IF 405
* [cite_start]**Program Studi:** PJJ Informatika
* [cite_start]**Mata Kuliah:** Data Science
---


Halo guys, Mi Ciamo Sina!
setelah lama vakum, finnally aku comeback kuliah setelah sakit beberapa semester belakangan, wish me luck, bless u, and thanks to pak syahid as dosen matkul data science semester ini <3

---

## 3. Daftar Pertemuan & Topik Pembelajaran

Berikut adalah rincian materi dari Pertemuan 1 hingga 7 beserta tautan langsung ke notebook praktik terkait:

* **[Pertemuan 1: Pengenalan Data Science]**
    * Definisi dan pilar utama Data Science.
    * Siklus hidup proyek data menggunakan metodologi CRISP-DM.
    * Pengenalan lingkungan kerja Google Colab, Python, dan GitHub.
* **[Pertemuan 2: Struktur Data Python, NumPy & Pandas]**
    * Manipulasi list, tuple, dictionary, dan set.
    * Komputasi numerik dengan NumPy `ndarray`.
    * Eksplorasi data tabular dengan Pandas Series dan DataFrame (termasuk _filtering_ dan agregasi).
* **[Pertemuan 3: Data Cleaning: Missing Values, Outlier & Ekstraksi Data])**
    * Deteksi dan penanganan *missing values* serta data duplikat.
    * Penanganan *outlier* menggunakan metode IQR Fence dan Z-Score.
    * Ekstraksi data dari format JSON dan REST API publik.
* **[Pertemuan 4: Statistika Dasar & Analisis Data]**
    * Ukuran pemusatan (Mean, Median, Modus) dan penyebaran (Varians, Standar Deviasi, IQR).
    * Analisis univariat (Histogram, Boxplot) dan analisis bivariat (Korelasi Pearson/Spearman, Scatter Plot).
* **[Pertemuan 5: Visualisasi Data]**
    * Penerapan 5 prinsip visualisasi efektif (Clarity, Accuracy, Efficiency, Aesthetics, Context).
    * Pembuatan grafik dasar dengan Matplotlib (Bar chart, Line chart).
    * Visualisasi statistik tingkat lanjut dengan Seaborn dan pendekatan analisis analitik (*What? So what? Now what?*).
* **[Pertemuan 6: Persiapan Data]**
    * *Encoding* data kategorikal (Label, One-Hot, Ordinal Encoding).
    * *Feature Scaling* (MinMaxScaler, StandardScaler, RobustScaler).
    * Pemisahan dataset menjadi *Training Set* dan *Test Set* untuk mencegah *data leakage*.
* **[Pertemuan 7: Pengantar Machine Learning: Regresi Linear]**
    * Perbedaan *Supervised* vs *Unsupervised Learning*, serta Klasifikasi vs Regresi.
    * Implementasi algoritma Regresi Linear dengan `scikit-learn`.
    * Evaluasi performa model menggunakan metrik MAE, RMSE, dan R-Squared.

    ## 4. Tools & Libraries yang Digunakan

Proyek dan tugas dalam repository ini dibangun menggunakan tumpukan teknologi modern ekosistem Python:
* **Bahasa Pemrograman:** Python 3.x
* **Manipulasi & Analisis Data:** Pandas, NumPy
* **Pembersihan Data & Ekstraksi:** Missingno, Requests, json
* **Visualisasi Data:** Matplotlib, Seaborn
* **Machine Learning & Preprocessing:** Scikit-learn (SciPy)

---

## 5. Cara Menjalankan Notebook

Anda dapat menjelajahi dan menjalankan seluruh kode di dalam repository ini dengan dua cara:

### Opsi A: Melalui Google Colab (Paling Direkomendasikan)
1. Buka [Google Colaboratory](https://colab.research.google.com/) di browser Anda.
2. Pilih tab **GitHub** pada jendela pop-up.
3. Masukkan URL repository ini dan tekan Enter.
4. Pilih file `.ipynb` yang ingin Anda jalankan.
5. Google Colab sudah memiliki sebagian besar *library* yang dibutuhkan (Pandas, NumPy, Matplotlib, dll.) secara bawaan.

### Opsi B: Secara Lokal (Jupyter Notebook)
1. *Clone* repository ini ke komputer lokal Anda:
```bash
   git clone [URL_GITHUB_REPO_ANDA]
   ```
2. Pastikan Anda telah menginstal Python. Disarankan menggunakan *virtual environment*.
3. Instal semua dependensi yang diperlukan:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn missingno requests
   ```
4. Buka Jupyter Notebook di terminal:
```bash
   jupyter notebook
   ```
5. Akses file `.ipynb` melalui browser Anda.

---

## 6. Kesimpulan Perjalanan Belajar (Pertemuan 1–7)

Jujur, perjalanan dari Pertemuan 1 sampai 7 ini lumayan mengubah cara pandang saya. Kalau awalnya saya cuma melihat data sebagai deretan angka yang kaku, sekarang saya sadar kalau data itu sebenarnya "bahan baku" yang sangat strategis. Belajar kerangka kerja CRISP-DM di awal juga ngasih *insight* penting buat saya: sebelum repot-repot ngoding, paham tujuan bisnisnya itu justru yang paling utama.

Pas masuk ke bagian teknis pakai Pandas untuk *Data Cleaning*, saya baru ngerasain sendiri realitanya—ternyata bener ya, beresin data yang kotor (kayak *missing values* atau *outlier*) itu memang fase yang paling menantang dan makan waktu. Nah, sebagai seorang desainer, bagian visualisasi data jelas jadi favorit saya. Tapi modul ini sedikit mengubah *mindset* saya, karena dalam Data Science, grafik itu nggak cukup cuma sekadar estetik atau cantik dilihat. Akurasi, efisiensi, dan kejelasan pesannya (*clarity*) justru jauh lebih penting.

Terakhir, waktu mulai kenalan sama *Machine Learning* lewat algoritma Regresi Linear, saya dapat satu pelajaran berharga: sebagus apa pun algoritmanya, hasilnya bakal percuma kalau data awalnya nggak disiapin dengan bener (*encoding*, *scaling*, *split data*). Intinya, buat saya Data Science itu sama sekali bukan "sulap" yang tiba-tiba ngasih prediksi jitu. Ini murni proses yang logis, bertahap, dan sistematis banget buat ngubah catatan masa lalu jadi wawasan yang berharga.