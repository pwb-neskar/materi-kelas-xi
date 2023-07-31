# Bagaimana Internet Bekerja
Sebagai pengembang, penting untuk memiliki pemahaman yang kuat tentang apa itu internet dan cara kerjanya. Ini adalah fondasi di mana sebagian besar aplikasi perangkat lunak modern dibangun. Untuk membangun aplikasi dan layanan yang efektif, aman, dan dapat diskalakan, Anda harus memiliki pemahaman yang kuat tentang cara kerja internet dan cara memanfaatkan kekuatan dan konektivitasnya.

Pada artikel ini kita akan membahas dasar-dasar internet termasuk apa itu cara kerjanya, beberapa konsep dasar, terminologi dan beberapa protokol umum yang digunakan untuk membangun aplikasi dan layanan di internet.
<details>
<summary>Pengantar Internet</summary>
Sebelum kita mempelajari apa itu Internet, kita perlu memahami apa itu Jaringan . Jaringan adalah sekelompok komputer atau perangkat lain yang terhubung satu sama lain. Misalnya, Anda di rumah mungkin memiliki jaringan komputer dan perangkat. Teman Anda yang tinggal di sebelah mungkin memiliki jaringan perangkat yang serupa. Tetangga mereka mungkin memiliki jaringan perangkat yang serupa. Semua jaringan ini ketika terhubung bersama membentuk internet.

> Internet adalah jaringan dari jaringan.

Internet dikembangkan pada akhir 1960-an oleh Departemen Pertahanan Amerika Serikat sebagai sarana untuk menciptakan jaringan komunikasi terdesentralisasi yang dapat menahan serangan nuklir. Selama bertahun-tahun, itu telah berkembang menjadi jaringan yang kompleks dan canggih yang menjangkau seluruh dunia.

Saat ini, internet adalah bagian penting dari kehidupan modern, digunakan oleh miliaran orang di seluruh dunia untuk mengakses informasi, berkomunikasi dengan teman dan keluarga, menjalankan bisnis, dan banyak lagi. Sebagai pengembang, penting untuk memiliki pemahaman yang kuat tentang cara kerja internet dan berbagai teknologi serta protokol yang mendukungnya.
</details>

<details>
<summary>Cara Kerja Internet: Gambaran Umum</summary>
Pada tingkat tinggi, internet bekerja dengan menghubungkan perangkat dan sistem komputer secara bersamaan menggunakan seperangkat protokol standar. Protokol ini menentukan bagaimana informasi dipertukarkan antar perangkat dan memastikan bahwa data ditransmisikan dengan andal dan aman.

Inti dari internet adalah jaringan global router yang saling terhubung, yang bertanggung jawab untuk mengarahkan lalu lintas antara perangkat dan sistem yang berbeda. Saat Anda mengirim data melalui internet, data dipecah menjadi paket-paket kecil yang dikirim dari perangkat Anda ke router. Router memeriksa paket dan meneruskannya ke router berikutnya di jalur menuju tujuannya. Proses ini berlanjut hingga paket mencapai tujuan akhirnya.

Untuk memastikan bahwa paket dikirim dan diterima dengan benar, internet menggunakan berbagai macam protokol, termasuk Internet Protocol (IP) dan Transmission Control Protocol (TCP). IP bertanggung jawab untuk merutekan paket ke tujuan yang benar, sementara TCP memastikan bahwa paket ditransmisikan dengan andal dan dalam urutan yang benar.

Selain protokol inti ini, ada berbagai macam teknologi dan protokol lain yang digunakan untuk memungkinkan komunikasi dan pertukaran data melalui internet, termasuk Domain Name System (DNS), Hypertext Transfer Protocol (HTTP), dan Secure Protokol Sockets Layer/Transport Layer Security (SSL/TLS). Sebagai pengembang, penting untuk memiliki pemahaman yang kuat tentang bagaimana teknologi dan protokol yang berbeda ini bekerja sama untuk memungkinkan komunikasi dan pertukaran data melalui internet.
</details>

