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
## Project Insight
- Technology adalah penyumbang penjualan terbesar (~69% dari total, Rp 11.394 juta), disusul Office Supplies (~28%) dan Furniture (~3%).
- Corporate adalah segmen pelanggan terbesar dengan kontribusi ~35% dari total penjualan, disusul Small Business, Home Office, dan Consumer.
- Surabaya adalah kota dengan penjualan tertinggi (~68%), jauh di atas Jakarta (~25%) dan Bandung (~8%).
- Dua produk teratas (Cando PC940 Copier dan HFX LaserJet 3310 Copier) menyumbang ~35% dari total penjualan.
- Penjualan mencapai puncak pada 2018 (~33% dari total), tetapi margin pada tahun itu paling rendah (40,8%) dibanding 46,0% pada 2016.
- Furniture memiliki margin tertinggi (55,3%) meskipun penjualannya paling kecil.
- Regular Air adalah metode pengiriman yang paling banyak dipakai, yaitu pada ~84% dari seluruh pesanan.

## Final Conclusion
Untuk meningkatkan penjualan Superstore, perlu diterapkan strategi yang berfokus pada pelanggan Corporate di Surabaya yang membeli produk Technology. Segmen ini adalah inti bisnis karena menghasilkan sebagian besar pendapatan. Pendekatannya mencakup paket dan promosi untuk produk Technology selain dua copier terlaris agar ketergantungan berkurang, perluasan pemasaran di Jakarta dan Bandung yang penjualannya masih rendah, serta promosi Furniture kepada pelanggan Corporate karena marginnya tinggi. Diskon juga perlu dipantau agar margin tetap sehat saat penjualan meningkat.
