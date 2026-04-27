LAPORAN PRAKTIKUM VISUALISASI DAN ANALISIS DATA : 

1. Business Question
   
Produk apa saja yang termasuk underperformer (harga tinggi namun penjualan rendah)?
Produk mana yang memiliki performa terbaik berdasarkan analisis RFM?
Kategori produk mana yang paling efisien dalam menghasilkan profit?

2. Data Wrangling
   
Dataset berisi 3500 data transaksi tanpa missing value.
Dilakukan pengecekan tipe data menggunakan df.info() dan tidak ditemukan nilai kosong.
Nama kolom disederhanakan agar mudah digunakan dalam analisis.
Kolom order_date diubah ke format datetime untuk mempermudah analisis waktu.
Dibuat kolom baru price_per_unit untuk menghitung harga per produk.

3. Insights
- Underperformer Product

Berdasarkan analisis, ditemukan beberapa produk dengan harga per unit tinggi namun memiliki jumlah penjualan rendah. Hal ini menunjukkan bahwa harga yang terlalu tinggi dapat menjadi faktor penghambat dalam meningkatkan volume penjualan.

- Visualisasi Scatter Plot

Scatter plot menunjukkan bahwa produk dengan harga tinggi cenderung memiliki jumlah penjualan yang lebih rendah, yang mengindikasikan adanya hubungan negatif antara harga dan jumlah pembelian.

- RFM Analysis (Adaptasi)

Produk dengan nilai Recency rendah (baru dibeli), Frequency tinggi, dan Monetary tinggi merupakan produk dengan performa terbaik dan layak diprioritaskan dalam strategi pemasaran.

- Efisiensi Kategori

Kategori dengan rasio profit terhadap sales yang rendah menunjukkan efisiensi yang kurang baik, sehingga perlu dilakukan evaluasi strategi harga atau biaya.

- Keterbatasan Data

Dataset tidak menyediakan data pelanggan dan anggaran iklan, sehingga beberapa analisis seperti RFM berbasis pelanggan dan uji pengaruh iklan tidak dapat dilakukan secara optimal.

4. Recommendation :
   
Evaluasi harga pada produk yang memiliki harga tinggi namun penjualan rendah.
Fokus pada produk dengan performa tinggi untuk meningkatkan profit.
Optimalkan kategori dengan efisiensi rendah melalui strategi pemasaran atau pengurangan biaya.
Tambahkan data seperti pelanggan dan anggaran iklan untuk analisis yang lebih mendalam di masa depan.

5. Catatan : 

Analisis regresi linear tidak dapat dilakukan karena tidak tersedia variabel Biaya Iklan (Ad_Budget) dalam dataset, sehingga model hanya dijelaskan secara teoritis.
