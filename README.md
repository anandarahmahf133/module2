# Capstone Project Module 2 - Data Analysis Studi Kasus PT Transjakarta

## **Konteks**
Menganalisis data untuk membantu stakeholder dalam pengambilan keputusan yang lebih baik baik dalam hal penjadwalan, alokasi sumber day, maupun perencanaan strategis jangka Panjang. 

## **Pernyataan Masalah**
Meskipun Transjakarta telah beroperasi dengan cukup baik, masih terdapat beberapa tantangan yang perlu diatasi untuk meningkatkan layanan dan efisiensi operasional. Berikut adalah beberapa permasalahan:
1. Menganalisa efisiensi rute dan penggunaan sumber daya
    Rute yang kurang efisien dan penggunaan sumber daya yang tidak optimal dapat meningkatkan biaya operasional dan mengurangi efektivitas layanan.
2. Menganalisa pengelolaan penumpang selama jam sibuk (rush hour)
    Ketidakmampuan untuk mengelola lonjakan penumpang selama jam sibuk dapat menyebabkan kepadatan yang berlebihan dan pengalaman penumpang yang buruk.

**Stakeholder :** Manajemen Transjakarta dan Penumpang Transjakarta

## **Tujuan Analisa**
1. **Optimalisasi Rute dan Penggunaan Sumber Daya**
   
    Menemukan cara untuk mengoptimalkan rute dan penggunaan sumber daya untuk meningkatkan efisiensi operasional
3. **Manajemen Penumpang Selama Jam Sibuk**
   
    Mengembangkan strategi untuk mengelola penumpang selama jam sibuk guna mengurangi kepadatan dan meningkatkan kenyamanan

## **DATA**
Untuk menyelesaikan permasalahan tersebut, terlebih dulu mengenal dataset. Dalam notebook ini menggunakan dataset Transjakarta yang dapat diakses [di sini](https://drive.google.com/file/d/1g7otxUatENCaEpoXqj7WSRQoy4MhFqZF/view?usp=sharing)

**Dataset Detail**

Detail untuk Row Data pada dataset Transjakarta sebagai berikut.

| Nama Kolom            | Deskripsi                                                                 |
|--------------------------|--------------------------------------------------------------------------|
| `transID`               | ID unik transaksi untuk setiap transaksi                                  |
| `payCardID`                   | Identifikasi utama dari penumpang. Kartu yang digunakan penumpang sebagai tiket untuk masuk dan keluar                                                          |
| `payCardBank`            | Nama bank penerbit kartu pembayaran milik penumpang                               |
| `payCardName`               | Nama penumpang yang ada di kartu                                          |
| `payCardSex`        | Jenis Kelamin Penumpang yang ada di kartu                                       |
| `payCardBirthDate`   | Tahun Kelahiran Penumpang                            |
| `corridorID`            | ID Koridor / ID Rute sebagai kunci untuk pengelompokkan rute                                     |
| `corridorName`           | Nama koridor / Nama Rute berisi Mulai dan Selesai untuk setiap Rute                      |
| `direction`         | 0 untuk Pergi, 1 untuk Pulang. Arah Rute                        |
| `tapInStops`        | ID halte tempat penumpang melakukan Tap Masuk        |
| `tapInStopsName` | Nama Halte tempat penumpang melakukan Tap Masuk                  |
| `tapInStopsLat`         | Latitude (Garis Lintang) dari halte tempat penumpang melakukan Tap Masuk       |
| `tapInStopsLon`           | Longitude (Garis Bujur) dari halte tempat penumpang melakukan Tap Masuk                             |
| `stopStartSeq`     | Posisi halte awal dalam rute perjalanan penumpang pada saat melakukan Tap Masuk |
| `tapInTime`            | Waktu penumpang melakukan Tap Masuk yang mencakup tanggal dan jam |
| `tapOutStops`      | ID halte tempat penumpang melakukan Tap Keluar |
| `tapOutStopsName`      | Nama Halte tempat penumpang melakukan Tap Keluar |
| `tapOutStopsLat`      | Latitude (Garis Lintang) dari halte tempat penumpang melakukan Tap Keluar |
| `tapOutStopsLon`      | Longitude (Garis Bujur) dari halte tempat penumpang melakukan Tap Keluar |
| `stopEndSeq`      | Posisi halte akhir dalam rute perjalanan penumpang pada saat melakukan Tap Keluar |
| `tapOutTime`      | Waktu penumpang melakukan Tap Keluar yang mencakup tanggal dan jam |
| `payAmount`      | Jumlah yang dibayarkan penumpang. Beberapa gratis. Beberapa berbayar. |

## **Tahapan Secara Umum**
1. DATA UNDERSTANDING 
2. DATA CLEANING 
3. DATA ANALYSIS

untuk detail tiap tahapan terdapat di dalam file.
