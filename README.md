# FraudDetection_Credit-Card

Jenis Analisis: Anomaly Detection
Keterangan Dataset : 
Dataset ini berisi transaksi yang dilakukan oleh kartu kredit pada bulan September 2013 oleh pemegang kartu di Eropa. Dataset ini menampilkan transaksi yang terjadi dalam dua hari, di mana ada 492 penipuan dari 284.807 transaksi. Dataset ini sangat tidak seimbang, kelas positif (penipuan) hanya 0,172% dari semua transaksi.
Dataset ini hanya berisi variabel input numerik yang merupakan hasil dari transformasi PCA. Karena masalah kerahasiaan, tidak terdapat fitur asli dan informasi latar belakang lebih lanjut tentang data. Fitur V1, V2, … V28 adalah komponen utama yang diperoleh dengan PCA, fitur yang tidak ditransformasikan dengan PCA hanya ‘Time’ dan ‘Amount’. Fitur ‘Time’ berisi detik yang berlalu antara setiap transaksi dan transaksi pertama dalam dataset. Fitur ‘Amount’ adalah jumlah transaksi, fitur ini dapat digunakan untuk pembelajaran sensitif biaya yang bergantung pada contoh. Fitur ‘Class’ adalah variabel respons dan mengambil nilai 1 dalam kasus penipuan dan 0 sebaliknya.


Link Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
