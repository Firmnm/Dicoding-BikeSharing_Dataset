# Analisis Performa Bike Sharing Dataset Pada Tahun 2012

## Performa Peminjaman Sepeda

Performa peminjaman sepeda pada tahun 2012 menunjukkan peningkatan yang cukup baik. Peningkatan signifikan terjadi antara kuartal 1 hingga kuartal 3, diikuti dengan penurunan pada kuartal akhir tahun.

## Situasi dan Kondisi dengan Peminjaman Tertinggi

Beberapa kondisi dengan jumlah peminjam tertinggi adalah sebagai berikut:

- *Musim Gugur* mencatatkan jumlah peminjaman tertinggi dibandingkan musim lainnya.
- *Cuaca cerah dan sedikit berawan* menjadi kondisi cuaca dengan peminjaman sepeda paling tinggi.
- Peminjaman sepeda paling banyak terjadi antara *pukul 5 hingga 6 sore dan pukul 8 pagi*.
- Peminjam sepeda lebih banyak pada hari kerja, *Senin hingga Jumat*, sedangkan pada *akhir pekan (Sabtu dan Minggu)*, peminjaman ramai mulai *pukul 12 siang hingga 3 sore*.
- Jumlah peminjam yang terdaftar lebih banyak dibandingkan peminjam biasa, hal tersebut menunjukkan bahwa bisnis ini perlu memperluas pemasaran untuk menarik lebih banyak peminjam baru, tidak hanya mengandalkan pelanggan yang sudah terdaftar

## Statistik Peminjam Sepeda

- **Registered Customer**: Jumlah peminjam sepeda yang sudah terdaftar jauh lebih banyak dibandingkan peminjam biasa.
- **Casual Customer**: Meski jumlahnya lebih sedikit dibandingkan peminjam terdaftar, ada kebutuhan untuk memperluas pemasaran bisnis untuk menarik perhatian peminjam baru.

## Kesimpulan dan Rekomendasi

Berdasarkan analisis data pada dataset Bike-Sharing atau Bisnis Peminjaman Sepeda, dapat disimpulkan sebagai berikut:

*   Pertanyaan 1: Bagaimana performa peminjaman sepeda pada tahun 2012?

> Performa peminjaman sepeda pada tahun  2012 menunjukkan peningkatan yang cukup signifikan, dengan lonjakan yang lebih jelas terjadi antara kuartal 1 (Januari – Maret) hingga kuartal 3 (Juli – September), serta penurunan pada kuartal 4  (Oktober - Desember). Dengan titik puncak peminjaman sepeda terjadi pada pertengahan tahun (Juni - September),

*   Pertanyaan 2: Situasi dan kondisi seperti apa dengan total peminjaman sepeda tertinggi dalam 1 tahun tersebut?

> Situasi dengan kondisi **musim gugur** dengan total peminjaman 641479 merupakan musim dengan jumlah peminjam sepeda tertinggi. Dan **musim panas** dengan total peminjaman 571273 merupakan musim dengan jumlah peminjam sepeda tertinggi kedua setelah musim gugur.

*   Pertanyaan 3: Berapa banyak peminjam sepeda yang terdaftar sebagai pelanggan dan tidak?

> Peminjam sepeda yang terdaftar jauh lebih banyak dengan total peminjaman 1676811, dengan persentase 81.8%. Sedangkan peminjam casual(tidak terdaftar) dengan total peminjaman 372765. dengan memiliki persentase kurang dari 20% selama 1 tahun tersebut.

---

Berikut adalah saran dan rekomendasi konkret untuk meningkatkan sistem penyewaan sepeda berdasarkan analisis data:

1. Efisiensi Operasional

  * Optimasi Ketersediaan Sepeda

    Berdasarkan data lonjakan penggunaan sepeda di musim panas dan gugur, pastikan jumlah sepeda yang tersedia di stasiun penyewaan mencukupi selama periode puncak (Juni–September). Lakukan analisis lebih lanjut pada lokasi yang sering kehabisan sepeda untuk mendistribusikan sepeda secara lebih merata.

  * Perawatan Proaktif

    Tingkatkan frekuensi inspeksi dan perawatan sepeda sebelum dan selama musim puncak guna meminimalkan kerusakan yang dapat mengurangi tingkat kepuasan pelanggan.


2. Kepuasan Pelanggan

  * Program Loyalitas untuk Peminjam Terdaftar

    Berikan insentif seperti diskon atau bonus perjalanan gratis untuk pelanggan yang sering menggunakan layanan, guna mempertahankan pelanggan setia.

  * Kemudahan Pendaftaran untuk Peminjam Casual

    Melihat dari hasil analsis persentase peminjam casual lebih rendah (hanya sekitar 18%), promosikan proses pendaftaran yang cepat dan sederhana, seperti integrasi dengan akun media sosial atau aplikasi seluler.


3. Peningkatan Potensi Pendapatan

  * Tingkatkan Tarif Dinamis

    Terapkan tarif dinamis selama musim puncak untuk memaksimalkan pendapatan, namun tetap beri pemberitahuan kepada pelanggan sebelumnya untuk menjaga transparansi.

  * Kerja Sama dengan Pariwisata Lokal

    Manfaatkan musim panas dan gugur sebagai peluang untuk bekerja sama dengan penyelenggara tur wisata, hotel, atau tempat wisata lokal untuk menyediakan paket perjalanan bersepeda.

  * Diversifikasi Layanan

    Tambahkan opsi penyewaan untuk jenis sepeda lain, seperti sepeda listrik, untuk menarik pelanggan baru dan memberikan pilihan lebih banyak.


# Dashboard BikeSharing_Dasatet

Untuk menjalankan dashboard ini di _local_ ada beberapa langkah yang perlu dilakukan

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard.py
```
