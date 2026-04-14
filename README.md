# Modul-Analisis-Multivariat-Menggunakan-Clustering

## Implementasi dan Perbandingan Metode Clustering (K-Means, K-Medians, DBSCAN, Mean Shift, dan Fuzzy C-Means) pada Dataset Kesehatan Ibu Hamil

**Disusun oleh:**
<br>
Cantika Latifatul Nur Ella (24031554023)
<br>
Sofia Dwi Kinasih (24031554079)

**Dosen Pengampu:**
Dinda Galuh Guminta, M.Stat.

---

## Deskripsi Penelitian

Penelitian ini membandingkan lima metode clustering untuk mengelompokkan pola risiko kesehatan ibu hamil berdasarkan dataset **Maternal Health Risk Assessment** yang memuat 1.205 observasi dan 11 variabel klinis.

Metode yang dibandingkan:
- **K-Means** — clustering berbasis rata-rata dengan Euclidean Distance
- **K-Medians** — pengembangan K-Means yang robust terhadap outlier menggunakan Manhattan Distance
- **DBSCAN** — clustering berbasis kepadatan, mampu mendeteksi noise
- **Mean Shift** — clustering adaptif tanpa asumsi jumlah cluster
- **Fuzzy C-Means** — clustering berbasis logika fuzzy dengan derajat keanggotaan ganda

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

## Dataset

Penelitian ini menggunakan dataset **Maternal Health Risk Assessment** yang diperoleh dari Mendeley Data, diterbitkan pada 1 November 2024. Dataset memuat 1.205 observasi dengan informasi klinis dan fisiologis ibu hamil mencakup indikator seperti usia, tekanan darah, kadar gula darah, suhu tubuh, dan BMI.

🔗 https://data.mendeley.com/datasets/p5w98dvbbk/1 

---

## Metode Analisis

- K-Means Clustering
- K-Medians Clustering
- DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- Mean Shift Clustering
- Fuzzy C-Means (FCM)
- Evaluasi dilakukan menggunakan **Silhouette Index**. 

Analisis dilakukan menggunakan bahasa pemrograman **R** dan dipublikasikan melalui **RPubs** 
🔗 https://rpubs.com/sofiadwik/1420940 
