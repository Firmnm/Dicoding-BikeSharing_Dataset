# Analisis Performa Bike Sharing Dataset Pada Tahun 2012

## Performa Peminjaman Sepeda

Performa peminjaman sepeda pada tahun 2012 menunjukkan peningkatan yang cukup baik. Peningkatan signifikan terjadi antara kuartal 1 hingga kuartal 3, diikuti dengan penurunan pada kuartal akhir tahun.

## Situasi dan Kondisi dengan Peminjaman Tertinggi

Beberapa kondisi dengan jumlah peminjam tertinggi adalah sebagai berikut:

- *Musim Gugur* mencatatkan jumlah peminjaman tertinggi dibandingkan musim lainnya.
- *Cuaca cerah dan sedikit berawan* menjadi kondisi cuaca dengan peminjaman sepeda paling tinggi.
- Peminjaman sepeda paling banyak terjadi antara *pukul 5 hingga 6 sore dan pukul 8 pagi*.
- Peminjam sepeda lebih banyak pada hari kerja, *Senin hingga Jumat*, sedangkan pada *akhir pekan (Sabtu dan Minggu)*, peminjaman ramai mulai *pukul 12 siang hingga 3 sore*.
Jumlah peminjam yang terdaftar lebih banyak dibandingkan peminjam biasa, hal tersebut menunjukkan bahwa bisnis ini perlu memperluas pemasaran untuk menarik lebih banyak peminjam baru, tidak hanya mengandalkan pelanggan yang sudah terdaftar

## Statistik Peminjam Sepeda

- **Registered Customer**: Jumlah peminjam sepeda yang sudah terdaftar jauh lebih banyak dibandingkan peminjam biasa.
- **Casual Customer**: Meski jumlahnya lebih sedikit dibandingkan peminjam terdaftar, ada kebutuhan untuk memperluas pemasaran bisnis untuk menarik perhatian peminjam baru.

## Kesimpulan dan Rekomendasi

Hasil analisis data peminjaman sepeda tahun 2012 menunjukkan adanya pola tertentu berdasarkan musim dan hari. Untuk meningkatkan jumlah peminjaman sepeda, strategi pemasaran dapat diarahkan pada:

- Menarik pelanggan baru yang belum terdaftar dalam layanan berbagi sepeda.

- Memaksimalkan potensi selama periode waktu dan kondisi cuaca yang menunjukkan tingkat peminjaman yang tinggi.

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