<details>
<summary>Konsep Dasar dan Terminologi</summary>
Untuk memahami internet, penting untuk memahami beberapa konsep dasar dan terminologi. Berikut adalah beberapa istilah dan konsep utama yang harus diperhatikan:
<ul><li>Paket: Sebuah unit kecil data yang dikirimkan melalui internet.</li><li>Router: Perangkat yang mengarahkan paket data antara jaringan yang berbeda.</li><li>IP Address: Pengidentifikasi unik yang ditetapkan untuk setiap perangkat di jaringan, digunakan untuk merutekan data ke tujuan yang benar.</li><li>Nama Domain: Nama yang dapat dibaca manusia yang digunakan untuk mengidentifikasi situs web, seperti google.com.</li><li>DNS: Domain Name System bertanggung jawab untuk menerjemahkan nama domain menjadi alamat IP.</li><li>HTTP: Hypertext Transfer Protocol digunakan untuk mentransfer data antara klien (seperti browser web) dan server (seperti situs web).</li><li>HTTPS: Versi HTTP terenkripsi yang digunakan untuk menyediakan komunikasi yang aman antara klien dan server.</li><li>SSL/TLS: Protokol Secure Sockets Layer dan Transport Layer Security digunakan untuk menyediakan komunikasi yang aman melalui internet.</li></ul>

Memahami konsep dan istilah dasar ini sangat penting untuk bekerja dengan internet dan mengembangkan aplikasi dan layanan berbasis internet.
</details>

<details>
<summary>Peran Protokol di Internet</summary>
Protokol memainkan peran penting dalam memungkinkan komunikasi dan pertukaran data melalui internet. Protokol adalah seperangkat aturan dan standar yang menentukan bagaimana informasi dipertukarkan antara perangkat dan sistem.

Ada banyak protokol berbeda yang digunakan dalam komunikasi internet, termasuk Internet Protocol (IP), Transmission Control Protocol (TCP), User Datagram Protocol (UDP), Domain Name System (DNS), dan masih banyak lagi.

IP bertanggung jawab untuk merutekan paket data ke tujuan yang benar, sementara TCP dan UDP memastikan bahwa paket ditransmisikan dengan andal dan efisien. DNS digunakan untuk menerjemahkan nama domain menjadi alamat IP, dan HTTP digunakan untuk mentransfer data antara klien dan server.

Salah satu manfaat utama menggunakan protokol standar adalah memungkinkan perangkat dan sistem dari pabrikan dan vendor yang berbeda untuk berkomunikasi satu sama lain dengan mulus. Misalnya, browser web yang dikembangkan oleh satu perusahaan dapat berkomunikasi dengan server web yang dikembangkan oleh perusahaan lain, selama keduanya mematuhi protokol HTTP.

Sebagai pengembang, penting untuk memahami berbagai protokol yang digunakan dalam komunikasi internet dan bagaimana protokol tersebut bekerja sama untuk memungkinkan transfer data dan informasi melalui internet.
</details>

<details>
<summary>
Memahami Alamat IP dan Nama Domain</summary>
Alamat IP dan nama domain keduanya merupakan konsep penting untuk dipahami saat bekerja dengan internet.

Alamat IP adalah pengidentifikasi unik yang ditetapkan untuk setiap perangkat di jaringan. Ini digunakan untuk merutekan data ke tujuan yang benar, memastikan bahwa informasi dikirim ke penerima yang dituju. Alamat IP biasanya direpresentasikan sebagai rangkaian empat angka yang dipisahkan oleh titik, seperti "192.168.1.1".

Nama domain, di sisi lain, adalah nama yang dapat dibaca manusia yang digunakan untuk mengidentifikasi situs web dan sumber daya internet lainnya. Mereka biasanya terdiri dari dua bagian atau lebih, dipisahkan oleh periode. Misalnya, "google.com" adalah nama domain. Nama domain diterjemahkan menjadi alamat IP menggunakan Domain Name System (DNS).

DNS adalah bagian penting dari infrastruktur internet, bertanggung jawab untuk menerjemahkan nama domain menjadi alamat IP. Saat Anda memasukkan nama domain ke browser web, komputer Anda mengirimkan kueri DNS ke server DNS, yang mengembalikan alamat IP yang sesuai. Komputer Anda kemudian menggunakan alamat IP tersebut untuk terhubung ke situs web atau sumber daya lain yang Anda minta.
</details>

<details>
<summary>Pengantar HTTP dan HTTPS</summary>
HTTP (Hypertext Transfer Protocol) dan HTTPS (HTTP Secure) adalah dua protokol yang paling umum digunakan dalam aplikasi dan layanan berbasis internet.

HTTP adalah protokol yang digunakan untuk mentransfer data antara klien (seperti browser web) dan server (seperti situs web). Saat Anda mengunjungi situs web, browser web Anda mengirimkan permintaan HTTP ke server, menanyakan halaman web atau sumber daya lain yang Anda minta. Server kemudian mengirimkan respons HTTP kembali ke klien, berisi data yang diminta.

