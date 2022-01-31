# Disclaimer

MD5 adalah hash bukanlah enkripsi, algoritmanya hanya satu arah. Tidak ada cara pasti untuk membalikkan / mendekripsi MD5Hash

Yang ada hanyalah beberapa metode membandingkan, bukan membalikkan algoritma. Termasuk juga dengan metode bruteforce ini.

Pada dasarnya metode brute-force hanya melakukan pembandingan set karakter ( lihat $charset di source code brute-force.php ) dengan hash yang diberikan. Hal ini dilakukan secara rekursif ( berulang )

Aplikasi ini efektif untuk membalikkan hash dengan kombinasi sederhana dan pendek. Semakin panjang dan komplek kombinasi karakter dalam hash, maka akan semakin lama proses membalikkannya. Juga mungkin bisa membuat proses di CPU tinggi.

## Sedikit Kisah
Aplikasi ini hanya untuk keperluan testing saja. Kode aslinya saya buat pada tahun 2014 sebagai tugas salah satu matakuliah ketika saya masih mengikuti kuliah kelas sore di UMJ :).

Saya Publish di Github, karena ternyata di th 2021 masih banyak request untuk file ini di blog lama saya dan link-nya sudah tidak aktif lagi.

Semoga bermanfaat.