### `Context`

Berdasarkan definisi dari [Cambridge Dictionary](https://dictionary.cambridge.org/dictionary/english/churn-rate), istilah *Churn* adalah persentase dari pelanggan yang berhenti membeli produk atau layanan dari perusahaan tertentu, dihitung untuk periode waktu tertentu.

Dalam konteks bisnis *e-commerce*, istilah "***Churn***" mengacu pada keadaan dimana pelanggan berhenti menjadi pelanggan atau tidak lagi membeli produk pada *e-commerce* tersebut selama periode waktu tertentu. ***Churn Rate*** adalah salah satu metrik penting pada bisnis *e-commerce* karena metrik tersebut dapat menunjukkan banyak hal seperti tingkat kepuasan pelanggan, keterlibatan, dan loyalitas pelanggan terhadap *e-commerce*. Tingkat *churn rate* yang tinggi dapat mengindikasikan bahwa pelanggan tidak puas dengan produk atau layanan yang ditawarkan, atau mereka menemukan alternatif yang lebih baik di tempat lain.

### `Problem Statement`

Terdapat perusahaan *e-commerce* yang memiliki masalah pada bisnis yang dijalankan-nya, pada *e-commerce* tersebut terdapat beberapa pelanggan yang sudah tidak lagi menjadi pelanggan atau tidak lagi berbelanja di *e-commerce* tersebut (***Churn***). *e-commerce* tersebut saat ini memiliki ***churn rate*** yang cukup tinggi, yaitu sebesar **16,33%** dari total pelanggan [(perhitungan *churn rate*)](https://www.paddle.com/resources/calculate-churn-rate), dimana nilai ideal untuk ***churn rate*** saat ini hanya berkisar 5% sampai 7% per tahun [(Monique Danao,2023)](https://www.forbes.com/advisor/business/churn-rate/). Oleh karena itu, hal tersebut akan berdampak pada jumlah pendapatan yang diterima oleh *e-commerce* tersebut, karena *churn rate* yang tinggi akan diikuti dengan penurunan pendapatan perusahaan.

Di sisi lain, ketika perusahaan salah memprediksi pelanggan ***Churn*** atau **tidak *Churn***, hal tersebut akan memberikan masalah kepada perusahaan. Contohnya, jika perusahaan akan melakukan usaha marketing ke semua pelanggan, maka besaran biaya yang dikeluarkan akan menjadi tinggi. Studi menunjukkan bahwa biaya untuk mendapatkan pelanggan baru adalah 5 sampai 25 kali lebih tinggi daripada biaya untuk mempertahankan pelanggan lama ([Amy Gallo, 2014](https://hbr.org/2014/10/the-value-of-keeping-the-right-customers)).Adapun jika perusahaan hanya memberikan usaha marketing ke sebagian pelanggan, maka perusahaan bisa kehilangan pelanggan yang sebenarnya berpotensi menjadi pelanggan yang **tidak *Churn*** (Loyal).

Sehingga pernyataan masalah pada kasus ini adalah bagaimana perusahaan dapat memprediksi pelanggan *churn*  agar promo, diskon, iklan dan usaha marketing lainnya dialokasikan secara lebih efisien sehingga perusahaan tidak perlu mengeluarkan biaya terlalu besar?


### `Project Stakeholders`

Pihak stakeholders yang terlibat dan yang akan menggunakan model dari analisis ini adalah:
* ***Sales & Marketing Team***: Tim ini akan bertanggung jawab dalam mengembangkan dan merencanakan usaha marketing serta mengimplementasikan kepada pelanggan secara tepat dalam upaya memaksimalkan pendapatan perusahaan.
* ***Operations Team***: Tim ini akan bertanggung jawab dalam mengkoordinasikan serta mengurus rincian operasi, mengevaluasi gambaran besar operasi, dan memastikan bahwa area bisnis berjalan semulus dan seefektif mungkin.
* ***Finance Team***: Tim ini akan bertanggung jawab dalam mengatur keuangan perusahaan yang diakibatkan oleh usaha marketing.

Ketiga peran diatas memiliki tujuan yang sama yaitu memaksimalkan pendapatan perusahaan dengan tepat


### `Goals`

*Stakeholders* dapat mengetahui serta memprediksi karakteristik dari jenis pelanggan yang ***Churn*** dan yang **Tidak *Churn***, sehingga mereka dapat menerapkan usaha marketing dengan tepat sasaran. Hal ini dapat menurunkan biaya yang diakibatkan oleh usaha marketing tersebut (*biaya akuisisi pelanggan*) dan diharapkan juga dapat meningkatkan profit dengan mempertahankan pelanggan yang loyal.

### `Analytic Aproach`

Metode dalam melakukan analisis *customer churn* ini menggunakan **analisis prediktif**, kemudian membangun model **klasifikasi** yang akan membantu *stakeholders* untuk dapat memprediksi jenis pelanggan *Churn* (tidak loyal) dan Tidak *Churn* (loyal) berdasarkan data historis.
