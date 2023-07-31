# Apa perbedaan antara webpage, website, web server, dan search engine?
Kami akan membahas istilah dan teknologi ini secara lebih mendetail saat kami menjelajahi lebih jauh, tetapi definisi singkat ini akan menjadi awal yang baik untuk Anda:

- webpage/halaman web
Dokumen yang dapat ditampilkan di browser web seperti Firefox, Google Chrome, Opera, Microsoft Edge, atau Apple Safari. Ini juga sering disebut hanya "halaman".

- website/situs web
Kumpulan halaman web yang dikelompokkan bersama dan biasanya dihubungkan bersama dalam berbagai cara. Sering disebut "situs web" atau "situs".

- web server/server web
Komputer yang menghosting situs web di Internet.

- search engine/mesin pencari
Layanan web yang membantu Anda menemukan halaman web lain, seperti Google, Bing, Yahoo, atau DuckDuckGo. Mesin pencari biasanya diakses melalui browser web (mis. Anda dapat melakukan pencarian mesin pencari langsung di bilah alamat Firefox, Chrome, dll.) atau melalui halaman web (mis. bing.com atau duckduckgo.com ).

Mari kita lihat analogi sederhana — perpustakaan umum. Inilah yang biasanya Anda lakukan ketika mengunjungi perpustakaan:

1. Temukan indeks pencarian dan cari judul buku yang Anda inginkan.
2. Catat nomor katalog buku tersebut.
3. Buka bagian tertentu yang berisi buku tersebut, temukan nomor katalog yang tepat, dan dapatkan bukunya.

Mari bandingkan perpustakaan dengan server web:

* Perpustakaan itu seperti server web. Ini memiliki beberapa bagian, yang mirip dengan server web yang menghosting banyak situs web.
* Bagian yang berbeda (sains, matematika, sejarah, dll.) di perpustakaan seperti situs web. Setiap bagian seperti situs web unik (dua bagian tidak berisi buku yang sama).
* Buku-buku di setiap bagian seperti halaman web. Satu situs web mungkin memiliki beberapa halaman web, misalnya bagian Sains (situs web) akan memiliki buku tentang panas, suara, termodinamika, statika, dll. (halaman web). Halaman web masing-masing dapat ditemukan di lokasi unik (URL).
* Indeks pencarian seperti mesin pencari. Setiap buku memiliki lokasi uniknya sendiri di perpustakaan (dua buku tidak dapat disimpan di tempat yang sama) yang ditentukan oleh nomor katalog.

## webpage / halaman web

Halaman web adalah dokumen sederhana yang dapat ditampilkan oleh [browser](5_web_browser.md) . Dokumen semacam itu ditulis dalam bahasa [HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML) (yang kami lihat lebih detail di [artikel lain](https://developer.mozilla.org/en-US/docs/Web/HTML)). Halaman web dapat menyematkan berbagai jenis sumber daya yang berbeda seperti:

* style information — mengontrol tampilan dan nuansa halaman
* scripts — yang menambahkan interaktivitas ke halaman
* media — images, sounds, and videos.

> Catatan: Browser juga dapat menampilkan dokumen lain seperti file PDF atau gambar, tetapi istilah halaman web secara khusus mengacu pada dokumen HTML. Kalau tidak, kami hanya menggunakan istilah document.

Semua halaman web yang tersedia di web dapat dijangkau melalui alamat unik. Untuk mengakses halaman, cukup ketikkan alamatnya di bilah alamat browser Anda:

![webpage](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines/web-page.jpg)

## website / situs web

Situs web adalah kumpulan halaman web yang ditautkan (ditambah sumber daya terkaitnya) yang berbagi nama domain unik. Setiap halaman web dari situs web tertentu menyediakan tautan eksplisit—sering kali dalam bentuk bagian teks yang dapat diklik—yang memungkinkan pengguna berpindah dari satu halaman situs web ke halaman lainnya.

Untuk mengakses situs web, ketikkan nama domainnya di bilah alamat browser Anda, dan browser akan menampilkan halaman web utama situs web, atau beranda / homepage (sering disebut sebagai "home"):

![website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines/web-site.jpg)

Perhatikan bahwa Anda juga dapat memiliki situs web satu halaman : situs yang terdiri dari satu halaman web yang diperbarui secara dinamis dengan konten baru bila diperlukan.

## web server / server web

Server web adalah komputer yang menghosting satu atau lebih situs web . "Hosting" berarti semua halaman web dan file pendukungnya tersedia di komputer itu. Server web akan mengirimkan halaman web apa pun dari situs web yang dihostingnya ke browser pengguna mana pun, sesuai permintaan pengguna.

Jangan bingung antara situs web dan server web . Misalnya, jika Anda mendengar seseorang berkata, "Situs web saya tidak merespons", itu sebenarnya berarti server web tidak merespons dan oleh karena itu situs web tidak tersedia. Lebih penting lagi, karena server web dapat menghosting banyak situs web, istilah server web tidak pernah digunakan untuk menunjuk situs web, karena dapat menyebabkan kebingungan besar. Dalam contoh kami sebelumnya, jika kami mengatakan, "Server web saya tidak merespons", itu berarti beberapa situs web di server web tersebut tidak tersedia.

## search engine

Mesin pencari adalah sumber umum kebingungan di web. Mesin pencari adalah jenis situs web khusus yang membantu pengguna menemukan halaman web dari situs web lain .

Ada banyak di luar sana: [Google](https://www.google.com/) , [Bing](https://www.bing.com/) , [Yandex](https://yandex.com/) , [DuckDuckGo](https://duckduckgo.com/) , dan banyak lagi. Ada yang generik, ada yang khusus tentang topik tertentu. Gunakan mana yang Anda suka.

Banyak pemula di web membingungkan mesin pencari dan browser. Mari kita perjelas: Browser adalah perangkat lunak yang mengambil dan menampilkan halaman web; mesin pencari adalah situs web yang membantu orang menemukan halaman web dari situs web lain. Kebingungan muncul karena, pertama kali seseorang meluncurkan browser, browser tersebut menampilkan beranda mesin pencari. Ini masuk akal, karena, tentu saja, hal pertama yang ingin Anda lakukan dengan browser adalah mencari halaman web untuk ditampilkan. Jangan bingung infrastruktur (misalnya, browser) dengan layanan (misalnya, mesin pencari). Perbedaannya akan sedikit membantu Anda, tetapi bahkan beberapa profesional berbicara dengan longgar, jadi jangan merasa cemas.

Berikut adalah contoh Firefox yang menampilkan kotak pencarian Google sebagai halaman awal default:

![google](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines/search-engine.jpg)


source : [mdn_web_docs](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines)

*Thanks To* : (roadmap.sh)[https://roadmap.sh/]

[Home](README.md)
[Back](2_cara_kerja_internet.md)
[Next](4_web_server.md)