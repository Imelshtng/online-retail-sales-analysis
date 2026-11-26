# online-retail-sales-analysis
# Online Retail II: Sales, Customer Retention & RFM Analysis

## 📌 Project Overview
Proyek ini menganalisis lebih dari 1 juta transaksi ritel online (*non-store retail*) berbasis di Inggris periode **2009–2011** dari **UCI Machine Learning Repository (Online Retail II)** menggunakan **Python (Pandas, Matplotlib, Seaborn)**. Fokus utama analisis adalah mengevaluasi kinerja penjualan, memahami distribusi geografis pelanggan, melakukan pembersihan anomali transaksi (retur/pembatalan), serta mengelompokkan pelanggan menggunakan **RFM Analysis**.

## 🎯 Key Analytical Steps & Business Insights
1. **Data Cleaning & Anomaly Handling:**
   - Menghapus transaksi tanpa `Customer ID` untuk keperluan pelacakan perilaku pelanggan.
   - Memisahkan transaksi pembatalan/retur (nomor faktur berawalan huruf `'C'`) serta nilai kuantitas/harga negatif agar perhitungan pendapatan bersih (*net revenue*) akurat.
2. **Tren Penjualan & Musiman (*Seasonality*):**
   - Penjualan menunjukkan lonjakan tajam setiap kuartal keempat (**September–November**), yang didorong oleh permintaan grosir menjelang musim liburan akhir tahun (*Christmas & year-end shopping*).
   - **United Kingdom** mendominasi porsi transaksi dan pendapatan dibandingkan pasar internasional lainnya (seperti EIRE, Netherlands, Germany, dan France).
3. **Segmentasi Pelanggan (RFM Analysis):**
   - Mengelompokkan pelanggan berdasarkan **Recency** (kebaruan transaksi), **Frequency** (frekuensi belanja), dan **Monetary** (total nilai belanja) untuk mengidentifikasi segmen *Champions / Loyal Customers* (pelanggan grosir B2B bernilai tinggi) serta segmen *At Risk / Hibernating* yang membutuhkan kampanye retensi.

## 💡 Strategic Recommendations
- **Program Loyalitas B2B:** Memberikan insentif volume atau prioritas stok kepada segmen *Champions / Top Spenders* menjelang periode puncak kuartal keempat (Q4).
- **Kampanye Re-engagement:** Mengirimkan penawaran khusus berbasis katalog produk terlaris kepada segmen pelanggan yang belum bertransaksi kembali dalam >90 hari.
- **Ekspansi Pasar Eropa:** Memfokuskan promosi pengiriman internasional pada negara dengan nilai rata-rata transaksi (*Average Order Value*) tinggi seperti Belanda dan Irlandia.

## 📂 Repository Structure
- `notebooks/` — Jupyter/Colab notebook berisi alur lengkap pembersihan data, EDA, visualisasi, dan RFM Analysis.
- `images/` — Visualisasi grafik utama hasil analisis.
- `data/` — Informasi sumber dan tautan unduhan dataset.

## 🛠️ Tools & Libraries
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab
