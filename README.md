
# Analisis Tingkat Attrition Karyawan - Jaya Jaya Maju

## 1. Latar Belakang Masalah

Perusahaan Jaya Jaya Maju mengalami tingkat attrition karyawan yang tinggi, yang berdampak pada produktivitas dan efisiensi operasional. Untuk itu, dilakukan analisis data untuk mengetahui faktor-faktor utama penyebab attrition dan membangun model prediksi untuk membantu HR dalam mengambil tindakan pencegahan yang lebih baik.

## 2. Preparation Run Program

Untuk menjalankan program ini, ikuti langkah-langkah berikut:

1. **Clone repository:**
    ```bash
    git clone https://github.com/<username>/<repo-name>.git
    cd submission
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Jalankan prediksi:**
    ```bash
    python prediction.py
    ```

4. **Buka notebook analisis:**
    Buka file `notebook.ipynb` menggunakan Jupyter Notebook untuk melihat analisis lengkap.

5. **Dashboard Metabase:**
    - Gunakan file `metabase.db.mv.db` untuk melihat dashboard di Metabase lokal Anda.
    - Dashboard berisi insight dari data attrition berdasarkan beberapa fitur penting.

## 3. Penjelasan Hasil Prediksi

Model machine learning yang dibangun mampu mengidentifikasi karyawan dengan potensi tinggi untuk mengundurkan diri. Beberapa fitur penting berdasarkan hasil feature importance antara lain:
- OverTime
- StockOptionLevel
- MaritalStatus
- JobSatisfaction
- TotalWorkingYears

Model ini dapat digunakan untuk memprediksi kemungkinan attrition dari karyawan baru maupun yang sedang aktif bekerja.

## 4. Recommendation Action

Berdasarkan hasil analisis dan prediksi, beberapa langkah yang direkomendasikan adalah:

- Meningkatkan kepuasan lingkungan kerja, khususnya bagi karyawan yang bekerja lembur secara rutin.
- Menyediakan opsi saham dan benefit yang kompetitif untuk meningkatkan retensi.
- Menyediakan dukungan tambahan bagi karyawan lajang yang berisiko lebih tinggi untuk attrition.
- Meningkatkan program kepuasan kerja dan kepemimpinan.

## 5. Conclusion

Dengan memahami faktor-faktor utama penyebab attrition dan membangun sistem prediktif, perusahaan dapat melakukan intervensi lebih awal terhadap potensi kehilangan karyawan. Penggunaan data sebagai dasar pengambilan keputusan HR akan meningkatkan efisiensi dan mempertahankan karyawan berpotensi tinggi di dalam organisasi.
