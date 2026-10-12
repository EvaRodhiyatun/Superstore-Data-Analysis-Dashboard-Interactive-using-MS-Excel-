# Superstore-Data-Analysis-Dashboard-Interactive-using-MS-Excel-
## Project Objective 
Superstore ingin mengetahui kinerja penjualan untuk periode Mei 2016 – Maret 2020, agar manajemen Superstore dapat memahami pelanggan, produk, dan wilayah penjualannya, sehingga dapat meningkatkan penjualan dan margin keuntungan di tahun-tahun berikutnya.
## Questions (KPIs)
- Berapa total penjualan, margin, jumlah pesanan, dan unit yang terjual?
- Bagaimana tren penjualan dan margin dari tahun ke tahun?
- Kategori, produk, dan segmen pelanggan mana yang paling berkontribusi?
- Kota mana yang paling besar penjualannya?
- Bagaimana pola metode pengiriman dan prioritas pesanan?
## Tujuan Project
1. Menyajikan KPI utama dalam satu halaman yang mudah dibaca.
2. Membuat dashboard **interaktif**: KPI dan semua grafik berubah saat slicer dipilih.
3. Menemukan peluang peningkatan penjualan dan margin dari pola data.
4. Melatih pembuatan dashboard Excel dari data mentah hingga siap dipresentasikan.
## Proses Analisis
| Tahap | Aktivitas |
|---|---|
| 1. Persiapan data | Memeriksa sheet *Data* |
| 2. Perhitungan metrik | `Cost Total = Cost Price × Qty`, `Margin Total = Order Total − Cost Total`, `% Margin = Margin Total ÷ Order Total`. |
| 3. Pivot table | Membuat pivot untuk KPI, penjualan dan margin per tahun, kategori × tipe pelanggan, produk teratas, kota, kategori, dan ship mode × prioritas. |
| 4. Visualisasi | Mengubah pivot menjadi 6 grafik (kombinasi kolom dan garis, stacked column, bar, donut, clustered column). |
| 5. Interaktivitas | Menambahkan 4 slicer (Order Year, Product Category, City, Customer Type) dan menghubungkannya ke semua pivot lewat *Report Connections*. |
| 6. KPI dinamis | Kartu KPI mengambil nilai dari pivot dengan `GETPIVOTDATA`, sehingga ikut berubah mengikuti slicer. |
| 7. Validasi | Total pivot dicocokkan dengan data sumber.|