HTTPS adalah versi HTTP yang lebih aman, yang mengenkripsi data yang dikirimkan antara klien dan server menggunakan enkripsi SSL/TLS (Secure Sockets Layer/Transport Layer Security). Ini memberikan lapisan keamanan tambahan, membantu melindungi informasi sensitif seperti kredensial masuk, informasi pembayaran, dan data pribadi lainnya.

Saat Anda mengunjungi situs web yang menggunakan HTTPS, browser web Anda akan menampilkan ikon gembok di bilah alamat, yang menunjukkan bahwa koneksi aman. Anda mungkin juga melihat huruf "https" di awal alamat situs web, bukan "http".
</details>

<details>
<summary>Membangun Aplikasi dengan TCP/IP</summary>
TCP/IP (Transmission Control Protocol/Internet Protocol) adalah protokol komunikasi dasar yang digunakan oleh sebagian besar aplikasi dan layanan berbasis internet. Ini memberikan pengiriman data yang andal, teratur, dan diperiksa kesalahan antara aplikasi yang berjalan pada perangkat yang berbeda.

Saat membangun aplikasi dengan TCP/IP, ada beberapa konsep kunci yang perlu dipahami:
<ul><li>Port: Port digunakan untuk mengidentifikasi aplikasi atau layanan yang berjalan di perangkat. Setiap aplikasi atau layanan diberi nomor port unik, memungkinkan data dikirim ke tujuan yang benar.</li><li>Soket: Soket adalah kombinasi dari alamat IP dan nomor port, yang mewakili titik akhir tertentu untuk komunikasi. Soket digunakan untuk membuat koneksi antar perangkat dan mentransfer data antar aplikasi.</li><li>Koneksi: Koneksi dibuat antara dua soket ketika dua perangkat ingin berkomunikasi satu sama lain. Selama proses pembuatan koneksi, perangkat menegosiasikan berbagai parameter seperti ukuran segmen maksimum dan ukuran jendela, yang menentukan bagaimana data akan dikirim melalui koneksi.</li><li>Transfer data: Setelah koneksi dibuat, data dapat ditransfer antara aplikasi yang berjalan di setiap perangkat. Data biasanya ditransmisikan dalam segmen, dengan setiap segmen berisi nomor urut dan metadata lainnya untuk memastikan pengiriman yang andal.</li></ul>

Saat membangun aplikasi dengan TCP/IP, Anda harus memastikan bahwa aplikasi Anda dirancang untuk bekerja dengan port, soket, dan koneksi yang sesuai. Anda juga harus terbiasa dengan berbagai protokol dan standar yang biasa digunakan dengan TCP/IP, seperti HTTP, FTP (File Transfer Protocol), dan SMTP (Simple Mail Transfer Protocol). Memahami konsep dan protokol ini sangat penting untuk membangun aplikasi dan layanan berbasis internet yang efektif, dapat diskalakan, dan aman.
</details>

<details>
<summary>Mengamankan Komunikasi Internet dengan SSL/TLS</summary>
Seperti yang telah kita bahas sebelumnya, SSL/TLS adalah protokol yang digunakan untuk mengenkripsi data yang dikirimkan melalui internet. Biasanya digunakan untuk menyediakan koneksi aman untuk aplikasi seperti browser web, klien email, dan program transfer file.

Saat menggunakan SSL/TLS untuk mengamankan komunikasi internet, ada beberapa konsep utama yang perlu dipahami:
<ul><li>Certificate(Sertifikat): Sertifikat SSL/TLS digunakan untuk membangun kepercayaan antara klien dan server. Mereka berisi informasi tentang identitas server dan ditandatangani oleh pihak ketiga tepercaya (Otoritas Sertifikat) untuk memverifikasi keasliannya.</li><li>Handshake (Jabat Tangan): Selama proses jabat tangan SSL/TLS, klien dan server bertukar informasi untuk menegosiasikan algoritme enkripsi dan parameter lain untuk koneksi aman.</li><li>Encryption (Enkripsi): Setelah koneksi aman dibuat, data dienkripsi menggunakan algoritme yang disepakati dan dapat ditransmisikan dengan aman antara klien dan server.</li></ul>

Saat membuat aplikasi dan layanan berbasis internet, penting untuk memahami cara kerja SSL/TLS dan untuk memastikan bahwa aplikasi Anda dirancang untuk menggunakan SSL/TLS saat mengirimkan data sensitif seperti kredensial login, informasi pembayaran, dan data pribadi lainnya. Anda juga harus memastikan bahwa Anda mendapatkan dan memelihara sertifikat SSL/TLS yang valid untuk server Anda, dan bahwa Anda mengikuti praktik terbaik untuk mengonfigurasi dan mengamankan koneksi SSL/TLS Anda. Dengan melakukannya, Anda dapat membantu melindungi data pengguna dan memastikan integritas dan kerahasiaan komunikasi aplikasi Anda melalui internet.
</details>

