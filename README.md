# Modul-Analisis-Multivariat-Menggunakan-Clustering

## Implementasi dan Perbandingan Metode Clustering (K-Means, K-Medians, DBSCAN, Mean Shift, dan Fuzzy C-Means) pada Dataset Kesehatan Ibu Hamil

**Disusun oleh:**
<br>
Cantika Latifatul Nur Ella (24031554023)
<br>
Sofia Dwi Kinasih (24031554079)

**Dosen Pengampu:**
<br>
Dinda Galuh Guminta, M.Stat.

---

## Deskripsi Dataset

Penelitian ini membandingkan lima metode clustering untuk mengelompokkan pola risiko kesehatan ibu hamil berdasarkan dataset **Maternal Health Risk Assessment** yang diperoleh dari Mendeley Data, diterbitkan pada 1 November 2024. Dataset memuat 1.205 observasi dan 11 variabel.
<br>
🔗 https://data.mendeley.com/datasets/p5w98dvbbk/1 

---

## Variabel Penelitian

| Simbol | Nama Variabel                  |
|-------:|-------------------------------|
| X1     | Usia                          |
| X2     | Tekanan darah sistolik        |
| X3     | Tekanan darah diastolik       |
| X4     | Gula darah                    |
| X5     | Suhu tubuh                    |
| X6     | Indeks massa tubuh (BMI)      |
| X7     | Komplikasi sebelumnya         |
| X8     | Diabetes melitus sebelumnya   |
| X9     | Diabetes gestasional          |
| X10    | Kesehatan mental              |
| X11    | Detak jantung                 |

---

## Metode Analisis

- **K-Means Clustering** — clustering berbasis rata-rata dengan Euclidean Distance
- **K-Medians Clustering** — pengembangan K-Means yang robust terhadap outlier menggunakan Manhattan Distance
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** — clustering berbasis kepadatan, mampu mendeteksi noise
- **Mean Shift Clustering** — clustering adaptif tanpa asumsi jumlah cluster
- **Fuzzy C-Means (FCM)** — clustering berbasis logika fuzzy dengan derajat keanggotaan ganda
- Evaluasi dilakukan menggunakan **Silhouette Index**.

Analisis dilakukan menggunakan bahasa pemrograman **R** dan dipublikasikan melalui **RPubs**
<br>
🔗 https://rpubs.com/sofiadwik/1420940 
