# 📊 Analisis Jam Sibuk dan Pola Perjalanan Penumpang Transjakarta Koridor 13

Notebook ini berisi analisis statistik terhadap data transaksi penumpang Transjakarta Koridor 13 (Ciledug - Tendean). Tujuan dari analisis ini adalah untuk mengidentifikasi **jam sibuk**, membandingkan **pola perjalanan antara hari kerja dan akhir pekan**, serta memberikan **rekomendasi strategis berbasis data** untuk mendukung efisiensi operasional.

## 🔍 Tujuan Analisis

1. **Identifikasi Jam Sibuk**  
   Menentukan waktu-waktu dengan volume penumpang tertinggi dalam satu hari.

2. **Perbandingan Hari Kerja vs Akhir Pekan**  
   Menganalisis perbedaan jumlah dan distribusi penumpang antara weekdays dan weekends.

3. **Rekomendasi Operasional**  
   Memberikan saran berbasis temuan statistik untuk peningkatan layanan Transjakarta Koridor 13.

## 🛠️ Tools dan Library

Notebook ini menggunakan beberapa library utama Python untuk analisis data:

- `pandas` - manipulasi data
- `numpy` - komputasi numerik
- `matplotlib`, `seaborn` - visualisasi
- `scipy.stats` - uji statistik (misalnya uji t dan uji ANOVA)

## 📁 Struktur Notebook

- **Import dan Persiapan Data**
- **Eksplorasi Awal Data**
- **Visualisasi Pola Perjalanan**
- **Uji Statistik:**
  - Uji t dua sampel independen
  - Uji ANOVA satu arah
- **Kesimpulan dan Rekomendasi**

## 📈 Contoh Visualisasi

- Grafik distribusi penumpang per jam
- Perbandingan volume hari kerja vs akhir pekan
- Boxplot untuk melihat sebaran penumpang

## 🧪 Hasil Pengujian

- Jam sibuk ditemukan pada pukul **06:00 - 08:00** dan **16:00 - 18:00**.
- Terdapat perbedaan signifikan antara hari kerja dan akhir pekan berdasarkan hasil uji statistik.
- Rekomendasi mencakup penyesuaian jadwal bus dan peningkatan armada pada jam sibuk.

## 📌 Catatan

- Data transaksi telah dibersihkan dan difokuskan hanya pada Koridor 13.
- Analisis ini dapat diperluas ke koridor lain atau digunakan untuk perencanaan operasional jangka panjang.

## 🧾 Lisensi

Proyek ini berada di bawah lisensi [MIT License](https://opensource.org/licenses/MIT).
