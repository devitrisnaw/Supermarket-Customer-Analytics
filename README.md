# ANALISIS PELANGGAN SUPERMARKET

### LATAR BELAKANG
Perkembangan bisnis ritel saat ini menuntut perusahaan untuk mampu memahami perilaku pelanggan secara mendalam. 
Data transaksi yang dikumpulkan oleh supermarket mencerminkan aktivitas belanja pelanggan yang dapat diolah untuk menggali informasi penting, seperti preferensi produk, waktu pembelian favorit, dan efektivitas cabang. 
Dengan menganalisis data pelanggan secara sistematis, supermarket dapat menyusun strategi pemasaran yang lebih tepat sasaran, meningkatkan pengalaman pelanggan, serta memaksimalkan keuntungan. 
Oleh karena itu, diperlukan analisis data pelanggan secara menyeluruh sebagai dasar pengambilan keputusan bisnis berbasis data.

### Pernyataan Masalah
Meskipun supermarket telah mengumpulkan berbagai data pelanggan, namun belum diketahui secara jelas:
1. Siapa segmen pelanggan utama berdasarkan demografi seperti usia, pendidikan, dan status pernikahan?
2. Produk atau kategori mana yang paling banyak dibeli dan memberikan kontribusi terbesar terhadap total belanja?
3. Bagaimana pengaruh karakteristik pelanggan (seperti pendapatan dan jumlah anak) terhadap pengeluaran mereka?
4. Seberapa efektif kampanye pemasaran yang telah dijalankan selama ini?
5. Faktor apa saja yang memengaruhi pelanggan dalam memberikan respons terhadap promosi?

### Struktur Kolom

1. Struktur Kolom

`ID` (Integer) = ID unik pelanggan

`Year_Birth` (Integer) = Tahun kelahiran pelanggan (bisa dihitung umur)

`Education` (Kategori) = Tingkat pendidikan (Basic, Graduation, Master, PhD, dsb.)

`Marital_Status` (Kategori) = Status pernikahan (Single, Married, Together, dsb.)

`Income` (Numerik) = Pendapatan tahunan pelanggan (dalam angka)

`Kidhome` (Integer) = Jumlah anak di rumah (yang berusia anak kecil)

`Teenhome` (Integer) = Jumlah anak remaja di rumah (yang berusia remaja)

`Dt_Customer` (Tanggal) = Tanggal pertama kali menjadi pelanggan

`Recency` (Integer) = Hari sejak pembelian terakhir

`MntWines`, `MntFruits`, ..., `MntGoldProds` (Integer) = Pengeluaran (dalam satuan mata uang) per kategori produk

`NumDealsPurchases` (Integer) = Jumlah pembelian dengan diskon

`NumWebPurchases` (Integer) = Jumlah pembelian via website

`NumCatalogPurchases`(Integer) = Jumlah pembelian via katalog

`NumStorePurchases` (Integer) = Jumlah pembelian langsung di toko

`NumWebVisitsMonth` (Integer) = Jumlah kunjungan ke website per bulan

`AcceptedCmp1–5` (Biner (0/1)) = Apakah pelanggan merespon kampanye marketing tertentu

`Complain`(Biner (0/1)) = Apakah pelanggan pernah mengeluh

`Z_CostContact` (Konstanta) = tidak terkait dengan kolom lainnya, sehingga dapat dihapus (semua bernilai sama)

`Z_Revenue` (Konstanta) = tidak terkait dengan kolom lainnya, sehingga dapat dihapus (semua bernilai sama)

`Response` (Biner (0/1)) = Apakah pelanggan merespons kampanye terakhir

### Link Tableau
https://public.tableau.com/app/profile/devi.trisnawati/viz/DashboardSuperNew/DashboardSupermarketCust?publish=yes

### Link PPT
https://drive.google.com/file/d/1XUDaFsg9xh5bEDFuQfCf2Dr-Tna5iIeS/view?usp=sharing
