# online-retail-sales-analysis
# Online Retail Sales & Customer Analysis (Olist E-Commerce)

## 📌 Project Overview
Proyek ini menganalisis lebih dari 100.000 transaksi e-commerce nyata dari platform **Olist (Brasil)** periode 2016–2018 menggunakan **Python (Pandas, Matplotlib, Seaborn)**. Tujuan utama analisis adalah mengevaluasi kinerja pertumbuhan penjualan, mengukur dampak efisiensi pengiriman logistik terhadap kepuasan pelanggan, serta memetakan perilaku retensi pelanggan.

## 🎯 Key Business Insights
1. **Tren Penjualan & Kategori Unggulan:**
   - Penjualan mengalami puncak tertinggi pada **November 2017** yang didorong oleh momentum promosi *Black Friday*.
   - Kategori produk penyumbang pendapatan terbesar didominasi oleh **Health & Beauty**, **Watches & Gifts**, dan **Bed Bath Table**.
2. **Dampak Keterlambatan Pengiriman terhadap Kepuasan Pelanggan:**
   - Pesanan yang tiba **tepat waktu** memperoleh rata-rata rating ulasan tinggi sebesar **4,29 / 5,00** (dengan persentase ulasan bintang 1 hanya ~4%).
   - Pesanan yang **terlambat** mengalami penurunan skor drastis menjadi **2,27 / 5,00**, di mana **lebih dari 50% pelanggan langsung memberikan bintang 1**.
3. **Segmentasi Pelanggan (RFM Analysis):**
   - Sekitar **97% pelanggan** hanya bertransaksi satu kali (*one-time buyers*), sementara hanya **~3%** yang melakukan pembelian berulang (*repeat order*).

## 💡 Strategic Recommendations
- **Optimasi SLA Pengiriman:** Mengevaluasi kinerja penjual (*seller*) dan rute pengiriman antar-negara bagian dengan tingkat keterlambatan tertinggi, serta menyesuaikan perhitungan estimasi waktu tiba agar lebih realistis.
- **Strategi Retensi Pelanggan:** Menyisipkan voucher diskon pembelian berikutnya di dalam paket fisik untuk segmen *Recent Big Spenders*, serta menjalankan kampanye pemasaran ulang (*re-engagement*) pada kategori produk habis pakai (*consumables*).

## 🛠️ Tools & Libraries
- **Language:** Python 3
- **Libraries:** Pandas, Matplotlib, Seaborn, KaggleHub
- **Environment:** Google Colab
