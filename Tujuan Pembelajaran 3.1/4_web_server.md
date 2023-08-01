# Web Server / Server Web

Istilah server web dapat merujuk pada perangkat keras atau perangkat lunak, atau keduanya bekerja bersama.

1. Di sisi perangkat keras, server web adalah komputer yang menyimpan perangkat lunak server web dan file komponen situs web (misalnya, dokumen HTML, gambar, lembar gaya CSS, dan file JavaScript). Server web terhubung ke Internet dan mendukung pertukaran data fisik dengan perangkat lain yang terhubung ke web.
2. Di sisi perangkat lunak, server web menyertakan beberapa bagian yang mengontrol cara pengguna web mengakses file yang dihosting. Minimal, ini adalah server HTTP . Server HTTP adalah perangkat lunak yang memahami URL (alamat web) dan HTTP (protokol yang digunakan browser Anda untuk melihat halaman web). Server HTTP dapat diakses melalui nama domain dari situs web yang disimpannya, dan mengirimkan konten dari situs web yang dihosting ini ke perangkat pengguna akhir.

Pada tingkat paling dasar, setiap kali browser membutuhkan file yang dihosting di server web, browser meminta file tersebut melalui HTTP. Ketika permintaan mencapai server web (perangkat keras) yang benar, server HTTP (perangkat lunak) menerima permintaan, menemukan dokumen yang diminta, dan mengirimkannya kembali ke browser, juga melalui HTTP. (Jika server tidak menemukan dokumen yang diminta, server akan mengembalikan respons 404. )

![webserver&browser](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server/web-server.svg)

Representasi dasar dari koneksi klien/server melalui HTTP
Untuk menerbitkan situs web, Anda memerlukan server web statis atau dinamis.

**Server web statis** , atau tumpukan, terdiri dari komputer (perangkat keras) dengan server HTTP (perangkat lunak). Kami menyebutnya "statis" karena server mengirimkan file yang dihosting apa adanya ke browser Anda.

**Server web dinamis** terdiri dari server web statis ditambah perangkat lunak tambahan, paling sering adalah server aplikasi dan database . Kami menyebutnya "dinamis" karena server aplikasi memperbarui file yang dihosting sebelum mengirim konten ke browser Anda melalui server HTTP.

Misalnya, untuk menghasilkan halaman web akhir yang Anda lihat di browser, server aplikasi mungkin mengisi template HTML dengan konten dari database. Situs seperti MDN atau Wikipedia memiliki ribuan halaman web. Biasanya, situs semacam ini hanya terdiri dari beberapa template HTML dan database raksasa, bukan ribuan dokumen HTML statis. Penyiapan ini mempermudah pemeliharaan dan pengiriman konten.

## File hosting
Pertama, server web harus menyimpan file situs web, yaitu semua dokumen HTML dan aset terkaitnya, termasuk gambar, lembar gaya CSS, file JavaScript, font, dan video.

Secara teknis, Anda dapat menghosting semua file tersebut di komputer Anda sendiri, tetapi jauh lebih nyaman untuk menyimpan semua file di server web khusus karena:

Server web khusus biasanya lebih tersedia (aktif dan berjalan).
Tidak termasuk waktu henti dan masalah sistem, server web khusus selalu terhubung ke Internet.
Server web khusus dapat memiliki alamat IP yang sama sepanjang waktu. Ini dikenal sebagai alamat IP khusus . (Tidak semua ISP menyediakan alamat IP tetap untuk saluran rumah.)
Server web khusus biasanya dikelola oleh pihak ketiga.
Untuk semua alasan ini, menemukan penyedia hosting yang baik adalah bagian penting dalam membangun situs web Anda. Periksa berbagai layanan yang ditawarkan perusahaan. Pilih salah satu yang sesuai dengan kebutuhan dan anggaran Anda. (Layanan berkisar dari gratis hingga ribuan dolar per bulan.) 

Setelah Anda memiliki layanan hosting web, Anda harus mengunggah file Anda ke server web Anda.

