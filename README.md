# Pemenggalan Kata Dasar Bahasa Indonesia
# Tugas Akhir Sistem Temu Kembali Informasi
# 1. Dataset
[db_stemming.csv](https://github.com/ardyanwahyu/TugasAkhirSTKI/files/13989959/db_stemming.csv) <br/>
# Menggunakan Library
1. sastrawi https://github.com/sastrawi/sastrawi  <br/>
# 2. Permasalahan dan Tujuan Eksperimen
Pemenggalan kata dasar atau stemming adalah proses dalam pemrosesan bahasa alami yang bertujuan untuk menghilangkan afiks (imbuhan) dari kata untuk mendapatkan akar kata atau bentuk dasar. Metode stemming digunakan untuk menyederhanakan kata-kata sehingga kata-kata yang memiliki akar kata yang sama dapat diidentifikasi dengan lebih mudah.Metode stemming bisa mengakibatkan kata-kata yang berbeda secara semantik dipenggal menjadi bentuk dasar yang sama. Hal ini dapat menyebabkan kehilangan informasi penting dalam teks.Sebaliknya, metode stemming juga bisa kurang agresif, sehingga kata-kata yang seharusnya dianggap sama tidak dipenggal menjadi bentuk dasar yang identik.Metode stemming mungkin tidak efektif untuk kata-kata slang atau non-standar yang tidak mengikuti aturan morfologi yang umum.Metode stemming mungkin memiliki performa yang berbeda untuk bahasa-bahasa tertentu, tergantung pada kompleksitas morfologi bahasa tersebut. <br/>

Tujuan utama dari aplikasi stemming adalah meningkatkan pemahaman teks dengan menyederhanakan kata-kata sehingga entitas atau konsep yang sama dapat diidentifikasi dengan lebih baik.Dalam sistem pencarian teks, stemming dapat membantu meningkatkan relevansi hasil pencarian dengan memperlakukan variasi kata sebagai bentuk yang sama.Pemenggalan kata dapat membantu mengoptimalkan penyimpanan data dengan mengurangi variasi kata dalam korpus teks.Tujuan lainnya adalah mencapai keseragaman data dengan mengubah variasi kata ke dalam bentuk dasar yang konsisten.<br/>
# 3. Model dan Alur Tahapan Eksperimen <br/>
Pemilihan algoritma stemming Nazief-Adriani sebagai model untuk aplikasi, terutama jika berfokus pada pemrosesan teks dalam bahasa Indonesia.Pengumpulan data teks dalam bahasa Indonesia yang akan diproses.data mencakup variasi kata-kata untuk menguji keefektifan stemming.Kemudian pra-pemrosesan teks, termasuk penghilangan tanda baca, konversi teks ke huruf kecil (lowercasing), dan penghilangan karakter khusus.tokenisasi untuk membagi teks menjadi kata-kata individu. Tokenisasi memungkinkan pemrosesan kata per kata.Menerapkan algoritma Nazief-Adriani pada setiap kata untuk memotong imbuhan dan mendapatkan bentuk dasar dalam bahasa Indonesia.Evaluasi hasil stemming untuk memastikan bahwa pemenggalan kata dasar sesuai dengan harapan. Tinjau beberapa contoh secara manual untuk memastikan bahwa pemenggalan berjalan dengan benar.Integrasikan proses pemenggalan kata dasar ke dalam aplikasi utama.Memastikan bahwa alur ini dapat dijalankan secara efisien dan terintegrasi dengan langkah-langkah pemrosesan teks lainnya dalam aplikasi.<br/>
# 4. Performa Model / Uji Performa Model <br/>
![Screenshot (143)](https://github.com/ardyanwahyu/TugasAkhirSTKI/assets/113100616/361fa125-ee4b-4be6-bfb8-1c5f8f187407)



