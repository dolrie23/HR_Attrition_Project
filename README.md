
# Analisis Tingkat Attrition Karyawan - Jaya Jaya Maju

## 1. Latar Belakang Masalah

Perusahaan Jaya Jaya Maju mengalami tingkat attrition karyawan yang tinggi (>10% Attrition Ratio), yang berdampak pada produktivitas dan efisiensi operasional. Untuk itu,
perlu dilakukan analisis data untuk mengetahui faktor-faktor utama penyebab attrition dan membangun model prediksi untuk membantu HR dalam mengambil tindakan pencegahan yang lebih baik.

## 2. Preparation Run Program

Untuk menjalankan notebook ini, ikuti langkah-langkah berikut:

1. **Clone repository:**
    ```bash
    git clone https://github.com/dolrie23/HR_Attrition_Project.git
    cd HR_Attrition_Project
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3. **Jika perlu run Notebook:**
   
   Membutuhkan data employee dan environment notebook
   
   ```
   $ conda create --n venv "python=<version>"
   $ conda activate venv
   ```
   
4. **Jalankan prediksi:**

    ```
    python prediction.py
    ```

5. **Buka notebook analisis:**
    
   Buka file `notebook.ipynb` menggunakan Jupyter Notebook untuk melihat analisis lengkap.


6. **Dashboard Metabase:**
      
    - Email Metabase: danielsimanjuntak2305@gmail.com dan password: root123
    - Gunakan file `metabase.db.mv.db` untuk melihat dashboard di Metabase lokal Anda.
    - Dashboard berisi insight dari data attrition berdasarkan beberapa fitur penting.

## 3. Penjelasan Hasil Prediksi

Model machine learning yang dibangun mampu mengidentifikasi karyawan dengan potensi tinggi untuk mengundurkan diri. 
Beberapa fitur penting berdasarkan hasil feature importance antara lain:
- OverTime
- StockOptionLevel
- MaritalStatus
- JobSatisfaction
- TotalWorkingYears
- EnvironmentSatisfaction
- YearsAtCompany
- Age
- YearsWithCurrManager
- MonthlyIncome

## 4. Recommendation Action

Berdasarkan hasil analisis dan prediksi, beberapa langkah yang direkomendasikan adalah:

- Mengevaluasi kepuasan lingkungan kerja, khususnya bagi karyawan yang bekerja lembur secara rutin.
- Menyediakan opsi saham dan benefit yang kompetitif untuk meningkatkan retensi.
- Menyediakan dukungan tambahan bagi karyawan muda yang berisiko lebih tinggi untuk attrition.
- Meningkatkan program mentoring dan penetapan jenjang karir yang pasti.

## 5. Conclusion

Dengan memahami faktor-faktor utama penyebab attrition dan membangun sistem prediktif, 
perusahaan dapat melakukan intervensi lebih awal terhadap potensi kehilangan karyawan. 
Penggunaan data sebagai dasar pengambilan keputusan HR akan meningkatkan efisiensi dan 
mempertahankan karyawan berpotensi tinggi.