## Berkomunikasi melalui HTTP
Kedua, server web menyediakan dukungan untuk HTTP ( Hyper text Transfer Protocol) . Seperti namanya, HTTP menentukan cara mentransfer hypertext (dokumen web yang ditautkan) antara dua komputer.

Protokol adalah seperangkat aturan untuk komunikasi antara dua komputer . HTTP adalah tekstual, protokol stateless.

Tekstual
Semua perintah adalah teks biasa dan dapat dibaca manusia.

Tanpa kewarganegaraan
Baik server maupun klien tidak mengingat komunikasi sebelumnya. Misalnya, dengan mengandalkan HTTP saja, server tidak dapat mengingat kata sandi yang Anda ketikkan atau mengingat kemajuan Anda dalam transaksi yang belum selesai. Anda memerlukan server aplikasi untuk tugas-tugas seperti itu. (Kami akan membahas teknologi semacam itu di artikel lain.)

HTTP memberikan aturan yang jelas tentang bagaimana klien dan server berkomunikasi. Kami akan membahas HTTP itu sendiri dalam artikel teknis nanti. Untuk saat ini, perhatikan saja hal-hal ini:

Biasanya hanya klien yang membuat permintaan HTTP, dan hanya ke server . Server menanggapi permintaan HTTP klien . Server juga dapat mengisi data ke dalam cache klien, sebelum diminta, melalui mekanisme yang disebut server push .
Saat meminta file melalui HTTP, klien harus memberikan URL file .
Server web harus menjawab setiap permintaan HTTP, setidaknya dengan pesan kesalahan. Pada web server, HTTP server bertugas memproses dan menjawab permintaan yang masuk.

Setelah menerima permintaan, server HTTP memeriksa apakah URL yang diminta cocok dengan file yang ada. Jika demikian, server web mengirimkan konten file kembali ke browser. Jika tidak, server akan memeriksa apakah harus membuat file secara dinamis untuk permintaan tersebut.

Jika tidak satu pun dari opsi ini memungkinkan, server web mengembalikan pesan kesalahan ke browser, paling sering 404 Not Found. Kesalahan 404 sangat umum sehingga beberapa desainer web mencurahkan banyak waktu dan tenaga untuk mendesain halaman kesalahan 404.

![not found 404](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server/mdn-404.jpg)

## Konten statis vs. dinamis
Secara kasar, server dapat menyajikan konten statis atau dinamis. Ingatlah bahwa istilah statis berarti "disajikan apa adanya". Situs web statis adalah yang paling mudah disiapkan, jadi sebaiknya buat situs pertama Anda menjadi situs statis.

Istilah dinamis berarti server memproses konten atau bahkan membuatnya dengan cepat dari database. Pendekatan ini memberikan lebih banyak fleksibilitas, tetapi kumpulan teknisnya lebih rumit, membuatnya jauh lebih menantang untuk membangun situs web.

Tidak mungkin untuk menyarankan satu server aplikasi siap pakai yang akan menjadi solusi yang tepat untuk setiap kemungkinan kasus penggunaan. Beberapa server aplikasi dirancang untuk menghosting dan mengelola blog, wiki, atau solusi e-niaga, sementara yang lain lebih umum. Jika Anda membuat situs web yang dinamis, luangkan waktu untuk meneliti kebutuhan Anda dan temukan teknologi yang paling sesuai dengan kebutuhan Anda.

Sebagian besar pengembang situs web tidak perlu membuat server aplikasi dari awal, karena ada begitu banyak solusi siap pakai, banyak di antaranya sangat dapat dikonfigurasi. Namun jika Anda memang perlu membuat server sendiri, Anda mungkin ingin menggunakan kerangka kerja server, memanfaatkan kode dan pustaka yang ada, dan memperluas hanya bagian yang Anda perlukan untuk memenuhi kasus penggunaan Anda. Hanya sejumlah kecil pengembang yang perlu mengembangkan server sepenuhnya dari awal: misalnya, untuk memenuhi batasan sumber daya yang ketat pada sistem yang disematkan.

*Source* : [mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server)

*Thanks To* : [roadmap.sh](https://roadmap.sh/)

[Home](README.md) | [Back](3_website_dan_halaman_web.md) | [Next](5_web_browser.md)
