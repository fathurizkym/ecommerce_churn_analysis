Latar Belakang
-------------
Salah satu jenis taxi yang beroperasi di New York City yaitu Street-hail Liveries atau yang juga dikenal sebagai green cabs atau taxi hijau ingin meningkatkan jumlah pengguna untuk jenis taxi hijau. Perusahaan telah melakukan pencatatan untuk semua riwayat perjalanan taxi hijau, dari pencatatan tersebut perusahaan ingin menentukan strategi bisnis yang akan dilakukan dalam upaya peningkatan jumlah pengguna taxi tersebut dilihat dari karakteristik pengguna taxi hijau.

Pernyataan Masalah 
------------
Perusahaan ingin mengetahui **karakteristik pengguna taxi hijau yang sudah melakukan perjalanan**. Informasi tersebut akan membantu perusahaan untuk menentukan strategi bisnis dalam upaya peningkatan jumlah pengguna taxi hijau.

Sebagai seorang *data analyst*, kita akan mencoba menjawab pertanyaan berikut:

**Bagaimana karakteristik pengguna taxi hijau jika dilihat dari lokasi pickup dan dropoff, distribusi perjalanan setiap minggunya, dan jenis pembayaran**

Business Task
------------
Analisis NYC TLC trip record untuk mengidentifikasi karakteristik penumpang/perjalanan taksi yang dapat meningkatkan jumlah pengguna taxi hijau melalui strategi marketing atau rekomendasi lainnya.

Asumsi dan Batasan Project
------------
- Dalam analisis yang akan dilakukan hanya menggunakan dua kota bagian yang memiliki pengguna taxi terbesar di New York City
- Satu trip mewakili satu orang yang berbeda
- Tidak memasukan trip dibawah 0.2mill atau 60seconds (Batas dikenakan tarif per meter)
- Tidak ada batasan umur orang yang menggunakan taksi
- Kenaikan atau penurunan populasi new york city tiap tahun tidak begitu signifikan
- Menggunakan data bulan Januari 2023

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for analysis.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- The document will consist of a detailed analysis and visualization.
    │
    ├── notebooks          <- Jupyter notebooks. A naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    └── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt`

--------