<details>
<summary>Masa Depan: Tren dan Teknologi yang Muncul</summary>
Internet terus berkembang, dan teknologi serta tren baru muncul setiap saat. Sebagai pengembang, penting untuk tetap mengikuti perkembangan terbaru untuk membangun aplikasi dan layanan yang inovatif dan efektif.

Berikut adalah beberapa tren dan teknologi baru yang membentuk masa depan internet:

* 5G: 5G adalah generasi terbaru dari teknologi jaringan seluler, menawarkan kecepatan yang lebih cepat, latensi yang lebih rendah, dan kapasitas yang lebih besar daripada generasi sebelumnya. Diharapkan untuk memungkinkan kasus penggunaan dan aplikasi baru, seperti kendaraan otonom dan operasi jarak jauh.

* Internet of Things (IoT): IoT mengacu pada jaringan perangkat fisik, kendaraan, peralatan rumah tangga, dan objek lain yang terhubung ke internet dan dapat bertukar data. Saat IoT terus berkembang, diharapkan akan merevolusi industri seperti perawatan kesehatan, transportasi, dan manufaktur.

* Kecerdasan Buatan / Artificial Intelligence (AI): Teknologi AI seperti pembelajaran mesin dan pemrosesan bahasa alami sudah digunakan untuk mendukung berbagai aplikasi dan layanan, mulai dari asisten suara hingga deteksi penipuan. Seiring dengan kemajuan AI, diharapkan akan memungkinkan kasus penggunaan baru dan mentransformasi industri seperti perawatan kesehatan, keuangan, dan pendidikan.

* Blockchain: Blockchain adalah teknologi ledger terdistribusi yang memungkinkan transaksi yang aman dan terdesentralisasi. Ini digunakan untuk mendukung berbagai aplikasi, dari cryptocurrency hingga manajemen rantai pasokan.

* Edge computing: Edge computing mengacu pada pemrosesan dan penyimpanan data at the edge of the network, bukan di pusat data centers. Hal ini diharapkan dapat mengaktifkan kasus dan aplikasi penggunaan baru, seperti real-time analytics dan low-latency applications.

Dengan terus mengikuti perkembangan ini serta tren dan teknologi baru lainnya, Anda dapat memastikan bahwa aplikasi dan layanan Anda dibuat untuk memanfaatkan kemampuan terbaru dan menawarkan pengalaman terbaik bagi pengguna Anda.
</details>

<details>
<summary>Kesimpulan</summary>
Dan itu membawa kita ke akhir artikel ini. Kami telah membahas banyak hal, jadi mari luangkan waktu sejenak untuk meninjau apa yang telah kami pelajari:

* Internet adalah jaringan global komputer yang saling terhubung yang menggunakan seperangkat protokol komunikasi standar untuk bertukar data.

* Internet bekerja dengan menghubungkan perangkat dan sistem komputer bersama-sama menggunakan protokol standar, seperti IP dan TCP.
* Inti dari internet adalah jaringan global router yang saling terhubung yang mengarahkan lalu lintas antara perangkat dan sistem yang berbeda.
* Konsep dasar dan terminologi yang perlu Anda pahami termasuk paket, router, alamat IP, nama domain, DNS, HTTP, HTTPS, dan SSL/TLS.
* Protokol memainkan peran penting dalam memungkinkan komunikasi dan pertukaran data melalui internet, memungkinkan perangkat dan sistem dari berbagai produsen dan vendor untuk berkomunikasi dengan mulus.

Saya harap artikel ini bermanfaat bagi Anda. Jika Anda memiliki pertanyaan atau komentar, jangan ragu untuk meninggalkannya di bawah. Terima kasih sudah membaca!
</details>


Video bagaimana internet bekerja : [How the Internet Works in 5 Minutes](https://www.youtube.com/watch?v=7_LPdttKXPc)

*Source* : [https://cs.fyi/guide/how-does-internet-work#introduction-to-the-internet](https://cs.fyi/guide/how-does-internet-work#introduction-to-the-internet)

*Thanks To* : [roadmap.sh](https://roadmap.sh/)


[Home](README.md)
[Back](1_pengantar_web_programing.md)
[Next](3_website_dan_halaman_web.md)


