### Datasets

- KAGGLE #1 -> 10000 Data
- KAGGLE #2 -> 499 Data
- Pemkomedan -> 315 Data

### PRE-PROCESSING DATA

1. Cleaning
   - Memeriksa total data
   - Memeriksa data None / NaN
     - Mengisi data None / NaN dengan Mean
   - Memeriksa format nilai data
     - Menyelaraskan format nilai data
   - Menghapus duplikat
2. Integration
   - Menggabungkan seluruh datasets menjadi 1 big data
3. Transformation
   - Ubah format gender menjadi nominal
   - Interpolasi nilai yang tidak memiliki LMS
   - Cari nilai z-score stunting & wasting
   - Tentukan label pada setiap data
   - Oversampling data dengan SMOTE untuk menyeimbangkan data
   - Normalisasi data
4. Reduction
   - Mengurangi jumlah data pada dataset latih dengan menghapus duplikat
