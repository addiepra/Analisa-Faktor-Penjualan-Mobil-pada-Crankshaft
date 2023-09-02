# Project-Sprint-3-Analisa-Faktor-Penjualan-Mobil-pada-Crankshaft-
## Pendahuluan <a id='intro'></a>
Sebagai seorang analis di Crankshaft List, saya memiliki tanggung jawab untuk menganalisis data yang telah terkumpul dari ratusan iklan kendaraan gratis yang ditayangkan di situs web perusahaan setiap harinya. Dalam upaya untuk lebih memahami faktor-faktor yang memiliki pengaruh terhadap harga kendaraan, saya akan memeriksa data yang telah terakumulasi selama beberapa tahun terakhir. Dengan menganalisis data ini, tujuan utama saya adalah untuk mengidentifikasi dan menggali wawasan mengenai variabel-variabel apa yang memiliki korelasi dengan harga kendaraan. Melalui pendekatan analitis ini, perusahaan kami berharap dapat memberikan informasi yang berharga kepada pengguna situs kami, serta mendukung keputusan pembelian dan penjualan kendaraan yang lebih baik di pasar.
### Tujuan: 
Proyek ini bertujuan untuk menganalisis data iklan kendaraan yang telah terkumpul selama beberapa tahun terakhir di situs web Crankshaft List. Tujuannya adalah untuk mengidentifikasi faktor-faktor yang berpotensi memengaruhi harga kendaraan. Dengan menganalisis hubungan antara variabel-variabel seperti usia kendaraan, jarak tempuh, kondisi, tipe transmisi, warna, dan lainnya dengan harga kendaraan, kami berharap dapat memberikan wawasan yang berharga bagi pengguna situs kami dalam mengambil keputusan pembelian dan penjualan kendaraan yang lebih informasional. Berikut rincian yang akan kita lewati:

- Pelajari parameter berikut: harga, usia kendaraan saat iklan ditayangkan, jarak tempuh, jumlah silinder, dan kondisi. Buatlah histogram untuk setiap parameter tersebut. Pelajari bagaimana outlier memengaruhi bentuk dan keterbacaan histogram yang kamu buat.
- Tentukan batas atas outlier, hapus outlier, dan simpan outlier tersebut ke dalam DataFrame yang terpisah, lalu lanjutkan pekerjaanmu dengan data yang telah difilter.
- Gunakan data yang telah difilter untuk membuat histogram baru. Bandingkan dengan histogram sebelumnya (histogram yang berisi outlier). Tarik kesimpulan untuk setiap histogram.
- Pelajari berapa hari iklan ditayangkan (days_listed). Buatlah sebuah histogram. Hitung rata-rata dan mediannya. Jelaskan berapa lama umumnya sebuah iklan ditayangkan. Tentukan kapan iklan dihapus dengan cepat, dan kapan iklan ditayangkan dalam waktu yang sangat lama.
- Lakukan analisis terhadap jumlah iklan dan harga rata-rata setiap jenis kendaraan. Buat sebuah grafik yang menunjukkan ketergantungan jumlah iklan pada jenis kendaraan. Pilih dua jenis kendaraan dengan jumlah iklan yang paling banyak.
- Faktor apa saja yang paling memengaruhi harga kendaraan? Ambil masing-masing jenis kendaraan populer yang kamu temukan pada tahap sebelumnya dan pelajari apakah harganya bergantung pada usia, jarak tempuh, kondisi, tipe transmisi, dan warnanya. Buat grafik boxplot untuk variabel kategorik (jenis transmisi dan warna), lalu buat scatterplot untuk sisanya. Ketika menganalisis variabel kategorik, ingat bahwa kategori harus memiliki setidaknya 50 iklan. Jika tidak, parameternya tidak akan valid untuk digunakan saat analisis.

### Tahapan yang Dilakukan
Di sini kita akan melakukan analisa dataset pada `/datasets/vehicles_us.csv.csv`.  
Proyek ini terdiri dari 12 tahap: 
 1. Pra-pemrosesan data
 2. Mengatasi Nilai-Nilai yang Hiang (Jika Ada)
 3. Memoerbaiki Tipe Data
 4. Memperbaiki Kualitas Data
 5. Memeriksa Data yang Sudah Bersih
 6. Mempelajari Parameter Inti
 7. Mempelajari dan Menangani Outlier
 8. Mempelajari Parameter Inti Tanpa Outlier
 9. Masa Berlaku Iklan
 10. Harga Rata-Rata Setiap Jenis Kendaraan
 11. Faktor Harga
 12. Kesimpulan Umum
