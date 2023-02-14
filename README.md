# Analisis Penjualan di E-Commerce

## Introduction
Belanja secara online semakin diminati oleh masyarakat. Hal ini mendorong pertumbuhan bisnis e-commerce. Berbagai kategori produk tersedia di e-commerce berkat kerja sama dengan mitra merchant (seller). Semakin tinggi volume transaksi penjualan yang dihasilkan oleh mitra merchant, maka akan berkontribusi positif terhadap profitabilitas e-commerce. Oleh karena itu, tim sales e-commerce perlu memantau penjualan yang terjadi untuk menghindari user (customer) pindah ke e-commerce lain.

## Objective
- Tim Sales ingin mengetahui top 10 kategori produk dengan pesanan paling banyak dan paling sedikit
- Tim Sales ingin  mengetahui top 5 penjualan tertinggi berdasarkan negara penjual
- Tim Sales ingin mengamati tren penjualan per bulan 

## Data Overview
Data dalam analisis ini diambil dari database e-commerce “Olist” yang terdiri dari sembilan tabel. Namun, tabel dan variabel yang digunakan untuk melakukan analisis berdasarkan objektif adalah:
- Tabel Olist Order
- Tabel Olist Order Items
- Tabel Olist Product
- Tabel Olist Seller
- Tabel Product Category Name Translation

## Data Preparation & Processing
Data melewati beberapa tahapan pengecekan dari identifikasi tipe data yang sesuai, missing value dan duplikasi, penanganan outlier, dan penyeragaman input data yang inkonsisten agar data siap untuk dianalisis dan hasil analisis dapat mencerminkan fakta yang terjadi. Proses dapat dilihat pada file `project_wrang_sql.ipynb`.

## Data Analysis
### Top 10 kategori produk dengan pesanan paling banyak dan paling sedikit
Berdasarkan analisis data, kategori produk yang paling banyak dipesan diantaranya bed bath table, health beauty, sport leisure, furniture decor, dan computer accessories. Sedangkan kategori produk yang paling sedikit dipesan diantaranya adalah security and services, fashion children clothes, la cuisine, csd dvds musical, art and craftsmanship.
Tim sales dapat menawarkan strategi iklan atau promo produk bagi seller yang menjual kategori produk yang paling sedikit dipesan untuk meningkatkan brand awarenessnya. Sedangkan bagi seller yang menjual produk yang paling banyak dipesan, tim sales dapat menawarkan benefit keanggotaan merchant premium seperti subsidi ongkos kirim agar profit dapat lebih optimal dan seller semakin loyal pada e-commerce.

### Top 5 Penjualan Tertinggi Berdasarkan Negara Penjual
Berdasarkan analisis data, 73,1% penjualan tertinggi dicapai oleh para seller dari negara bagian SP. Dengan demikian, tim sales dapat mendukung strategi penjualan para seller dari negara bagian SP dengan memberikan benefit premium dibandingkan para seller lainnya. Selain itu, e-commerce dapat bekerja sama dengan lembaga pemerintah yang menangani umkm di negara bagian SP melalui pelaksanaan pelatihan kewirausahaan, sehingga diharapkan dapat meningkatkan minat menjadi seller aktif di e-commerce.

### Tren Penjualan per Bulan
Berdasarkan analisis data, penjualan pada tiga tahun terakhir mengalami tren naik pada awal hingga pertengahan tahun dan cenderung turun pada triwulan ketiga terutama bulan September. Tim sales dapat membuat event promo terhadap kategori produk yang paling banyak dipesan pada momen penurunan penjualan untuk memaksimalkan potensi profit. 
